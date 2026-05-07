---
name: Kyoto Consulting Aesthetic
colors:
  surface: '#fff8f5'
  surface-dim: '#e1d8d4'
  surface-bright: '#fff8f5'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fbf2ed'
  surface-container: '#f5ece7'
  surface-container-high: '#efe6e2'
  surface-container-highest: '#e9e1dc'
  on-surface: '#1e1b18'
  on-surface-variant: '#484740'
  inverse-surface: '#34302c'
  inverse-on-surface: '#f8efea'
  outline: '#79776f'
  outline-variant: '#c9c6bd'
  surface-tint: '#605e5b'
  primary: '#605e5b'
  on-primary: '#ffffff'
  primary-container: '#f9f5f0'
  on-primary-container: '#72706c'
  inverse-primary: '#c9c6c1'
  secondary: '#506354'
  on-secondary: '#ffffff'
  secondary-container: '#d0e5d2'
  on-secondary-container: '#546758'
  tertiary: '#944925'
  on-tertiary: '#ffffff'
  tertiary-container: '#fff3ef'
  on-tertiary-container: '#aa5a34'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e6e2dd'
  primary-fixed-dim: '#c9c6c1'
  on-primary-fixed: '#1c1c19'
  on-primary-fixed-variant: '#484743'
  secondary-fixed: '#d3e8d5'
  secondary-fixed-dim: '#b7ccb9'
  on-secondary-fixed: '#0e1f13'
  on-secondary-fixed-variant: '#394b3d'
  tertiary-fixed: '#ffdbcd'
  tertiary-fixed-dim: '#ffb596'
  on-tertiary-fixed: '#360f00'
  on-tertiary-fixed-variant: '#76320f'
  background: '#fff8f5'
  on-background: '#1e1b18'
  surface-variant: '#e9e1dc'
typography:
  headline-xl:
    fontFamily: Public Sans
    fontSize: 48px
    fontWeight: '300'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Public Sans
    fontSize: 32px
    fontWeight: '400'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Public Sans
    fontSize: 24px
    fontWeight: '500'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Public Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Public Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: Public Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.0'
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
  container-max: 1200px
  gutter: 24px
  margin-page: 48px
  section-gap: 120px
---

## Brand & Style

This design system is built upon the philosophy of *Wa* (harmony) and the minimalist precision of Scandinavian design, creating a "Japandi" fusion tailored for high-end consulting. The brand personality is grounded, intentional, and hospitable, evoking the serene atmosphere of a modern Machiya in Kyoto.

The visual style prioritizes **Minimalism** with a tactile warmth. It avoids the sterile coldness of traditional corporate blue palettes in favor of organic textures and intentional "Ma" (negative space). The goal is to elicit a sense of calm authority and quiet confidence, signaling to clients that the firm values clarity, longevity, and meticulous craftsmanship in its advisory work.

## Colors

The palette is anchored in an "Earth and Paper" concept. The primary foundation is a warm, textured cream that mimics the soft light filtered through a shoji screen. 

- **Primary (Washi Cream):** Used for large surfaces to reduce eye strain and provide a welcoming, premium canvas.
- **Secondary (Koke Green):** A muted moss green used for secondary actions and environmental accents, representing growth and stability.
- **Tertiary (Bengala Earth):** A deep terracotta used sparingly for primary call-to-actions or to highlight critical insights, providing a grounded focal point.
- **Neutral (Sumi Ink):** A soft, warm charcoal used for typography and structural lines, offering high legibility without the harshness of pure black.

## Typography

This design system utilizes **Public Sans** for its institutional clarity and neutral, rhythmic spacing. The typographic hierarchy is inspired by architectural blueprints: clean, structured, and legible.

Headlines should utilize light weights (300) at large scales to emphasize the premium, airy nature of the brand. Body text is set with a generous line-height (1.6) to ensure a comfortable reading experience for long-form consulting reports. Small labels should be set in uppercase with increased letter spacing to serve as subtle wayfinding elements.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy within a fluid container, emphasizing structural balance and symmetry. A 12-column grid is used for desktop layouts, but the defining characteristic is the use of "Ma"—large, intentional gaps between sections to allow the content to breathe.

Spacing follows a strict 8px rhythmic scale. Section headers should be preceded by significant white space (120px+) to create a sense of pace and transition, mirroring the experience of walking through a series of temple courtyards.

## Elevation & Depth

To maintain the Japandi aesthetic, this design system avoids heavy, artificial shadows. Depth is instead conveyed through **Tonal Layers** and **Low-Contrast Outlines**.

- **Surface Tiers:** Use subtle shifts in background color (e.g., from Washi Cream to a slightly cooler Taupe) to differentiate content blocks.
- **Ghost Borders:** Elements like cards or input fields should use thin (1px) borders in a muted neutral tone rather than drop shadows.
- **Soft Ambient Depth:** For floating elements like modals, use a very large, ultra-low opacity (4-6%) shadow tinted with the Terracotta or Moss Green to maintain a warm, organic feel.

## Shapes

The shape language reflects the "Soft Minimalism" of modern Japanese architecture. While the overall structure remains rectilinear and disciplined, corners are softened to feel approachable.

A **Soft (0.25rem)** roundedness is the standard for primary UI elements like buttons and input fields. This slight radius removes the aggressive "sharpness" of pure brutalism while maintaining a professional, geometric integrity. For larger containers or "hero" imagery, a more pronounced radius may be used to mimic the organic curves of hand-thrown ceramics.

## Components

Components should feel like physical objects placed intentionally within a space.

- **Buttons:** Primary buttons use the Deep Terracotta with white text, featuring a subtle hover state that shifts to a slightly darker shade. Secondary buttons should be outlined (Ghost style) with a Moss Green border.
- **Cards:** Cards are defined by thin, Sumi Ink borders (10-15% opacity) and a background slightly lighter than the page foundation. No heavy shadows.
- **Inputs:** Text fields use a "bottom-line only" or very light border approach to keep the interface feeling airy. Labels are always positioned above the field in the "label-caps" style.
- **Chips/Tags:** Use the Moss Green at a low opacity (10%) for the background with high-contrast text for a "natural" categorization feel.
- **Navigation:** A minimalist top-bar navigation with generous horizontal padding, using thin vertical separators that echo wooden slat walls.