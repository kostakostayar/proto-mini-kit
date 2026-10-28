# Prototype UI Kit

A small, dependency-free library for assembling static, interactive interface prototypes. It uses plain HTML, CSS, vanilla JavaScript, and SVG; there is no build step.

## Open the showcase

Open `index.html` directly in a browser. The page uses local CSS and does not fetch HTML fragments, so it also works from `file://`.

## Project map

- `index.html` — local showcase and component index. New component examples should be added here.
- `tokens/tokens.css` — optional shared design tokens. Components should remain usable when copied without the token file, or clearly document the tokens they need.
- `components/README.md` — component index and rules for adding components.
- `docs/AI_GUIDE.md` — compact workflow for AI-assisted component work and Figma handoff.

## Component approach

Each component gets its own folder only when it is added. Include only the files it needs: usually CSS and an HTML example; add JavaScript only for actual interaction. A short `manifest.json` is useful when a component has a non-obvious API, states, or dependencies. Keep examples and source close together, use no hidden project-specific dependencies, and document whether shared tokens are required.

## Use in another project

Copy the component's required files and its example. If it uses shared tokens, copy `tokens/tokens.css` or replace its token references with local values. Include the component's JavaScript only when its behavior requires it. No network or runtime loader is needed.

## Adding components

Start with the [AI guide](docs/AI_GUIDE.md). Once a component is implemented, add a short entry and a direct example link in `index.html` and update the component index above.
