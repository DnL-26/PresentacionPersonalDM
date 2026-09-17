---
name: Syntactic Slate
colors:
  surface: '#0f131c'
  surface-dim: '#0f131c'
  surface-bright: '#353942'
  surface-container-lowest: '#0a0e16'
  surface-container-low: '#181c24'
  surface-container: '#1c2028'
  surface-container-high: '#262a33'
  surface-container-highest: '#31353e'
  on-surface: '#dfe2ee'
  on-surface-variant: '#c7c4d7'
  inverse-surface: '#dfe2ee'
  inverse-on-surface: '#2c3039'
  outline: '#908fa0'
  outline-variant: '#464554'
  surface-tint: '#c0c1ff'
  primary: '#c0c1ff'
  on-primary: '#1000a9'
  primary-container: '#8083ff'
  on-primary-container: '#0d0096'
  inverse-primary: '#494bd6'
  secondary: '#d0bcff'
  on-secondary: '#3c0091'
  secondary-container: '#571bc1'
  on-secondary-container: '#c4abff'
  tertiary: '#4edea3'
  on-tertiary: '#003824'
  tertiary-container: '#00885d'
  on-tertiary-container: '#000703'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e1e0ff'
  primary-fixed-dim: '#c0c1ff'
  on-primary-fixed: '#07006c'
  on-primary-fixed-variant: '#2f2ebe'
  secondary-fixed: '#e9ddff'
  secondary-fixed-dim: '#d0bcff'
  on-secondary-fixed: '#23005c'
  on-secondary-fixed-variant: '#5516be'
  tertiary-fixed: '#6ffbbe'
  tertiary-fixed-dim: '#4edea3'
  on-tertiary-fixed: '#002113'
  on-tertiary-fixed-variant: '#005236'
  background: '#0f131c'
  on-background: '#dfe2ee'
  surface-variant: '#31353e'
typography:
  display-hero:
    fontFamily: Plus Jakarta Sans
    fontSize: 56px
    fontWeight: '800'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '800'
    lineHeight: 44px
    letterSpacing: -0.025em
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: -0.005em
  body-md:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0.005em
  code-md:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 22px
    letterSpacing: -0.01em
  code-badge:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-nav:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.01em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

The design system embodies the calculated precision of engineering combined with the clarity of modern architectural minimalism. Tailored for a software engineer entering the frontier of tech, the design aesthetic bridges technical depth with executive-ready polish. It avoids juvenile visual clutter in favor of intentional typographic discipline, high visual contrast, and tactful micro-interactions.

The visual direction mixes technical minimalism with frosted glass accents and crisp low-contrast borders:
- **Atmospheric Depth:** Deep slate and void-black foundations create a rich canvas that eliminates eye strain while framing work with gallery-grade prestige.
- **Electric Accents:** Deliberate strikes of vibrant indigo and violet guide the eye strictly toward actionable touchpoints and semantic states.
- **Engineering Legibility:** Monospaced typographic accents complement structural sans-serif hierarchies, communicating an authentic code-native fluency.
- **Tactile Refinement:** Subtle linear gradients, translucent overlays, and hairline zinc outlines create tangible layers without heavy ornamentation.

## Colors

The palette operates in strict dark-mode equilibrium, utilizing a spectrum of neutral slates to structure information depth:

- **Canvas & Backgrounds:**
  - Base Ground: `#0b0f17` (Deep slate/void black for primary layout background).
  - Surface Substrate: `#111827` (Zinc-slate for cards, sidebars, and elevated containers).
  - Elevated Popover / Modal: `#1f2937` (Brightened slate layer for floating elements).
- **Accents & Interactions:**
  - Primary Accent: `#6366f1` (Electric Indigo) for primary CTAs, active status indicators, and focus rings.
  - Secondary Accent: `#8b5cf6` (Vivid Violet) used for subtle gradient transitions, link highlights, and secondary interactive states.
  - Success / Tertiary Accent: `#10b981` (Terminal Green) exclusively for availability tags ("Open for roles"), live metrics, and stable git branch badges.
- **Structural Lines & Borders:**
  - Ghost Hairline: `rgba(255, 255, 255, 0.08)` or `#1f2937` for structural grids and card perimeters.
  - Active Border: `rgba(99, 102, 241, 0.4)` on focused or hovered cards.
- **Content Typography:**
  - Primary Foreground: `#f9fafb` (Zinc 50) for headlines and high-priority copy.
  - Secondary Foreground: `#9ca3af` (Zinc 400) for metadata, captions, and narrative body copy.
  - Tertiary / Muted: `#6b7280` (Zinc 500) for timestamps, syntax punctuation, and deactivated states.

## Typography

The typographic system utilizes a tri-font hierarchy to communicate editorial presence, utilitarian prose, and architectural code grammar:

- **Display & Headlines (Plus Jakarta Sans):** Provides geometric precision with humanist touches. Headings utilize tight negative letter spacing to project confidence and density.
- **Body & Editorial (Inter):** Chosen for optimal x-height, neutral tone, and clarity across dense technical summaries and CV experience logs.
- **Technical & Micro-Copy (JetBrains Mono):** Reserved for technical stack tags, metrics, git hashes, inline code snippets, and section index numerics (e.g., `01 / EXPERIENCE`).

## Layout & Spacing

The layout is built on a responsive 12-column grid constrained to a maximum content width of `1200px` for optimal readability and balanced negative space.

- **Desktop (>= 1024px):** 12 columns with `1.5rem` (24px) gutters and `3rem` (48px) safe margins. Sections are spaced with generous vertical padding (`5rem` to `8rem`) to allow individual projects and career milestones to breathe.
- **Tablet (768px - 1023px):** 8 columns with `1.5rem` gutters and `2rem` margins. Complex multi-column project showcase layouts transition into 2-column stacked modules.
- **Mobile (< 768px):** 4 columns with `1rem` gutters and `1.25rem` outer canvas padding. Grids collapse to a clean vertical linear sequence.
- **Component Flow:** Spacing follows strict modular intervals of 4px and 8px. Grouped UI elements (e.g., technical tags inside a project card) use `space-xs` and `space-sm`, while inter-block structural boundaries rely on `space-lg` and `space-xl`.

## Elevation & Depth

Visual hierarchy is communicated through translucent surfaces, backdrop filters, and fine structural borders rather than heavy drop shadows:

- **Surface Ground (Level 0):** Canvas `#0b0f17`. Zero elevation.
- **Sub-surfaces & Cards (Level 1):** Solid `#111827` or translucent `rgba(17, 24, 39, 0.7)` with `backdrop-filter: blur(12px)`. Outlined by a continuous 1px stroke of `rgba(255, 255, 255, 0.08)`.
- **Floating Controls & Navigation (Level 2):** Translucent glass `rgba(11, 15, 23, 0.8)` with `backdrop-filter: blur(16px)` and a refined border of `rgba(255, 255, 255, 0.12)`.
- **Hover & Active Highlights:** Interactive surfaces undergo a slight color temperature lift to `#1f2937` accompanied by an ambient, diffused glow: `box-shadow: 0 0 24px -4px rgba(99, 102, 241, 0.15)`.

## Shapes

The design uses a medium rounded form factor (`roundedness: 2`) across functional framing to balance modern UI smoothness with rigorous engineering ergonomics:

- **Cards and Panels:** Standardized to `12px` (`rounded-lg`) corner radii to soften viewport edges without feeling toy-like.
- **Inputs and Buttons:** Sized to `8px` (`rounded`) for dependable visual clickability and alignment with form fields.
- **Pills and Badges:** Fully circular (`rounded-full` / 9999px) for technology badges, status dots, and floating navigation bars, offering a direct structural contrast against rectangular project cards.

## Components

### Buttons
- **Primary:** Gradient fill of `linear-gradient(135deg, #6366f1, #8b5cf6)`, text `#ffffff`, font `Inter` 500. Inner border subtle specular reflection (`inset 0 1px 0 rgba(255, 255, 255, 0.2)`). Slight lift on hover with `translate-y: -1px` and accent glow.
- **Secondary / Ghost:** Transparent or dark zinc `rgba(255, 255, 255, 0.04)` with `1px solid rgba(255, 255, 255, 0.1)`. Hover state renders an indigo border highlight with `background: rgba(99, 102, 241, 0.08)`.
- **Icon Actions (GitHub, LinkedIn, Resume Download):** Square 40x40px with `rounded` (8px) corners, dark backdrop, and monochrome icons that shift to `#6366f1` on hover.

### Tech Stack Chips & Status Badges
- **Tech Stack Chips:** Pill-shaped (`rounded-full`), height 26px, padding `0.25rem 0.75rem`. Background `#111827`, border `1px solid rgba(255, 255, 255, 0.08)`, font `JetBrains Mono` 12px in `#9ca3af`. On hover, the border shifts to `#6366f1`.
- **Status Indicator ("Available for Hire"):** Pill badge featuring a pulsing green beacon dot (`#10b981`), background `rgba(16, 185, 129, 0.1)`, border `1px solid rgba(16, 185, 129, 0.2)`, text `#10b981`.

### Project Cards
- Composed of a `12px` rounded card with glassmorphism surface `rgba(17, 24, 39, 0.6)` and `1px border rgba(255, 255, 255, 0.06)`.
- Features an embedded preview container with an inner shadow, project title in `Plus Jakarta Sans`, summary text in `Inter`, tech pill clusters, and external link anchors with trailing arrow glyphs (`→`).
- Hover triggers smooth elevation: border color shifts to `rgba(99, 102, 241, 0.35)` with an ambient indigo glow.

### Experience & CV Timeline List
- Vertical running hairline guide in `#1f2937` with node markers in `#6366f1`.
- Timeline entry header displays role title and organization side-by-side with monospaced date intervals (e.g., `2024 — PRESENT`).
- Bulleted impact summaries set with clean, low-contrast zinc bullets and generous line spacing.

### Interactive Code Snippets / Terminal Box
- Surface styled in deep `#070a0f` with a macOS-style header containing 3 window dots (`#ef4444`, `#f59e0b`, `#10b981`) and a discrete monospaced title (e.g., `main.rs` or `fetch_experience.ts`).
- Font set strictly to `JetBrains Mono` with subtle syntax highlighting for keywords (`#8b5cf6`), strings (`#10b981`), and methods (`#6366f1`).