# Mindset of Champions Brand Kit

**Design System (live):** https://mindsetofchampions-new.github.io/branding/  
**Repo:** https://github.com/mindsetofchampions-new/branding

> Complete brand assets and design resources for Mindset of Champions.

---

## Folder Structure

```
brand-kit/
├── README.md                    # This file
├── BRAND-GUIDELINES.md          # Official brand usage guidelines
├── CHAMPIONS-FRAMEWORK.md       # CHAMPIONS pillar visual identity
│
├── logos/                       # Logo assets
│   └── moc-logo.svg            # Primary logo (SVG)
│
├── tokens/                      # Design tokens (JSON format)
│   ├── colors.json             # Color definitions
│   ├── typography.json         # Typography definitions
│   └── spacing.json            # Spacing & layout tokens
│
└── css/                         # CSS/SCSS variables
    ├── variables.css           # CSS custom properties
    └── variables.scss          # SCSS variables & mixins
```

---

## Quick Start

### For Web Projects

**CSS Custom Properties:**
```html
<link rel="stylesheet" href="path/to/css/variables.css">
```

**SCSS:**
```scss
@import 'path/to/css/variables.scss';

.my-button {
  @include button-primary;
}
```

### For Design Tools

Import `tokens/colors.json` and `tokens/typography.json` into Figma, Sketch, or other design tools that support design tokens.

---

## Brand Colors

| Color | Hex | Usage |
|-------|-----|-------|
| MOC Black | `#0A0A0A` | Primary background |
| MOC Red | `#CC0000` | Primary accent, CTAs |
| MOC Lime | `#AAFF00` | Secondary accent |
| Pure White | `#FFFFFF` | Text, foreground |

---

## Typography

| Family | Name | Usage |
|--------|------|-------|
| Display | Bebas Neue | Headlines, titles |
| Sans | DM Sans | Body text, UI |
| Mono | Geist Mono | Code, data |

---

## CHAMPIONS Framework

See `CHAMPIONS-FRAMEWORK.md` for the complete visual identity of each pillar:

| Pillar | Color | Icon |
|--------|-------|------|
| **C**haracter | Crimson `#DC2626` | Shield |
| **H**abits | Orange `#EA580C` | Flame |
| **A**ppearance | Amber `#D97706` | Sparkle |
| **M**ission | Emerald `#059669` | Target |
| **P**ositive Attitude | Sky `#0284C7` | Sun |
| **I**ntentionality | Indigo `#4F46E5` | Compass |
| **O**bstacles | Violet `#7C3AED` | Mountain |
| **N**etwork | Pink `#DB2777` | Users |
| **S**uccess | Gold `#CA8A04` | Trophy |

---

## Related Documents

- **[DESIGN-SYSTEM.md](../DESIGN-SYSTEM.md)** — Complete tech-agnostic design system
- **[BRAND-GUIDELINES.md](./BRAND-GUIDELINES.md)** — Brand usage rules and voice

---

## Contact

For brand inquiries or asset requests:
- **Email**: hr@mindsetofchampions.org
- **Website**: mindsetofchampions.org
