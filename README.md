# siemens-color-scheme

A Qoder Skill that applies **Siemens brand design guidelines** when writing frontend code. Based on Siemens Corporate Design specification (State: 2025-02-17).

## Features

- **Complete Color Palette** — Primary, secondary, status, and Deep Blue scale colors with TailwindCSS token mappings
- **Corporate Gradients** — Bold Dynamic Petrol, Soft Dynamic Petrol, Deep Blue–Petrol
- **Key Visuals** — Brand motifs (Transformation, Moving Forward, Xcelerator, Sustainability), visual matrix, and technology portfolio icons
- **Interaction Patterns** — CTA buttons, links, focus states with TailwindCSS snippets
- **Dos & Don'ts** — Clear rules for color selection, backgrounds, highlights, and WCAG 2.1 compliance

## Installation

### Option 1: Manual (User-level)

Clone this repo into your Qoder skills directory:

```bash
git clone https://github.com/<your-username>/siemens-color-scheme.git ~/.qoder/skills/siemens-color-scheme
```

### Option 2: Manual (Project-level)

Clone into your project's `.qoder/skills/` directory:

```bash
git clone https://github.com/<your-username>/siemens-color-scheme.git .qoder/skills/siemens-color-scheme
```

### Option 3: Skills CLI

```bash
npx skills add https://github.com/<your-username>/siemens-color-scheme -a qoder
```

## File Structure

```
siemens-color-scheme/
├── SKILL.md           # Main skill file (color palette, gradients, interaction patterns, key rules)
├── KEY_VISUALS.md     # Key visuals reference (brand motifs, visual matrix, technology icons, typography)
└── README.md          # This file
```

## Usage

This skill activates automatically when you mention:

- Siemens colors / Siemens design / Siemens branding / Siemens style
- Siemens UI / Siemens palette / Petrol
- Dayu UI / Siemens Xcelerator / Key visuals

Example prompts:

```
按照西门子配色规范设计一个登录页面
Create a dashboard using Siemens brand colors
用 Siemens style 做一个组件
```

## Color Quick Reference

| Role | Token | Hex |
|------|-------|-----|
| Brand Primary | `siemens-petrol` | `#009999` |
| Primary Hover | `siemens-petrol-dark` | `#007a7a` |
| Dark Background | `deep-blue` | `#000028` |
| Light Background | `light-sand` | `#f3f3f0` |
| Success | `bold-green` | `#00ffb9` |
| Error | `red` | `#ef0137` |
| Agent/AI | `dark-purple` | `#553ba3` |

## Requirements

- [Qoder](https://qoder.com) IDE or CLI
- TailwindCSS (for token-based class names)

## License

This skill references the Siemens Corporate Design specification for development purposes. Siemens brand assets and guidelines are property of Siemens AG.
