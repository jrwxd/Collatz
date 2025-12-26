# Collatz Visualizer

A minimal, dependency-free Collatz (3n + 1) visualizer with both a 2D plot and a Three.js sweep. Open `index.html` in a browser, enter a starting integer, and watch the sequence animate with stats (steps to 1, peak value, current value, and length). The 3D view counts from 1 -> N and draws edges for each Collatz hop as it goes.

## Usage
- Open index.html in any modern browser (no build step required).
- 2D: pick a starting number or tap a preset, then hit **Visualize**. Adjust the delay slider to change animation speed.
- 3D: set the sweep upper bound and click **Play 3D sweep** to watch 1..N connect via Collatz edges. Speed uses the same delay slider.

## GitHub Pages
This repo is already static; to host it on GitHub Pages:
1) Push to `main` (or your chosen branch).
2) In GitHub: Settings → Pages → set Source to `main` / root. Save.
3) Pages will publish to `https://<username>.github.io/Collatz/` (or your org URL). No build step required.