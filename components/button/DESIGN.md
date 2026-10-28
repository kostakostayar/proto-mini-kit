---
version: "alpha"
name: "❖ Controls — DesignBridge"
description: "Design system specification generated from ❖ Controls"
components:
  button:
    width: 4455px
    height: 2340px
    type: "Primary | Secondary | Ghost | Grey | ⛔Accent dark | ⛔Accent light"
    size: "Lg | Md | Sm | Xs"
    state: "Normal | Hover | Active | Disabled"
    density: "Normal | Tight"
    -square: "false | true"
  button-icon:
    width: 4455px
    height: 2327px
    type: "Primary | Secondary | Ghost | Grey | ⛔Accent dark | ⛔Accent light"
    size: "Lg | Md | Sm | Xs"
    state: "Normal | Hover | Active | Disabled"
    density: "Normal | Tight"
    square: "false | true"
  button-2rows:
    width: 2295px
    height: 2340px
    type: "Primary | Secondary | Ghost | ⛔Accent dark | ⛔Accent light"
    size: "Lg | Md"
    state: "Normal | Hover | Active | Disabled"
    density: "Normal | Tight"
    -square: "false | true"
---

# ❖ Controls — DesignBridge

> **AI AGENT INSTRUCTIONS — READ FIRST, APPLY TO ALL OUTPUT**
>
> This file is the complete visual specification for **"❖ Controls — DesignBridge"**.
> The YAML front matter above contains the normative design tokens. The sections below explain how to apply them.
> Apply every rule to every line of UI, HTML, CSS, JSX, or component code you generate.
>
> 1. **Colours** — Use only exact hex values or `var(--token)` names from this file. No substitutions.
> 2. **Typography** — Match font family, weight, size, line-height exactly.
> 3. **Spacing** — Use only values from the spacing/sizing token tables.
> 4. **Border radius** — Use only the defined radius tokens.
> 5. **Components** — Mirror defined structures. Honour variant property names exactly.
> 6. **Shadows** — Apply defined elevation styles. Do not invent shadows.
> 7. **Themes** — Use the `themes` block for dark mode / multi-theme support. Apply correct mode tokens.
> 8. **Unknowns** — If a visual decision is not defined here, ask before inventing it.

## How to Use

| Platform | Instructions |
|----------|-------------|
| **Claude Design** | Upload as design asset: *Add assets → DESIGN.md*, or attach in chat: *"Create a design system from this DESIGN.md"* |
| **Google Stitch** | Upload via *Design System → DESIGN.md* |
| **Claude Code** | Place in project root, reference as `@DESIGN.md` |
| **Cursor / Windsurf** | Add to context, prompt: *"Follow @DESIGN.md for all visual decisions"* |
| **Gemini CLI** | Place in project root — auto-detected by Gemini agents |
| **Antigravity** | Import via *Design System settings* |
| **GitHub Copilot** | Place in project root for automatic context |
| **OpenAI Codex** | Paste as system context before UI tasks |
| **Any LLM** | Paste at top of session as system context |

```
You have the design system for "❖ Controls — DesignBridge" in DESIGN.md. Follow it precisely for ALL visual decisions. No deviations.
```

## Overview

Design system extracted from **❖ Controls**. This specification defines the complete visual language including colour palette, typography scale, spacing system, and component catalogue.

## Design System Summary

- **Source**: ❖ Controls · Generated: 2026-10-23
- **Generator**: DesignOps Tools: DesignBridge v2.1 — [designops.tools](https://designops.tools)
- **Spec**: [google-labs-code/design.md](https://github.com/google-labs-code/design.md) (alpha)
- **Component sets**: 3

## Components

> Replicate structures exactly. Honour variant property names for interactive states.

### Variant Sets

#### Button
*Page: Button*
> ✅ Current  🟢 Storybook: HoffButton

- **Total variants**: 384
- **Frame size**: 4455 × 2340px
- **Variant properties**:
  - `Type: Primary | Secondary | Ghost | Grey | ⛔Accent dark | ⛔Accent light`
  - `Size: Lg | Md | Sm | Xs`
  - `State: Normal | Hover | Active | Disabled`
  - `Density: Normal | Tight`
  - `⛔ Square: false | true`
- **Sample variant names**: `Type=Primary, Size=Lg, State=Normal, Density=Normal, ⛔ Square=true` · `Type=Primary, Size=Lg, State=Normal, Density=Tight, ⛔ Square=true` · `Type=Primary, Size=Md, State=Normal, Density=Normal, ⛔ Square=true` · `Type=Primary, Size=Md, State=Normal, Density=Tight, ⛔ Square=true` · `Type=Primary, Size=Sm, State=Normal, Density=Normal, ⛔ Square=true` · `Type=Primary, Size=Xs, State=Normal, Density=Normal, ⛔ Square=true` · `Type=Primary, Size=Sm, State=Normal, Density=Tight, ⛔ Square=true` · `Type=Primary, Size=Xs, State=Normal, Density=Tight, ⛔ Square=true`

**Component anatomy** (default variant):

```
└─ Component "Type=Primary, Size=Lg, State=Normal, Density=Normal, ⛔ Square=true" (153×68) [row, gap:8px, pad:20px 28px, align:center / center]
  ├─ Instance "ic-shopping-cart-3" (28×28)
    ├─ Vector "Vector"
  ├─ Text "Button" (61×32) → "Button"
```

**Interactive state map:**

```css
/* Component: Button */
/* Variant property: State */
.button[data-state="normal"] {
  /* State: Normal */
}
.button:hover {
  /* State: Hover */
}
.button:active {
  /* State: Active */
}
.button:disabled {
  /* State: Disabled */
}
```

#### Button icon
*Page: Button*
> ✅ Current  🟢 Storybook: HoffButton

- **Total variants**: 384
- **Frame size**: 4455 × 2327px
- **Variant properties**:
  - `Type: Primary | Secondary | Ghost | Grey | ⛔Accent dark | ⛔Accent light`
  - `Size: Lg | Md | Sm | Xs`
  - `State: Normal | Hover | Active | Disabled`
  - `Density: Normal | Tight`
  - `⛔Square: false | true`
- **Sample variant names**: `Type=Primary, Size=Lg, State=Normal, Density=Normal, ⛔Square=true` · `Type=Primary, Size=Lg, State=Normal, Density=Normal, ⛔Square=false` · `Type=Primary, Size=Lg, State=Normal, Density=Tight, ⛔Square=true` · `Type=Primary, Size=Lg, State=Normal, Density=Tight, ⛔Square=false` · `Type=Primary, Size=Md, State=Normal, Density=Normal, ⛔Square=true` · `Type=Primary, Size=Md, State=Normal, Density=Normal, ⛔Square=false` · `Type=Primary, Size=Md, State=Normal, Density=Tight, ⛔Square=true` · `Type=Primary, Size=Md, State=Normal, Density=Tight, ⛔Square=false`

**Component anatomy** (default variant):

```
└─ Component "Type=Primary, Size=Lg, State=Normal, Density=Normal, ⛔Square=true" (68×68) [row, pad:20px, align:center / center]
  ├─ Instance "ic-shopping-cart-3" (28×28)
    ├─ Vector "Vector"
```

**Interactive state map:**

```css
/* Component: Button icon */
/* Variant property: State */
.button-icon[data-state="normal"] {
  /* State: Normal */
}
.button-icon:hover {
  /* State: Hover */
}
.button-icon:active {
  /* State: Active */
}
.button-icon:disabled {
  /* State: Disabled */
}
```

#### Button 2rows
*Page: Button*
> ✅ Current  🟢 Storybook: HoffButton

- **Total variants**: 160
- **Frame size**: 2295 × 2340px
- **Variant properties**:
  - `Type: Primary | Secondary | Ghost | ⛔Accent dark | ⛔Accent light`
  - `Size: Lg | Md`
  - `State: Normal | Hover | Active | Disabled`
  - `Density: Normal | Tight`
  - `⛔ Square: false | true`
- **Sample variant names**: `Type=Primary, Size=Lg, State=Normal, Density=Normal, ⛔ Square=true` · `Type=Secondary, Size=Lg, State=Normal, Density=Normal, ⛔ Square=true` · `Type=Ghost, Size=Lg, State=Normal, Density=Normal, ⛔ Square=true` · `Type=⛔Accent dark, Size=Lg, State=Normal, Density=Normal, ⛔ Square=true` · `Type=⛔Accent light, Size=Lg, State=Normal, Density=Normal, ⛔ Square=true` · `Type=Primary, Size=Lg, State=Normal, Density=Tight, ⛔ Square=true` · `Type=Secondary, Size=Lg, State=Normal, Density=Tight, ⛔ Square=true` · `Type=Ghost, Size=Lg, State=Normal, Density=Tight, ⛔ Square=true`

**Component anatomy** (default variant):

```
└─ Component "Type=Primary, Size=Lg, State=Normal, Density=Normal, ⛔ Square=true" (172×68) [column, gap:2px, pad:12px 28px, align:start / center]
  ├─ Text "Button text 1" (116×24) → "Button text 1"
  ├─ Text "Button text 2" (86×16) → "Button text 2"
```

**Interactive state map:**

```css
/* Component: Button 2rows */
/* Variant property: State */
.button-2rows[data-state="normal"] {
  /* State: Normal */
}
.button-2rows:hover {
  /* State: Hover */
}
.button-2rows:active {
  /* State: Active */
}
.button-2rows:disabled {
  /* State: Disabled */
}
```

## Design Rules — Mandatory for AI Agents

| Category | Rule |
|----------|------|
| Colours | Use only tokens defined above. Always output as `var(--token)`. Never hard-code. |
| Typography | Match family, weight, size, line-height exactly from the table above. |
| Spacing | Use only spacing token values. No arbitrary numbers. |
| Radius | Use only border-radius tokens. No arbitrary values. |
| Shadows | Use only defined elevation/effect styles. |
| Components | Replicate structures. Honour variant property names. |
| HTML | Output semantic HTML5 with ARIA roles. All components responsive by default. |
| Unknowns | If a decision is not defined here: ask the user, do not invent. |

---

*Generated on 2026-10-23 by **DesignOps Tools: DesignBridge v2.1** from "❖ Controls".*
*Spec: [google-labs-code/design.md](https://github.com/google-labs-code/design.md) · Format version: alpha*
*[designops.tools](https://designops.tools) — Bridge your Figma design system to any AI tool.*