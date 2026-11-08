# Catenary Cable Arch Suspension Canvas - Physics Simulator 2026

> **A browser-based physics simulator for exploring catenary cables and suspension arches with live curve, tension, and lowest-point visualizations.**

[![Platform](https://img.shields.io/badge/Platform-Web%20browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Unversioned-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/michaelneumann82/catenary-cable-arch-suspension-canvas-win-5645?style=flat-square)](https://github.com/michaelneumann82/catenary-cable-arch-suspension-canvas-win-5645)

---

<p align="center">
  <a href="https://michaelneumann82.github.io/catenary-cable-arch-suspension-canvas-win-5645/">
    <img src="https://img.shields.io/badge/Download-Catenary%20Cable%20Arch%20Suspension%20Canvas%20Latest-brightgreen?style=for-the-badge" alt="Download Catenary Cable Arch Suspension Canvas">
  </a>
</p>

> **[Direct Download - Catenary Cable Arch Suspension Canvas](https://michaelneumann82.github.io/catenary-cable-arch-suspension-canvas-win-5645/)**

---

[Download Latest Build](https://michaelneumann82.github.io/catenary-cable-arch-suspension-canvas-win-5645/)

---

## About Catenary Cable Arch Suspension Canvas

Catenary Cable Arch Suspension Canvas is a static web application for examining the shape and behavior of suspended cables and arch-like curves. It renders the simulation directly in a browser canvas, making it useful for visual study, demonstrations, and quick experimentation without a desktop installation.

The simulator provides interactive controls for sag and support distance, along with visual markers for the lowest point and support tension vectors. Users can switch between catenary and inverted catenary arch modes to compare related forms in one focused interface.

---

## Features

- Live visualization of a catenary curve
- Support tension vector display
- Marker for the curve's lowest point
- Adjustable sag value
- Adjustable distance between supports
- Catenary and inverted catenary arch modes
- Keyboard-based controls
- Static single-page application that runs in a modern web browser

---

## Installation

Clone the repository:

```bash
git clone https://github.com/michaelneumann82/catenary-cable-arch-suspension-canvas-win-5645.git
cd REPO
```

Because the project is a static SPA, no package installation or build step is required for basic use. Open the project's main HTML entry file in a modern web browser, or serve the directory locally with any static HTTP server.

For a local server using Python:

```bash
python3 -m http.server
```

Then open the local address shown by the server.

---

## Usage

1. Launch the application in a web browser.
2. Adjust the sag parameter to change the cable's curvature.
3. Modify the support distance to explore different spans.
4. Observe the real-time catenary rendering.
5. Use the displayed vectors to inspect support tension direction.
6. Locate the highlighted lowest point.
7. Switch between catenary and inverted catenary arch modes.
8. Use the available keyboard controls for interactive adjustments.

---

## Configuration

The simulator is configured through its in-browser controls and keyboard interactions. There is no separate configuration file or backend service required for the static application.

Use the interface to change:

- Sag
- Support distance
- Curve or arch mode

---

## Requirements

- A modern web browser with HTML canvas support
- JavaScript enabled
- Local storage space sufficient for the repository files
- Optional local static HTTP server for serving the application during development

The project is delivered as a static web application and does not require a runtime service or database.

---

## FAQ

### Is an installation package required?

No. Download or clone the static project files and open the application in a compatible web browser.

### Can I run it without an internet connection?

Yes, once the project files are available locally, the static application can be opened locally, subject to browser file-loading behavior.

### How do I change the cable shape?

Adjust the sag and support-distance controls. The curve is redrawn as the parameters change.

### What does the lowest-point marker show?

It identifies the lowest point of the currently displayed catenary curve.

### What are the arch modes for?

The simulator includes both catenary and inverted catenary forms so their different orientations can be viewed and compared.

### What should I do if the interface does not respond?

Confirm that JavaScript is enabled and try serving the repository through a local HTTP server instead of opening the HTML file directly. Also verify that you are using a current browser.

### How are updates delivered?

Updates are published through the project repository and its web deployment at [https://michaelneumann82.github.io/catenary-cable-arch-suspension-canvas-win-5645/](https://michaelneumann82.github.io/catenary-cable-arch-suspension-canvas-win-5645/).

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
