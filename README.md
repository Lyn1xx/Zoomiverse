# Zoomiverse — Prototype for NASA Space Apps "Embiggen Your Eyes!"

## What it is
Zoomiverse is a small web prototype that demonstrates zooming into very large images (using OpenSeadragon), adding annotations/pins, and exporting/importing annotation data.

## How to run
1. Download the files and unzip.
2. Open `index.html` in a modern browser (Chrome/Firefox/Edge).
3. Click a sample image from the left panel. Use Add Pin to place annotations.

## Notes
- Annotations are stored locally in browser `localStorage`.
- To make the app use NASA images dynamically, call NASA Image + Video Library API and provide tile or deep-zoom pyramids.
- To share annotations between users, add a backend (e.g., Firebase) to store and serve JSON.

## Future improvements
- Support real NASA tile pyramids / IIIF / deep-zoom formats.
- Side-by-side and overlay comparison mode.
- AI search: find regions by textual prompts.
- Collaborative annotations (real-time).
