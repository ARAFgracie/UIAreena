# UI Areena

UI Areena is a backend-free, GitHub Pages-ready UI reference library for designers and developers.

## Pages

- `index.html` — Home
- `buttons.html` — 40+ distinct button concepts
- `navbar.html` — 39+ distinct navbar concepts
- `forms.html` — 32+ distinct form concepts
- `cards.html` — 38+ distinct card concepts
- `ui-library.html` — 46+ distinct UI primitive concepts
- `icons.html` — 360 inline SVG icons
- `architecture.html` — 30 website architecture / connection flows
- `prompts.html` — 34 engineered website-building prompts

## Important implementation fixes

- Every library preview now mounts its recipe CSS inside an isolated Shadow DOM, so preview CSS cannot leak between cards and the actual visual recipe is rendered.
- Live accent color and radius controls rebuild the isolated preview.
- Copied snippets retain their selected accent and radius variables.
- Drawer navigation locks page scrolling, closes on outside click/scrim, supports Escape, and has basic keyboard focus looping.
- Dark/light theme is shared through `localStorage`.
- All pages use the UI Areena brand and shared navigation.
- No backend is required.

## Icons

`icons.html` contains 360 self-contained SVG glyphs. Each icon can be searched, filtered by category, previewed with live color, and copied as standalone SVG.

The icon artwork/data is sourced from the Font Awesome Free icon packages available in the build environment. If you redistribute the icon artwork, retain the applicable Font Awesome Free licensing/attribution requirements.
