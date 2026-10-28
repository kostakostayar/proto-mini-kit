# Component folders

## Component index

- [`button/`](button/example.html) — responsive action button using the exported Desktop/Mobile token values.
- [`check/`](check/example.html) — reusable native checkbox indicator.
- [`checkbox/`](checkbox/example.html) — accessible checkbox with optional label and description.
- [`icon/`](icon/example.html) — inline SVG icon with configurable pixel width and preserved artwork proportions.

Create a folder here for each component, using a short lowercase name such as `button/`.

Keep only what the component needs:

- `component.css` for styles;
- `example.html` for a standalone demonstration;
- `component.js` only when interaction needs JavaScript;
- `manifest.json` when a compact record of purpose, API, states, or dependencies helps someone reuse it.

Keep HTML understandable, scope CSS to the component, and avoid global resets or hidden dependencies. If the component references shared variables, identify the required token file in its manifest or README. Do not create placeholder files for unused formats.
