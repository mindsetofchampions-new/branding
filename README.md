# Mindset of Champions Branding

**Live:** https://mindsetofchampions-new.github.io/branding/  
**Repo:** https://github.com/mindsetofchampions-new/branding

> Central repository for all Mindset of Champions brand and design documentation.

---

## Contents

### [DESIGN-SYSTEM.md](./DESIGN-SYSTEM.md)
Complete technology-agnostic design system documentation covering:
- Color system with semantic tokens
- Typography scale and guidelines
- Spacing and layout rules
- Component specifications
- Animation patterns
- CHAMPIONS Framework visual identity
- Implementation examples (CSS, SCSS, JSON tokens)

### [brand-kit/](./brand-kit/)
Production-ready brand assets and resources:
- **[BRAND-GUIDELINES.md](./brand-kit/BRAND-GUIDELINES.md)** — Official brand usage guidelines
- **[CHAMPIONS-FRAMEWORK.md](./brand-kit/CHAMPIONS-FRAMEWORK.md)** — Pillar visual identity reference
- **[logos/](./brand-kit/logos/)** — Logo files
- **[tokens/](./brand-kit/tokens/)** — Design tokens in JSON format
- **[css/](./brand-kit/css/)** — CSS and SCSS variables

---

## Quick Reference

### Primary Colors
| Color | Hex | Usage |
|-------|-----|-------|
| MOC Black | `#0A0A0A` | Background |
| MOC Red | `#CC0000` | Primary accent |
| MOC Lime | `#AAFF00` | Secondary accent |
| White | `#FFFFFF` | Text |

### Fonts
- **Bebas Neue** — Headlines
- **DM Sans** — Body text
- **Geist Mono** — Code

### CHAMPIONS Pillars
| Letter | Pillar | Color |
|--------|--------|-------|
| C | Character | `#DC2626` |
| H | Habits | `#EA580C` |
| A | Appearance | `#D97706` |
| M | Mission | `#059669` |
| P | Positive Attitude | `#0284C7` |
| I | Intentionality | `#4F46E5` |
| O | Obstacles | `#7C3AED` |
| N | Network | `#DB2777` |
| S | Success | `#CA8A04` |

---

## Usage

### Web Development
Import CSS variables or SCSS from `brand-kit/css/`:
```css
@import './Branding/brand-kit/css/variables.css';
```

### Design Tools
Use JSON tokens from `brand-kit/tokens/` with Figma Tokens, Style Dictionary, or similar.

### Documentation
Reference `DESIGN-SYSTEM.md` for implementation specifications.

---

*Maintained by the Mindset of Champions team.*
