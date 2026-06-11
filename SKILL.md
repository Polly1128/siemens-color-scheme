---
name: siemens-color-scheme
description: Apply Siemens brand color scheme, key visuals, and design guidelines when writing frontend code. Use when the user explicitly asks for Siemens colors, Siemens design, Siemens branding, Siemens style, key visuals, or Siemens UI. Also when the user mentions Petrol, Siemens palette, Dayu UI, or Siemens Xcelerator. Based on Siemens Corporate Design specification (State: 2025-02-17).
---

# Siemens Design System

Apply Siemens brand design guidelines (State: 2025-02-17) when writing TailwindCSS or inline styles for UI components. Covers color scheme, key visuals, and interaction patterns.

## Color Hierarchy

**Primary colors**: Siemens Petrol, Bold Green, Bold Blue — represent brand identity.
**Primary backgrounds**: Deep Blue, White, Light Sand.

## Brand Primary: Siemens Petrol

**The core brand color is Petrol (#009999).** Always prefer Petrol over Tailwind's default blue.

- **Siemens Petrol** — Logo on light backgrounds, highlight words in key messages.
- **Bold Green** — Digital key visuals and UI components.
- **Bold Blue** — Digital key visuals and UI components.
- **Soft Green / Soft Blue** — Print adaptations of Bold Green / Bold Blue. Do NOT use in digital UI; use Bold Green / Bold Blue instead.

| Token | Hex | RGB | Digital Usage |
|-------|-----|-----|---------------|
| `primary` / `siemens-petrol` | `#009999` | 0 153 153 | Primary buttons, links, active states, logo |
| `primary-dark` / `siemens-petrol-dark` | `#007a7a` | 0 122 122 | Hover states on primary elements |
| `primary-light` / `light-petrol` | `#00c1b6` | 0 193 182 | Highlight color on dark backgrounds |
| `primary-soft` | `#e6f7f5` | 230 247 245 | Light backgrounds, selected row/item bg |
| `brand-bold-green` / `bold-green` | `#00ffb9` | 0 255 185 | Digital key visuals, UI components, gradients |
| `brand-green` / `soft-green` | `#00d7a0` | 0 215 160 | Print-only equivalent of Bold Green; in digital use for success states |
| `bold-blue` | `#00e6dc` | 0 230 220 | Digital key visuals, UI components, gradient endpoint |
| `soft-blue` | `#00bedc` | 0 190 220 | Print-only equivalent of Bold Blue |
| `deep-blue` | `#000028` | 0 0 40 | Primary background color (dark theme) |

## Background & Surface

| Token | Hex | RGB | Usage |
|-------|-----|-----|-------|
| `light-sand` / `content-bg` | `#f3f3f0` | 243 243 240 | Light background (default), pictures, illustrations |
| `sidebar-bg` / `white` | `#ffffff` | 255 255 255 | Sidebar, card backgrounds, pictures, illustrations |
| `deep-blue` | `#000028` | 0 0 40 | Default dark background across all media |
| `sidebar-active` | `#e6f7f5` | 230 247 245 | Active sidebar item background |

## Deep Blue Scale (Text & Gray)

The Deep Blue scale replaces Tailwind's default gray. Use these for all text, borders, and neutral surfaces.

| Token | Hex | RGB | Usage |
|-------|-----|-----|-------|
| `deep-blue-95` | `#0d0d33` | 13 13 51 | Near-black, deepest text |
| `deep-blue-90` | `#19193d` | 25 25 61 | Very dark text |
| `deep-blue-85` | `#262648` | 38 38 72 | Dark emphasis text |
| `deep-blue-80` | `#333353` | 51 51 83 | Headings, primary text |
| `deep-blue-70` | `#4c4c68` | 76 76 104 | Strong secondary text |
| `deep-blue-60` | `#66667e` | 102 102 126 | Secondary text, descriptions |
| `deep-blue-55` | `#737489` | 115 116 137 | Medium text |
| `deep-blue-50` | `#808099` | 128 128 153 | Mid-tone text |
| `deep-blue-40` | `#9999a9` | 153 153 169 | Placeholder, hint text |
| `deep-blue-30` | `#b3b3be` | 179 179 190 | Light hint text |
| `deep-blue-20` | `#ccccd4` | 204 204 212 | Disabled text, dividers |
| `deep-blue-10` | `#e5e5e9` | 229 229 233 | Subtle borders, input borders |
| `deep-blue-8` | `#ebebee` | 235 235 238 | Very light backgrounds |

## Border

| Token | Hex | Usage |
|-------|-----|-------|
| `border-light` / `deep-blue-10` | `#e5e5e9` | Subtle borders, input borders |
| `border-base` / `deep-blue-20` | `#ccccd4` | Default borders |

## Secondary Colors

For illustrations and infographics only. Do NOT use as primary UI colors.

| Token | Hex | RGB | Usage |
|-------|-----|-----|-------|
| `dark-sand` | `#aaaa96` | 170 170 150 | Muted neutral (illustration) |
| `soft-sand` | `#c5c5b8` | 197 197 184 | Subtle tint (illustration) |
| `bright-sand` | `#dfdfd9` | 223 223 217 | Light surface (illustration) |
| `dark-yellow` | `#f7c600` | 247 198 0 | Caution emphasis |
| `yellow` | `#ffd732` | 255 215 50 | Info highlights, attention |
| `soft-yellow` | `#ffe270` | 255 226 112 | Light yellow accent |
| `dark-green` | `#00646e` | 0 100 110 | Success emphasis |
| `green` | `#00af8e` | 0 175 142 | Success |
| `dark-blue` | `#00557c` | 0 85 124 | Deep blue accent |
| `blue` | `#0087be` | 0 135 190 | Secondary blue accent |

## Accent: Purple (Agent/AI)

| Token | Hex | RGB | Usage |
|-------|-----|-----|-------|
| `dark-purple` | `#553ba3` | 85 59 163 | Agent/AI elements, skill badges |
| `purple` | `#8055ff` | 128 92 255 | Agent highlights |
| `soft-purple` | `#b4a8ff` | 180 168 255 | Agent light backgrounds, skill tags |

## Special Purpose: Technics & Data

Red and orange for technical illustrations, diagrams, and color-blind differentiation. Do NOT use in top-level brand illustrations.

| Token | Hex | RGB | Usage |
|-------|-----|-----|-------|
| `red` | `#ef0137` | 239 1 55 | Errors, destructive actions, technical diagrams |
| `red-dark` | `#c40028` | 196 0 40 | Error hover states |
| `red-light` | `#ffecef` | 255 236 239 | Error background |
| `dark-orange` | `#ec6602` | 236 102 2 | Warning emphasis, technical diagrams |
| `orange` | `#ff9000` | 255 144 0 | Warnings, technical diagrams |

## Interaction Colors

Interactive elements use blue tones from the palette. CTA buttons use **Bold Dynamic Petrol** gradient to stand out.

| Element | Style |
|---------|-------|
| CTA button | `bg-gradient-petrol-bold text-white` |
| Interactive link | `text-siemens-petrol hover:text-siemens-petrol-dark` |
| Active/focus state | `border-brand-petrol ring-2 ring-primary-soft` |

## Corporate Gradients

| Name | Direction | Color A | Color B | Medium | Tailwind Usage |
|------|-----------|---------|---------|--------|----------------|
| Bold Dynamic Petrol | 135deg | `#00ffb9` | `#00e6dc` | Digital only | `bg-gradient-petrol-bold` |
| Soft Dynamic Petrol | 135deg | `#00d7a0` | `#00bedc` | Print only | `bg-gradient-petrol-soft` |
| Deep Blue–Petrol | 135deg | `#009999` | `#000028` | Digital & print | `bg-gradient-to-br from-siemens-petrol to-deep-blue` |

## Shadows

```
shadow-soft: 0 1px 2px rgba(51,51,83,0.05), 0 1px 3px rgba(51,51,83,0.08)
shadow-card: 0 2px 4px rgba(51,51,83,0.04), 0 1px 2px rgba(51,51,83,0.06)
```

## Key Visuals

Siemens uses a structured visual matrix organized by context (WHY/HOW/WHAT) with four visual types: Shapes, Full-bleed images, Illustrations, Product images.

**Brand Motifs** (use in hero sections, key visuals):
- Transformation → Infinity symbol (∞)
- Moving Forward → Double arrow (»)
- Siemens Xcelerator → X-shaped icon
- Sustainability → Circle (○)

**Technology Portfolio Icons**: Digital Twin, Cloud, AI, Cybersecurity, Electrification, Smart Grid, Smart City, Transportation, Real Estate, Additive Manufacturing — all styled in Petrol on dark backgrounds, geometric and minimal.

**Typography in visuals**: SiemensSans Pro, headlines uppercase Bold, taglines in `light-petrol` on dark, product names in white.

For detailed visual matrix, icon specs, and layout principles, see [KEY_VISUALS.md](KEY_VISUALS.md).

## Key Rules

### Color Selection
1. **Never use Tailwind's default blue (`blue-500`/`blue-600`)**. Replace with Petrol tokens.
2. **Never use Tailwind's default gray scale**. Replace with Deep Blue scale for all neutral tones.
3. **Never use Soft Green / Soft Blue in digital UI** — they are print adaptations; use Bold Green / Bold Blue instead.
4. **Never use skin/hair tones in interfaces or charts** — illustrations only.
5. **Never use technics/data colors (red/orange) in top-level brand illustrations**.

### Backgrounds
6. **Default background**: `bg-deep-blue` (`#000028`) — dark theme.
7. **Alternative light background**: `bg-light-sand` (`#f3f3f0`).
8. **Pictures & illustrations**: Use Light Sand or white backgrounds.

### UI Patterns
9. **CTA buttons**: `bg-gradient-petrol-bold text-white` (Bold Dynamic Petrol).
10. **Primary buttons**: `bg-siemens-petrol text-white hover:bg-siemens-petrol-dark`.
11. **Secondary/outline buttons**: `border-deep-blue-10 text-deep-blue-80 hover:bg-light-sand`.
12. **Card surfaces**: `bg-white` with `shadow-card` or `shadow-soft`.
13. **Input focus**: `focus:border-brand-petrol focus:ring-2 focus:ring-primary-soft`.
14. **Agent/AI indicators**: Purple tokens (`dark-purple`, `soft-purple`).
15. **Success indicators**: `bold-green` / `brand-green`, not Tailwind green.

### Highlights
16. **Dark background highlights**: Use Light Petrol (`#00c1b6`).
17. **Light background highlights**: Use Siemens Petrol (`#009999`), only at 17pt+ for WCAG 2.1 contrast.
18. **Text hierarchy**: `deep-blue-80` → `deep-blue-60` → `deep-blue-40` → `deep-blue-20`.
