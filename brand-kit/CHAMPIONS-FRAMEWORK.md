# C.H.A.M.P.I.O.N.S. Framework Visual Identity

> Complete visual identity system for the nine pillars of the CHAMPIONS Framework.

---

## Overview

The C.H.A.M.P.I.O.N.S. Framework is the core curriculum structure of Mindset of Champions. Each letter represents a pillar of personal development, organized into three progressive phases.

---

## The Nine Pillars

### Phase 1: Foundation
**Theme**: "Who I am + How I show up"

| Letter | Pillar | Color Name | Hex | RGB | Icon |
|--------|--------|------------|-----|-----|------|
| **C** | Character Development | Crimson | `#DC2626` | rgb(220, 38, 38) | Shield |
| **H** | Habits | Orange | `#EA580C` | rgb(234, 88, 12) | Flame |
| **A** | Appearance | Amber | `#D97706` | rgb(217, 119, 6) | Sparkle |

---

### Phase 2: Direction
**Theme**: "Why I do it + How I think"

| Letter | Pillar | Color Name | Hex | RGB | Icon |
|--------|--------|------------|-----|-----|------|
| **M** | Mission | Emerald | `#059669` | rgb(5, 150, 105) | Target |
| **P** | Positive Attitude | Sky | `#0284C7` | rgb(2, 132, 199) | Sun |
| **I** | Intentionality | Indigo | `#4F46E5` | rgb(79, 70, 229) | Compass |

---

### Phase 3: Launch
**Theme**: "How I navigate the world + Legacy"

| Letter | Pillar | Color Name | Hex | RGB | Icon |
|--------|--------|------------|-----|-----|------|
| **O** | Obstacles | Violet | `#7C3AED` | rgb(124, 58, 237) | Mountain |
| **N** | Network | Pink | `#DB2777` | rgb(219, 39, 119) | Users/Handshake |
| **S** | Success | Gold | `#CA8A04` | rgb(202, 138, 4) | Trophy |

---

## Color Swatches

### All Pillar Colors at a Glance

```
C  #DC2626  ████████  Crimson     Shield
H  #EA580C  ████████  Orange      Flame
A  #D97706  ████████  Amber       Sparkle
M  #059669  ████████  Emerald     Target
P  #0284C7  ████████  Sky         Sun
I  #4F46E5  ████████  Indigo      Compass
O  #7C3AED  ████████  Violet      Mountain
N  #DB2777  ████████  Pink        Users
S  #CA8A04  ████████  Gold        Trophy
```

---

## Icon Reference

Use Lucide Icons (or equivalent) for pillar iconography:

| Pillar | Lucide Icon Name | Alternative Names |
|--------|------------------|-------------------|
| Character | `shield` | `shield-check`, `shield-plus` |
| Habits | `flame` | `zap`, `trending-up` |
| Appearance | `sparkles` | `star`, `sparkle` |
| Mission | `target` | `crosshair`, `focus` |
| Positive | `sun` | `sun-medium`, `smile` |
| Intentionality | `compass` | `navigation`, `map-pin` |
| Obstacles | `mountain` | `mountain-snow`, `flag` |
| Network | `users` | `handshake`, `users-2` |
| Success | `trophy` | `award`, `medal` |

---

## CSS Implementation

### CSS Custom Properties

```css
:root {
  /* Phase 1: Foundation */
  --pillar-character: #DC2626;
  --pillar-habits: #EA580C;
  --pillar-appearance: #D97706;
  
  /* Phase 2: Direction */
  --pillar-mission: #059669;
  --pillar-positive: #0284C7;
  --pillar-intentionality: #4F46E5;
  
  /* Phase 3: Launch */
  --pillar-obstacles: #7C3AED;
  --pillar-network: #DB2777;
  --pillar-success: #CA8A04;
}
```

### Tailwind CSS Classes

If using Tailwind CSS, these are the equivalent utility classes:

| Pillar | Background | Text | Border |
|--------|------------|------|--------|
| Character | `bg-red-600` | `text-red-600` | `border-red-600` |
| Habits | `bg-orange-600` | `text-orange-600` | `border-orange-600` |
| Appearance | `bg-amber-600` | `text-amber-600` | `border-amber-600` |
| Mission | `bg-emerald-600` | `text-emerald-600` | `border-emerald-600` |
| Positive | `bg-sky-600` | `text-sky-600` | `border-sky-600` |
| Intentionality | `bg-indigo-600` | `text-indigo-600` | `border-indigo-600` |
| Obstacles | `bg-violet-600` | `text-violet-600` | `border-violet-600` |
| Network | `bg-pink-600` | `text-pink-600` | `border-pink-600` |
| Success | `bg-yellow-600` | `text-yellow-600` | `border-yellow-600` |

**Note**: For exact color matching, extend your Tailwind config with custom colors.

---

## Component Patterns

### Letter Badge

A single letter badge for representing each pillar:

```
┌──────┐
│  C   │  40-48px square
└──────┘
```

**Specifications**:
- Size: 40-48px square
- Background: `rgba(255, 255, 255, 0.06)` or pillar color at 10% opacity
- Border: `1px solid rgba(255, 255, 255, 0.12)`
- Border Radius: 8px
- Font: Bebas Neue (Display)
- Text Color: Pillar color or `#AAFF00`

### Pillar Card

A card displaying pillar information:

```
┌─────────────────────────────┐
│ ◀ 4px accent                │
│   [Icon]                    │
│   PILLAR NAME               │
│   Description text...       │
└─────────────────────────────┘
```

**Specifications**:
- Use Glass Card style
- Left border: 4px solid [Pillar Color]
- Icon: 24-32px, colored with pillar color
- Title: Bebas Neue, uppercase
- Description: DM Sans, white/60

### Phase Group

Display pillars grouped by phase:

```
┌─────────────────────────────────────────┐
│  PHASE 1: FOUNDATION                    │
│  "Who I am + How I show up"             │
│                                         │
│  ┌─────┐  ┌─────┐  ┌─────┐              │
│  │  C  │  │  H  │  │  A  │              │
│  └─────┘  └─────┘  └─────┘              │
│                                         │
│  Character • Habits • Appearance        │
└─────────────────────────────────────────┘
```

---

## Usage Guidelines

### DO:
- Use pillar colors consistently for their respective pillars
- Pair icons with their designated pillars
- Group pillars by phase when showing the full framework
- Use the colors to create visual hierarchy

### DON'T:
- Mix pillar colors randomly
- Use pillar colors for non-related content
- Substitute icons without approval
- Use gradients across pillar colors (unless specifically designed)

---

## Print Color Values

For print materials, use these CMYK approximations:

| Pillar | CMYK |
|--------|------|
| Character | 0, 83, 88, 14 |
| Habits | 0, 62, 95, 8 |
| Appearance | 0, 45, 97, 15 |
| Mission | 97, 0, 30, 41 |
| Positive | 99, 34, 0, 22 |
| Intentionality | 45, 51, 0, 10 |
| Obstacles | 47, 76, 0, 7 |
| Network | 0, 82, 35, 14 |
| Success | 0, 14, 98, 21 |

---

## Digital Asset Checklist

For each pillar, prepare:
- [ ] Icon in SVG format
- [ ] Color swatch image (PNG)
- [ ] Badge component
- [ ] Card component
- [ ] Social media icon variants

---

## Related Files

- `/Branding/brand-kit/tokens/colors.json` — Full color token definitions
- `/Branding/brand-kit/css/variables.css` — CSS custom properties
- `/Branding/brand-kit/css/variables.scss` — SCSS variables and mixins
- `/Branding/DESIGN-SYSTEM.md` — Complete design system documentation
