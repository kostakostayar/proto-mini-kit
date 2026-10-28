# AI guide: add one component

## Figma handoff

1. Share the selected component/frame only, with its variants and relevant states. Do not export the full page or library.
2. Export a PNG screenshot at 1× (2× only if small details are hard to read). Include the component bounds and enough surrounding context to show spacing. Export icons or illustrations as SVG separately; keep multicolor brand artwork unchanged.
3. Provide a small JSON file with the component name, dimensions, layout direction/gap/padding, typography, colors, borders/radii, variants, interaction states, and behavior. Include only properties visible or confirmed in the reference. Example:

   ```json
   {
     "name": "Component name",
     "size": { "width": 240, "height": 48 },
     "layout": { "padding": [12, 16], "gap": 8 },
     "style": { "font": "…", "color": "…", "radius": 8 },
     "variants": [],
     "states": [],
     "behavior": []
   }
   ```

4. Put the files together in `work/figma/<component-name>/`: `reference.png`, `properties.json`, and any exported SVGs. Keep this handoff folder out of the component implementation unless those assets are actually needed.
5. Give the agent the screenshot, JSON, exported assets, this guide, and `tokens/tokens.css`. Add a brief note for anything the export cannot express, such as keyboard behavior or responsive rules.

## Compact implementation prompt

```text
Implement the Figma component in this repository using only the supplied reference files. First inspect the current project instructions and relevant tokens. Do not invent variants or behavior beyond the reference. Add a self-contained folder under components/<name>/ with only needed files (CSS, standalone example HTML, JS only if interaction requires it, and a concise manifest when useful). Keep styles scoped, make token dependencies explicit, and use local SVG files where provided. Add a short entry and example link to index.html. Do not add dependencies, a build step, a server, or unrelated components. At the end, summarize changed files and any reference details that remain ambiguous.
```

## Review checklist

- Compare the example with the reference at the same scale and check each supplied variant/state.
- Exercise the specified interaction with mouse and keyboard where applicable.
- Confirm the example opens directly from `file://` and that every linked local file exists.
- Add the component to the index and update its manifest when its API or dependencies change.
