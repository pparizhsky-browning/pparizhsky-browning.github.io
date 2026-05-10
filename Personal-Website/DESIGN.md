---
name: Midnight Obsidian
colors:
  surface: '#121317'
  surface-dim: '#121317'
  surface-bright: '#38393d'
  surface-container-lowest: '#0d0e12'
  surface-container-low: '#1a1b1f'
  surface-container: '#1e1f23'
  surface-container-high: '#292a2e'
  surface-container-highest: '#343539'
  on-surface: '#e3e2e7'
  on-surface-variant: '#c7c6ca'
  inverse-surface: '#e3e2e7'
  inverse-on-surface: '#2f3034'
  outline: '#919094'
  outline-variant: '#46464a'
  surface-tint: '#c8c6c7'
  primary: '#c8c6c7'
  on-primary: '#313031'
  primary-container: '#0a0a0b'
  on-primary-container: '#7a797a'
  inverse-primary: '#5f5e5f'
  secondary: '#c8c6c8'
  on-secondary: '#303032'
  secondary-container: '#474649'
  on-secondary-container: '#b7b4b7'
  tertiary: '#10b981'
  on-tertiary: '#022c22'
  tertiary-container: '#022c22'
  on-tertiary-container: '#34d399'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e5e2e3'
  primary-fixed-dim: '#c8c6c7'
  on-primary-fixed: '#1c1b1c'
  on-primary-fixed-variant: '#474647'
  secondary-fixed: '#e4e2e4'
  secondary-fixed-dim: '#c8c6c8'
  on-secondary-fixed: '#1b1b1d'
  on-secondary-fixed-variant: '#474649'
  tertiary-fixed: '#6ee7b7'
  tertiary-fixed-dim: '#10b981'
  on-tertiary-fixed: '#022c22'
  on-tertiary-fixed-variant: '#065f46'
  background: '#121317'
  on-background: '#e3e2e7'
  surface-variant: '#343539'
typography:
  display-xl:
    fontFamily: Noto Serif
    fontSize: 72px
    fontWeight: '700'
    lineHeight: 84px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Noto Serif
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 56px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Noto Serif
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 32px
  section-gap: 160px
  margin-safe: 40px
---

## Brand & Style
This design system is engineered for high-impact storytelling and a premium personal presence. It evokes a sense of prestige, authority, and cinematic depth. The visual direction leans into a sophisticated **Glassmorphism-Minimalist** hybrid, utilizing deep layers and atmospheric light to create a three-dimensional digital environment. 

The aesthetic is defined by "The Void"—a concept where content emerges from deep blacks and charcoals through sharp accents and soft, diffused glows. It targets an audience that values craftsmanship and quiet confidence, delivering an emotional response of awe and professional excellence.

## Colors
The palette is rooted in the "Midnight" spectrum. The background utilizes a true black (`#000000`) for OLED-optimized depth, while primary containers use Deep Charcoal (`#0A0A0B`) to establish a base layer. 

The accent, **Emerald Green** (`#10B981`), is used sparingly for high-contrast "moments of intent"—calls to action, active states, and critical highlights. Atmospheric grays provide the necessary hierarchy for secondary information, ensuring that the interface remains legible without breaking the immersive dark environment. Radial gradients should transition from the secondary color to the primary color to simulate subtle spotlighting on key content areas.

## Typography
The typographic system relies on a dramatic contrast between the classical elegance of **Noto Serif** and the industrial precision of **Inter**. 

Headlines should be treated as hero elements, often utilizing large scale and generous tracking adjustments to command attention. Use the `label-caps` style for section overlines or small metadata to provide a technical, "curated" feel. Line heights are intentionally generous to support the brand's focus on whitespace and readability in high-contrast environments.

## Layout & Spacing
This design system utilizes a **12-column fixed grid** centered within the viewport, paired with aggressive vertical rhythm. "Breathe" is the core principle; section gaps are unusually large (`160px` or more) to ensure each piece of content is consumed in isolation, mirroring a cinematic film strip.

Component spacing follows a strict 8px linear scale. Horizontal margins are wide to push content into a focused central column, emphasizing a high-end editorial layout rather than a dense information dashboard.

## Elevation & Depth
Depth is achieved through **Tonal Layering** and **Glassmorphism** rather than traditional drop shadows.
1.  **Level 0 (Base):** Deepest black (`#000000`).
2.  **Level 1 (Card/Container):** Deep charcoal (`#0A0A0B`) with a 1px border of white at 10% opacity.
3.  **Level 2 (Float):** Semi-transparent charcoal with a `20px` backdrop blur (glassmorphism) and a soft, Cyan-tinted outer glow (`0px 20px 40px rgba(16, 185, 129, 0.05)`).

Shadows should never be pure black; they must be diffused and slightly tinted by the accent color to maintain the "atmospheric" quality.

## Shapes
The shape language is "Soft-Precision." We use a low `0.25rem` radius (Soft) for most components to maintain a serious, architectural feel. This prevents the UI from appearing too "bubbly" or consumer-grade, keeping it firmly in the premium/professional territory. Larger containers or hero images may occasionally use a slightly higher radius (`0.5rem`) to soften the visual impact of high-contrast photography.

## Components
- **Buttons:** Primary buttons use a solid Emerald Green background with black text, featuring a subtle "glow" on hover. Secondary buttons are "Ghost" style with a 1px border and no fill.
- **Cards:** Utilize a subtle gradient fill from top-left to bottom-right. The top-left edge should have a "light leak" effect—a thin highlight border to simulate a light source.
- **Input Fields:** Minimalist under-lines or very dark backgrounds (`#161618`) with the focus state transitioning the border to Emerald Green.
- **Chips/Labels:** Small, uppercase text with high letter-spacing. Use a dark gray background with 50% opacity.
- **Cinematic Dividers:** Instead of solid lines, use 1px gradients that fade out to 0% opacity at both ends, creating a soft horizontal separation.
- **Specialty Component (Project Reveal):** A full-width image container with a vertical parallax effect and a bottom-aligned Serif headline that overlaps the image boundary.