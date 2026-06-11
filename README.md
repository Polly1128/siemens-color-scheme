# siemens-color-scheme

A Qoder Skill that applies **Siemens brand design guidelines** when writing frontend code and designing print materials. Based on Siemens Corporate Design specification (State: 2025-02-17).

## Features

- **Complete Color Palette** — Primary, secondary, status, Deep Blue scale colors with TailwindCSS token mappings and RGB values
- **Color Semantics** — Digital vs. print usage rules (Soft Green/Soft Blue for print only), WCAG 2.1 contrast guidelines
- **Corporate Gradients** — Bold Dynamic Petrol (digital), Soft Dynamic Petrol (print), Deep Blue–Petrol
- **Key Visuals** — Brand motifs (Transformation ∞, Moving Forward », Xcelerator X, Sustainability ○), visual matrix, and 10 technology portfolio icons
- **Roll-up Banner (易拉宝) Design** — Three layout patterns (Event, Strategy, Product), logo placement, typography rules, content zone guidelines
- **Interaction Patterns** — CTA buttons, links, focus states with TailwindCSS snippets
- **Dos & Don'ts** — Clear rules for color selection, backgrounds, highlights, and accessibility

## Installation

### Option 1: Manual (User-level)

Clone this repo into your Qoder skills directory:

```bash
git clone https://github.com/Polly1128/siemens-color-scheme.git ~/.qoder/skills/siemens-color-scheme
```

### Option 2: Manual (Project-level)

Clone into your project's `.qoder/skills/` directory:

```bash
git clone https://github.com/Polly1128/siemens-color-scheme.git .qoder/skills/siemens-color-scheme
```

### Option 3: Skills CLI

```bash
npx skills add https://github.com/Polly1128/siemens-color-scheme -a qoder
```

## File Structure

```
siemens-color-scheme/
├── SKILL.md           # Main skill file (colors, gradients, key visuals summary, interaction patterns, key rules, banner design)
├── KEY_VISUALS.md     # Detailed reference (brand motifs, visual matrix, technology icons, typography, banner layout patterns)
└── README.md          # This file
```

## Usage

This skill activates automatically when you mention:

- Siemens colors / Siemens design / Siemens branding / Siemens style
- Siemens UI / Siemens palette / Petrol
- Dayu UI / Siemens Xcelerator / Key visuals
- 易拉宝 / Roll-up banner / Banner design

Example prompts:

```
按照西门子配色规范设计一个登录页面
Create a dashboard using Siemens brand colors
用 Siemens style 做一个组件
设计一个西门子AI Camp的易拉宝
```

## Color Quick Reference

| Role | Token | Hex | Usage |
|------|-------|-----|-------|
| Brand Primary | `siemens-petrol` | `#009999` | Logo, buttons, links |
| Primary Hover | `siemens-petrol-dark` | `#007a7a` | Hover states |
| Dark Background | `deep-blue` | `#000028` | Dark theme bg, banners |
| Light Background | `light-sand` | `#f3f3f0` | Light theme bg |
| Highlight (dark bg) | `light-petrol` | `#00c1b6` | Dark bg highlights |
| Digital Accent | `bold-green` | `#00ffb9` | Key visuals, CTA gradient |
| Print Accent | `soft-green` | `#00d7a0` | Print only, success states |
| Error | `red` | `#ef0137` | Errors, destructive actions |
| Agent/AI | `dark-purple` | `#553ba3` | AI indicators, skill badges |

## Requirements

- [Qoder](https://qoder.com) IDE or CLI
- TailwindCSS (for token-based class names)

## License

This skill references the Siemens Corporate Design specification for development purposes. Siemens brand assets and guidelines are property of Siemens AG.