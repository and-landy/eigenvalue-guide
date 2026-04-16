# Eigenvalue Field Guide

Interactive classification guide for **2×2 linear ODE systems** — eigenvalues, phase portraits, and general solutions.

二维线性系统特征值分类速查手册

## Features

- **8 classification types** with theory, formulas, and phase portraits
- **Worked examples** with full LaTeX derivations
- **Interactive calculator** — input any 2×2 matrix, get instant classification
- **Dark / Light theme** toggle
- **RK4-simulated** phase portraits
- **KaTeX** rendered mathematics

## Deploy

This is a single `index.html` file with no build step required. All dependencies load from CDNs.

### GitHub Pages

1. Clone this repo
2. Go to **Settings → Pages**
3. Set Source to **main** branch, root folder
4. Save — your site will be live at `https://USERNAME.github.io/eigenvalue-guide/`

### Local

Just open `index.html` in a browser.

## Tech

- React 18 (via CDN)
- KaTeX 0.16.9
- Babel Standalone (in-browser JSX compilation)
- Custom RK4 ODE solver for phase portraits
- Zero build tools, zero dependencies to install

## License

MIT
