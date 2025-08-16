
# DitherLab (Ready-to-Run)

A minimal, monochrome dithering tool. Upload (click, drag & drop, or paste), choose an algorithm/palette, tweak blur/noise, and download the result.

## Quick Start (macOS / Windows)

1. Install **Node.js (LTS)**: https://nodejs.org/en/download
2. Open this folder in **VS Code** (or Terminal).
3. In the folder, run:
   ```bash
   npm install
   npm run dev
   ```
4. Open the printed local URL in your browser (e.g. http://localhost:5173).

## Features
- Algorithms: Threshold, Ordered (Bayer 2/4/8/16), Random, Floyd–Steinberg, Atkinson, JJN, Stucki
- Palettes: 1‑bit, 4/8‑gray, Game Boy (DMG), Sepia 4, Blueprint 4, C64 (subset)
- Progressive blur and noise
- Scale, invert, download

## Tailwind
Already configured. Global styles in `src/index.css`.
