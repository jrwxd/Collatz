# Collatz 3D Graph

A minimal Three.js visualization of the Collatz map: one sphere per integer, edges for n -> f(n) (3n + 1). Animate the sweep from 1..N and watch the graph grow.

## Usage
- Open index.html in any modern browser (no build step required).
- Set the max N, then hit **Rebuild graph**.
- Press **Play** to animate edge drawing (delay slider controls speed). **Reset** clears the edges.

## GitHub Pages
Static ready. To host:
1) Push to `main`.
2) In GitHub: Settings → Pages → Source: `main` / root. Save.
3) Visit `https://<username>.github.io/Collatz/` after it builds.