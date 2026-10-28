---
version: "alpha"
name: "❖ Controls — DesignBridge"
description: "Design system specification generated from ❖ Controls"
components:
  radiobutton:
    width: 1020px
    height: 648px
    state: "Normal | Hover | Disabled"
    checked: "False | True"
    label: "True | False"
  radiobutton-box:
    width: 460px
    height: 560px
    state: "Disabled | Normal | Hover"
    checked: "True | False"
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
- **Component sets**: 2

## Components

> Replicate structures exactly. Honour variant property names for interactive states.

### Variant Sets

#### Radiobutton
*Page: Radiobutton*
> ✅ Current  🟢 Storybook: HoffRadio

- **Total variants**: 12
- **Frame size**: 1020 × 648px
- **Variant properties**:
  - `State: Normal | Hover | Disabled`
  - `Checked: False | True`
  - `Label: True | False`
- **Sample variant names**: `State=Normal, Checked=False, Label=True` · `State=Normal, Checked=False, Label=False` · `State=Normal, Checked=True, Label=True` · `State=Normal, Checked=True, Label=False` · `State=Hover, Checked=False, Label=True` · `State=Hover, Checked=False, Label=False` · `State=Hover, Checked=True, Label=True` · `State=Hover, Checked=True, Label=False`

**Component anatomy** (default variant):

```
└─ Component "State=Normal, Checked=False, Label=True" (120×52) [row, gap:12px, pad:6px 0px]
  ├─ Instance "Radiobutton box" (20×20) [row, align:center / center]
    ├─ Vector "Mark"
  ├─ Frame "Container" (88×40) [column, gap:4px]
    ├─ Text "Label" → "Label"
    ├─ Text "Description" → "Description"
```

**Interactive state map:**

```css
/* Component: Radiobutton */
/* Variant property: State */
.radiobutton[data-state="normal"] {
  /* State: Normal */
}
.radiobutton:hover {
  /* State: Hover */
}
.radiobutton:disabled {
  /* State: Disabled */
}
```

#### Radiobutton box
*Page: Radiobutton*
- **Total variants**: 6
- **Frame size**: 460 × 560px
- **Variant properties**:
  - `State: Disabled | Normal | Hover`
  - `Checked: True | False`
- **Sample variant names**: `State=Normal, Checked=False` · `State=Hover, Checked=False` · `State=Disabled, Checked=False` · `State=Normal, Checked=True` · `State=Hover, Checked=True` · `State=Disabled, Checked=True`

**Component anatomy** (default variant):

```
└─ Component "State=Normal, Checked=False" (20×20) [row, align:center / center]
  ├─ Vector "Mark" (10×10)
```

**Interactive state map:**

```css
/* Component: Radiobutton box */
/* Variant property: State */
.radiobutton-box:disabled {
  /* State: Disabled */
}
.radiobutton-box[data-state="normal"] {
  /* State: Normal */
}
.radiobutton-box:hover {
  /* State: Hover */
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