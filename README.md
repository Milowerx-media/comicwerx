# Comicwerx

A lightweight, zero-dependency comic book rough layout, thumbnailing, and lettering placement web application built with vanilla HTML5 Canvas, CSS, and JavaScript.

## Features

- Exact Custom Page Dimensions: Configure custom decimal widths and heights in Inches (in), Millimeters (mm), or Pixels (px), set custom DPI/PPI, and define exact Bleed, Safe Margin, and Panel Gutter measurements.
- Dynamic Panel Grid & Frame Editor: Generate 1- to 9-panel layouts, split panels horizontally or vertically, add floating inset panels, drag-to-reposition or resize frames, and attach per-panel shot/script notes.
- Clipped Per-Panel Rough Sketching: Sketch rough thumbnails with Non-Photo Blue (#4da6ff), Layout Red, Graphite, Ink Black, or custom swatches using the Pencil, Straight Line, Box, Oval, and Eraser tools—automatically clipped inside the active panel borders.
- Dial-In Word Balloons with Bendable Tails: Place Speech Balloons, Thought Clouds, Shout Bursts, and Narrative Caption Boxes. Aim tails using the canvas tip handle or polar angle/reach inputs, and bend or bow tails smoothly along a quadratic Bezier curve using the amber midpoint diamond or the Tail Bend slider.
- Local Export & Save: Export clean PNG pages (with an option to hide Non-Photo Blue rough lines) and save/reload layouts locally as .json files.

## Quick Start

Because Comicwerx has zero build steps or external dependencies, you can run it immediately:

1. Clone the repository:
   git clone https://github.com/YOUR_USERNAME/comicwerx.git
   cd comicwerx

2. Open index.html directly in any modern browser, or serve it locally:
   python3 -m http.server 8080

## Deploying to GitHub Pages

1. Push this repository to GitHub.
2. Open Settings -> Pages in your GitHub repository.
3. Under Build and deployment, set Source to Deploy from a branch, select main and / (root), and click Save.
4. Your live app will be published at https://YOUR_USERNAME.github.io/comicwerx/.

## License

MIT License — see LICENSE for details.
