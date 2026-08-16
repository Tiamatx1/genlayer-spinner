# GenLayer Consensus Orbit Spinner

A web-ready animated SVG spinner designed for the **Design the GenLayer Spinner** community mission.

## Concept

**Consensus Orbit** represents validator nodes orbiting and aligning around a shared GenLayer core. The motion is deliberately simple so the mark remains recognizable at small sizes while still feeling distinctly GenLayer.

## Requirements covered

- Original animated spinner concept
- Smooth infinite loop
- Web-ready SVG
- Works on light and dark backgrounds
- Clear at small sizes
- GenLayer-inspired geometric identity
- `prefers-reduced-motion` support
- No external runtime dependencies

## Files

- `genlayer-spinner.svg` — reusable animated SVG asset
- `index.html` — local/live preview with light/dark toggle and size examples

## Usage

Embed the SVG directly:

```html
<img src="./genlayer-spinner.svg" width="32" height="32" alt="Loading">
```

Or use the SVG file inline in an HTML document when CSS customization is needed.

## Animation

The orbit rotates continuously while the surrounding nodes pulse with staggered timing. The SVG includes a reduced-motion fallback for accessibility.

## Preview

Open `index.html` in a browser, or enable GitHub Pages for the repository to create a public demo URL.

## Mission

Created for GenLayer Portal's **Design the GenLayer Spinner** mission, August 2026.
