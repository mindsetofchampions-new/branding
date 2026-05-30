# Mindset of Champions Design System

> A technology-agnostic design system documentation for building consistent Mindset of Champions experiences across any platform or framework.

---

## Table of Contents

1. [Brand Overview](#brand-overview)
2. [Color System](#color-system)
3. [Typography](#typography)
4. [Spacing & Layout](#spacing--layout)
5. [Components](#components)
6. [Iconography](#iconography)
7. [Motion & Animation](#motion--animation)
8. [Imagery](#imagery)
9. [CHAMPIONS Framework Visual Identity](#champions-framework-visual-identity)
10. [Accessibility](#accessibility)
11. [Implementation Examples](#implementation-examples)

---

## Brand Overview

### Mission Statement
Mindset of Champions is a Philadelphia-based nonprofit using esports, media production, and live events to deliver social-emotional learning, career readiness, and leadership development to underserved youth.

### Brand Tagline
**"A League. A Lab. A Legacy."**

### Brand Voice
- **Bold & Confident**: Strong, declarative statements
- **Youth-Focused**: Energetic and inspiring
- **Professional**: Credible and trustworthy
- **Action-Oriented**: Calls to action, movement-driven language

### Brand Pillars
1. **Esports & Gaming** — Competition as a vehicle for growth
2. **Leadership Development** — Building character through mentorship
3. **Career Readiness** — Real-world skills for future success
4. **Community Impact** — Philadelphia-centered, youth-powered

---

## Color System

### Primary Palette

| Name | Hex | RGB | Usage |
|------|-----|-----|-------|
| **MOC Black** | `#0A0A0A` | rgb(10, 10, 10) | Primary background, foundation color |
| **MOC Red** | `#CC0000` | rgb(204, 0, 0) | Primary brand color, CTAs, accents |
| **MOC Lime** | `#AAFF00` | rgb(170, 255, 0) | Secondary accent, highlights, success states |
| **Pure White** | `#FFFFFF` | rgb(255, 255, 255) | Text, foreground elements |

### Extended Palette

| Name | Hex | RGB | Usage |
|------|-----|-----|-------|
| **Red Hover** | `#AA0000` | rgb(170, 0, 0) | Hover state for red elements |
| **Lime Hover** | `#99DD00` | rgb(153, 221, 0) | Hover state for lime elements |
| **Dark Gray** | `#111111` | rgb(17, 17, 17) | Secondary surfaces, dropdowns |

### Opacity Tokens

| Token | Value | Usage |
|-------|-------|-------|
| `white/80` | rgba(255, 255, 255, 0.8) | Primary body text |
| `white/70` | rgba(255, 255, 255, 0.7) | Secondary text, nav items |
| `white/60` | rgba(255, 255, 255, 0.6) | Muted text, descriptions |
| `white/50` | rgba(255, 255, 255, 0.5) | Tertiary text, captions |
| `white/40` | rgba(255, 255, 255, 0.4) | Placeholder text, disabled |
| `white/12` | rgba(255, 255, 255, 0.12) | Borders, dividers |
| `white/10` | rgba(255, 255, 255, 0.10) | Subtle borders |
| `white/6` | rgba(255, 255, 255, 0.06) | Card backgrounds, inputs |

### Semantic Colors

| Semantic Token | Value | Usage |
|----------------|-------|-------|
| `--background` | `#0A0A0A` | Page background |
| `--foreground` | `#FFFFFF` | Default text color |
| `--primary` | `#CC0000` | Primary actions, links |
| `--primary-foreground` | `#FFFFFF` | Text on primary |
| `--accent` | `#AAFF00` | Highlights, badges |
| `--accent-foreground` | `#0A0A0A` | Text on accent |
| `--muted` | rgba(255, 255, 255, 0.06) | Muted backgrounds |
| `--muted-foreground` | rgba(255, 255, 255, 0.6) | Muted text |
| `--border` | rgba(255, 255, 255, 0.12) | Default borders |
| `--ring` | `#CC0000` | Focus rings |
| `--destructive` | `#CC0000` | Error states |

### Color Usage Guidelines

1. **Background**: Always use `#0A0A0A` (MOC Black) for primary backgrounds
2. **Red Accents**: Use `#CC0000` for CTAs, active states, and brand emphasis
3. **Lime Accents**: Use `#AAFF00` sparingly for highlights, success states, and secondary emphasis
4. **Text Hierarchy**: Use white with decreasing opacity for text hierarchy
5. **Borders**: Use `white/12` for standard borders, `white/10` for subtle borders
6. **Glassmorphism**: Apply `white/6` backgrounds with `backdrop-blur` for glass effects

---

## Typography

### Font Families

| Name | Font | Fallback | Usage |
|------|------|----------|-------|
| **Display** | Bebas Neue | sans-serif | Headlines, hero text, section titles |
| **Sans** | DM Sans | sans-serif | Body text, UI elements, buttons |
| **Mono** | Geist Mono | monospace | Code, data, technical content |

### Type Scale

| Level | Font | Size | Line Height | Weight | Tracking |
|-------|------|------|-------------|--------|----------|
| **Hero** | Display | 7rem-9rem (112-144px) | 1.0 | 400 | wide |
| **H1** | Display | 4rem-5rem (64-80px) | 1.1 | 400 | wide |
| **H2** | Display | 3rem-4rem (48-64px) | 1.1 | 400 | wide |
| **H3** | Display | 2rem-3rem (32-48px) | 1.2 | 400 | wide |
| **H4** | Display | 1.5rem (24px) | 1.2 | 400 | wide |
| **Body Large** | Sans | 1.25rem (20px) | 1.6 | 400 | normal |
| **Body** | Sans | 1rem (16px) | 1.5 | 400 | normal |
| **Body Small** | Sans | 0.875rem (14px) | 1.5 | 400 | normal |
| **Caption** | Sans | 0.75rem (12px) | 1.4 | 500 | widest |
| **Label** | Sans | 0.875rem (14px) | 1.4 | 500 | wider |

### Typography Guidelines

1. **Headlines**: Always use Bebas Neue in UPPERCASE with wide tracking
2. **Body Text**: Use DM Sans with `line-height: 1.5-1.6` for readability
3. **Labels & Badges**: Use uppercase with `tracking-wider` or `tracking-widest`
4. **Emphasis**: Use lime (`#AAFF00`) or red (`#CC0000`) for colored emphasis
5. **Links**: Red for inline links, lime for call-to-action links

---

## Spacing & Layout

### Spacing Scale

| Token | Value | Usage |
|-------|-------|-------|
| `xs` | 4px (0.25rem) | Tight spacing, icon gaps |
| `sm` | 8px (0.5rem) | Small padding, compact elements |
| `md` | 16px (1rem) | Standard padding, gaps |
| `lg` | 24px (1.5rem) | Section padding, card padding |
| `xl` | 32px (2rem) | Large gaps, content sections |
| `2xl` | 48px (3rem) | Section margins |
| `3xl` | 64px (4rem) | Page section spacing |
| `4xl` | 96px (6rem) | Major section breaks |

### Border Radius

| Token | Value | Usage |
|-------|-------|-------|
| `sm` | 8px | Small buttons, badges |
| `md` | 12px | Inputs, small cards |
| `lg` | 16px (1rem) | Standard components |
| `xl` | 20px | Cards, modals |
| `2xl` | 24px | Large cards, hero elements |
| `full` | 9999px | Pills, circular elements |

### Container Widths

| Breakpoint | Max Width | Usage |
|------------|-----------|-------|
| `sm` | 640px | Mobile content |
| `md` | 768px | Tablet content |
| `lg` | 1024px | Small desktop |
| `xl` | 1280px | Standard desktop (primary) |
| `2xl` | 1536px | Wide desktop |

### Layout Grid

- **Max Content Width**: 1280px (80rem)
- **Gutter**: 16px-32px responsive
- **Column System**: 12-column grid
- **Standard Gap**: 24px (1.5rem)

---

## Components

### Buttons

#### Primary Button (Red)
```
Background: #CC0000
Background Hover: #AA0000
Text: #FFFFFF
Border Radius: 12px (rounded-xl)
Padding: 16px 32px (py-4 px-8)
Shadow Hover: 0 10px 25px rgba(204, 0, 0, 0.25)
Transform Hover: scale(1.05)
```

#### Secondary Button (Lime)
```
Background: #AAFF00
Background Hover: #99DD00
Text: #0A0A0A
Border Radius: 12px
Padding: 16px 24px
Shadow Hover: 0 10px 25px rgba(170, 255, 0, 0.25)
```

#### Outline Button
```
Background: transparent
Border: 1px solid rgba(255, 255, 255, 0.3)
Background Hover: rgba(255, 255, 255, 0.12)
Border Hover: rgba(255, 255, 255, 0.5)
Text: #FFFFFF
```

#### Ghost Button
```
Background: transparent
Background Hover: rgba(255, 255, 255, 0.06)
Text: rgba(255, 255, 255, 0.7)
Text Hover: #FFFFFF
```

### Cards

#### Glass Card (Primary)
```
Background: rgba(255, 255, 255, 0.06)
Backdrop Filter: blur(24px)
Border: 1px solid rgba(255, 255, 255, 0.12)
Border Radius: 24px (rounded-2xl)
Shadow: 0 8px 32px rgba(0, 0, 0, 0.4)
Padding: 24px

Hover State:
- Background: rgba(255, 255, 255, 0.10)
- Border: rgba(255, 255, 255, 0.18)
- Shadow: 0 12px 40px rgba(204, 0, 0, 0.15)
```

#### Solid Card
```
Background: #111111
Border: 1px solid rgba(255, 255, 255, 0.12)
Border Radius: 24px
```

### Inputs

```
Background: rgba(255, 255, 255, 0.06)
Border: 1px solid rgba(255, 255, 255, 0.1)
Border Focus: #CC0000
Border Radius: 12px
Text: #FFFFFF
Placeholder: rgba(255, 255, 255, 0.4)
Padding: 12px 16px
```

### Badges

#### Status Badge
```
Background: rgba(255, 255, 255, 0.06)
Backdrop Filter: blur(8px)
Border: 1px solid rgba(255, 255, 255, 0.12)
Border Radius: 9999px (full)
Padding: 8px 16px
Text: rgba(255, 255, 255, 0.8)
Font Size: 14px
```

#### Tag/Pill
```
Background: rgba(255, 255, 255, 0.1)
Border Radius: 9999px
Padding: 4px 12px
Text: rgba(255, 255, 255, 0.8)
Font Size: 12px
```

### Red Accent Border Pattern
```
Border Left: 4px solid #CC0000
Padding Left: 24px
```

---

## Iconography

### Icon System
- **Primary Icon Set**: Lucide Icons
- **Default Size**: 20px (w-5 h-5)
- **Small**: 16px (w-4 h-4)
- **Large**: 24px (w-6 h-6)
- **Stroke Width**: 2px (default)

### Icon Colors
- **Default**: `white/60` or `white/70`
- **Hover**: `white` or `#CC0000`
- **Active**: `#AAFF00`
- **Accent**: `#AAFF00` (for markers, indicators)

### Common Icons
| Use Case | Icon |
|----------|------|
| Navigation | Menu, X, ChevronDown, ChevronRight |
| Social | Instagram, Twitter, Youtube, Linkedin, Facebook |
| Actions | ArrowRight, ExternalLink, Download, Play |
| Status | CheckCircle, XCircle, AlertCircle |
| Contact | Mail, MapPin, Phone |

---

## Motion & Animation

### Timing Functions

| Name | Value | Usage |
|------|-------|-------|
| **Smooth** | `cubic-bezier(0.22, 1, 0.36, 1)` | Most animations |
| **Bounce** | `cubic-bezier(0.68, -0.55, 0.265, 1.55)` | Playful elements |
| **Ease Out** | `ease-out` | Fade in, reveal |

### Duration

| Name | Value | Usage |
|------|-------|-------|
| **Fast** | 150ms | Hover states, micro-interactions |
| **Normal** | 300ms | Transitions, state changes |
| **Medium** | 500ms | Complex animations |
| **Slow** | 700-800ms | Scroll reveals, entrance |

### Standard Animations

#### Fade Up
```
From: opacity 0, translateY 30px
To: opacity 1, translateY 0
Duration: 800ms
Easing: ease-out
```

#### Slide Left
```
From: opacity 0, translateX -40px
To: opacity 1, translateX 0
Duration: 700ms
Easing: cubic-bezier(0.22, 1, 0.36, 1)
```

#### Slide Right
```
From: opacity 0, translateX 40px
To: opacity 1, translateX 0
Duration: 700ms
```

#### Scale In
```
From: opacity 0, scale 0.9
To: opacity 1, scale 1
Duration: 700ms
```

#### Pop In
```
0%: opacity 0, scale 0.8, translateY 20px
70%: scale 1.02, translateY -2px
100%: opacity 1, scale 1, translateY 0
Duration: 500ms
```

#### Pulse Glow (Red)
```
0%, 100%: box-shadow 0 0 20px rgba(204, 0, 0, 0.3)
50%: box-shadow 0 0 40px rgba(204, 0, 0, 0.6)
Duration: 2s infinite
```

#### Bounce Slow
```
0%, 100%: translateY 0
50%: translateY -10px
Duration: 2s infinite
```

### Scroll Animation Triggers
- **Threshold**: 15-30% visibility
- **Stagger Delay**: 80-150ms between items
- **Root Margin**: Optional negative for early trigger

---

## Imagery

### Photography Style
- **Tone**: High-energy, action-focused, youth-centered
- **Color Treatment**: May have slight warm or cool grade, but avoid heavy filters
- **Subject Matter**: Youth gaming, events, community, mentorship moments
- **Composition**: Dynamic angles, close-ups of concentration/celebration

### Background Treatments

#### Hero Gradient Overlay
```
Linear Gradient:
- From: rgba(10, 10, 10, 0.8)
- Via: rgba(10, 10, 10, 0.6)
- To: rgba(10, 10, 10, 1.0)
Direction: to bottom
```

#### Decorative Blurs
```
Red Glow:
- Background: rgba(204, 0, 0, 0.05-0.1)
- Size: 128px-192px
- Filter: blur(48px-64px)

Lime Glow:
- Background: rgba(170, 255, 0, 0.05-0.1)
- Size: 128px-192px
- Filter: blur(48px-64px)
```

### Accent Lines
```
Red Accent Line:
- Width: 4px (vertical) or 2px (horizontal)
- Color: #CC0000
- Gradient: to transparent at ends
```

---

## CHAMPIONS Framework Visual Identity

The C.H.A.M.P.I.O.N.S. Framework represents nine core pillars of development, organized into three phases.

### Pillar Colors & Icons

| Pillar | Letter | Color Name | Hex | RGB | Icon | Phase |
|--------|--------|------------|-----|-----|------|-------|
| **Character Development** | C | Crimson | `#DC2626` | rgb(220, 38, 38) | Shield | Foundation |
| **Habits** | H | Orange | `#EA580C` | rgb(234, 88, 12) | Flame (streak) | Foundation |
| **Appearance** | A | Amber | `#D97706` | rgb(217, 119, 6) | Sparkle | Foundation |
| **Mission** | M | Emerald | `#059669` | rgb(5, 150, 105) | Target | Direction |
| **Positive Attitude** | P | Sky | `#0284C7` | rgb(2, 132, 199) | Sun | Direction |
| **Intentionality** | I | Indigo | `#4F46E5` | rgb(79, 70, 229) | Compass | Direction |
| **Obstacles** | O | Violet | `#7C3AED` | rgb(124, 58, 237) | Mountain | Launch |
| **Network** | N | Pink | `#DB2777` | rgb(219, 39, 119) | Users/Handshake | Launch |
| **Success** | S | Gold | `#CA8A04` | rgb(202, 138, 4) | Trophy | Launch |

### Phase Groupings

| Phase | Number | Name | Pillars | Theme |
|-------|--------|------|---------|-------|
| **Phase 1** | 01 | Foundation | C-H-A | "Who I am + How I show up" |
| **Phase 2** | 02 | Direction | M-P-I | "Why I do it + How I think" |
| **Phase 3** | 03 | Launch | O-N-S | "How I navigate the world + Legacy" |

### Letter Badge Component
```
Size: 40-48px square
Background: rgba(255, 255, 255, 0.06)
Backdrop Filter: blur(8px)
Border: 1px solid rgba(255, 255, 255, 0.12)
Border Radius: 8px
Font: Display (Bebas Neue)
Text Color: #AAFF00 (or pillar-specific color)
```

### Pillar Card Component
```
Background: Glass Card style
Left Border: 4px solid [Pillar Color]
Icon Size: 24-32px
Icon Color: [Pillar Color]
Title Font: Display
```

---

## Accessibility

### Color Contrast
- **Primary Text on Background**: White (#FFFFFF) on #0A0A0A = 21:1 (AAA)
- **Muted Text**: white/60 on #0A0A0A = 10.4:1 (AAA)
- **Red on Background**: #CC0000 on #0A0A0A = 5.1:1 (AA)
- **Lime on Black**: #AAFF00 on #0A0A0A = 14.3:1 (AAA)

### Focus States
```
Outline: 3px solid #CC0000
Outline Offset: 2px
OR
Ring: 3px solid with ring opacity 50%
```

### Motion Accessibility
- Respect `prefers-reduced-motion` media query
- Provide fallbacks for all scroll-triggered animations
- Keep essential animations under 500ms

### Screen Reader Considerations
- All decorative images: `aria-hidden="true"` or empty `alt=""`
- Interactive elements: Descriptive labels
- Icon buttons: Include `aria-label`
- Live regions for dynamic content updates

---

## Implementation Examples

### CSS Custom Properties (Native)
```css
:root {
  /* Core Colors */
  --moc-black: #0A0A0A;
  --moc-red: #CC0000;
  --moc-red-hover: #AA0000;
  --moc-lime: #AAFF00;
  --moc-lime-hover: #99DD00;
  --moc-white: #FFFFFF;
  
  /* CHAMPIONS Pillar Colors */
  --pillar-character: #DC2626;
  --pillar-habits: #EA580C;
  --pillar-appearance: #D97706;
  --pillar-mission: #059669;
  --pillar-positive: #0284C7;
  --pillar-intentionality: #4F46E5;
  --pillar-obstacles: #7C3AED;
  --pillar-network: #DB2777;
  --pillar-success: #CA8A04;
  
  /* Typography */
  --font-display: 'Bebas Neue', sans-serif;
  --font-sans: 'DM Sans', sans-serif;
  --font-mono: 'Geist Mono', monospace;
  
  /* Spacing */
  --space-xs: 0.25rem;
  --space-sm: 0.5rem;
  --space-md: 1rem;
  --space-lg: 1.5rem;
  --space-xl: 2rem;
  --space-2xl: 3rem;
  --space-3xl: 4rem;
  
  /* Border Radius */
  --radius-sm: 0.5rem;
  --radius-md: 0.75rem;
  --radius-lg: 1rem;
  --radius-xl: 1.25rem;
  --radius-2xl: 1.5rem;
  --radius-full: 9999px;
}
```

### SCSS Variables
```scss
// Core Colors
$moc-black: #0A0A0A;
$moc-red: #CC0000;
$moc-red-hover: #AA0000;
$moc-lime: #AAFF00;
$moc-lime-hover: #99DD00;

// CHAMPIONS Colors
$champions: (
  character: #DC2626,
  habits: #EA580C,
  appearance: #D97706,
  mission: #059669,
  positive: #0284C7,
  intentionality: #4F46E5,
  obstacles: #7C3AED,
  network: #DB2777,
  success: #CA8A04
);
```

### Design Tokens (JSON)
```json
{
  "color": {
    "brand": {
      "black": { "value": "#0A0A0A" },
      "red": { "value": "#CC0000" },
      "lime": { "value": "#AAFF00" },
      "white": { "value": "#FFFFFF" }
    },
    "champions": {
      "character": { "value": "#DC2626" },
      "habits": { "value": "#EA580C" },
      "appearance": { "value": "#D97706" },
      "mission": { "value": "#059669" },
      "positive": { "value": "#0284C7" },
      "intentionality": { "value": "#4F46E5" },
      "obstacles": { "value": "#7C3AED" },
      "network": { "value": "#DB2777" },
      "success": { "value": "#CA8A04" }
    }
  }
}
```

### Figma Implementation Notes
- Use Color Styles for all brand colors
- Create Text Styles matching type scale
- Build Component library with variants
- Use Auto Layout with spacing tokens
- Apply Effects for glassmorphism

---

## Version History

| Version | Date | Changes |
|---------|------|---------|
| 1.0.0 | 2024 | Initial design system documentation |

---

*This design system is maintained by the Mindset of Champions team. For questions or contributions, contact hr@mindsetofchampions.org*
