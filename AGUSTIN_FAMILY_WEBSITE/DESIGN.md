---
name: Heritage Narrative
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
  on-surface-variant: '#524341'
  inverse-surface: '#34302c'
  inverse-on-surface: '#f8efea'
  outline: '#857371'
  outline-variant: '#d7c2bf'
  surface-tint: '#894e47'
  primary: '#2f0805'
  on-primary: '#ffffff'
  primary-container: '#4a1c17'
  on-primary-container: '#c48077'
  inverse-primary: '#ffb4aa'
  secondary: '#5f5e59'
  on-secondary: '#ffffff'
  secondary-container: '#e5e2db'
  on-secondary-container: '#65645f'
  tertiary: '#0b190a'
  on-tertiary: '#ffffff'
  tertiary-container: '#1f2e1d'
  on-tertiary-container: '#859680'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad5'
  primary-fixed-dim: '#ffb4aa'
  on-primary-fixed: '#370d0a'
  on-primary-fixed-variant: '#6d3731'
  secondary-fixed: '#e5e2db'
  secondary-fixed-dim: '#c9c6c0'
  on-secondary-fixed: '#1c1c18'
  on-secondary-fixed-variant: '#474742'
  tertiary-fixed: '#d5e8ce'
  tertiary-fixed-dim: '#b9ccb3'
  on-tertiary-fixed: '#101f0f'
  on-tertiary-fixed-variant: '#3b4b38'
  background: '#fff8f5'
  on-background: '#1e1b18'
  surface-variant: '#e9e1dc'
typography:
  display-lg:
    fontFamily: Libre Caslon Text
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
  headline-lg:
    fontFamily: Libre Caslon Text
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Libre Caslon Text
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  headline-md:
    fontFamily: Libre Caslon Text
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Manrope
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
---

## Brand & Style

This design system is built on the principles of **Sophisticated Traditionalism**. It evokes the tactile quality of a well-preserved archive while maintaining the effortless usability of a modern digital product. The target audience includes genealogy enthusiasts, family historians, and multi-generational families seeking to document their lineage.

The aesthetic blends **Minimalism** with **Tactile** accents. It prioritizes whitespace and high-quality typography to ensure complex genealogical data remains legible. The interface should feel like a premium stationary set—sturdy, intentional, and timeless—evoking an emotional response of reverence, continuity, and warmth.

## Colors

The palette is rooted in natural materials associated with history and the earth. 

- **Primary (Mahogany):** Used for key branding, primary actions, and top-level headings. It provides the "ink" and "wood" anchor for the design.
- **Secondary (Parchment):** The foundation of the UI. This off-white, warm cream is used for page backgrounds and container fills to reduce eye strain compared to pure white.
- **Tertiary (Forest Green):** Used for growth-related elements, such as "adding" family members, confirming connections, or highlighting living relatives.
- **Neutral (Charcoal):** Reserved for body text and subtle UI borders to ensure high contrast without the harshness of pure black.

## Typography

The typography strategy employs a "Heritage Serif" paired with a "Technical Sans." 

- **Libre Caslon Text** is used for headings. Its historical roots and elegant terminals provide the necessary authority and warmth for names and titles.
- **Manrope** is used for all functional data, dates, and body copy. Its modern, geometric construction ensures that dense information—like vital records and lists—remains clear and accessible.
- Titles should generally use a slightly tighter letter-spacing than body text to maintain a formal, printed appearance.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy for desktop to mirror the structured nature of a family tree. On larger screens, the content is centered with generous margins to create a focused, "gallery" feel.

- **Desktop:** 12-column grid with a 1280px max-width.
- **Tablet:** 8-column grid with 32px margins.
- **Mobile:** 4-column grid with 20px margins.

Spacing follows an 8px base unit. Larger gaps (48px+) should be used between major generational sections to allow the tree to "breathe," emphasizing the passage of time between branches.

## Elevation & Depth

Hierarchy is established through **Tonal Layering** and **Soft Ambient Shadows**.

- **Level 0 (Background):** Parchment Cream (#FCF9F2).
- **Level 1 (Cards):** Pure White (#FFFFFF) with a 1px border in a 10% opacity Mahogany.
- **Elevation:** Use very soft, diffused shadows (Blur: 12px, Y: 4px, Color: #4A1C17 at 5% opacity). This creates a "resting on paper" effect rather than a floating digital element.
- **Active State:** Elements should "press" into the surface using a slightly darker border rather than a larger shadow, maintaining the tactile, physical-media feel.

## Shapes

The shape language is **Refined and Rounded**. 

Corners are softened to avoid the clinical feel of sharp angles. While primary cards and buttons use the standard `rounded` (0.5rem) setting, avatars and profile photos should utilize circular framing to contrast with the rectangular structure of the tree. Input fields and secondary containers should use `rounded-lg` (1rem) to feel more approachable.

## Components

- **Family Member Cards:** The core component. Use a white background, a 1px Mahogany border at low opacity, and a vertical layout. The name appears in `headline-md` (Serif), with birth/death dates below in `label-md` (Sans).
- **Buttons:** Primary buttons are solid Mahogany with White text. Secondary buttons are outlined in Forest Green. All buttons have a subtle 0.5px inner glow on the top edge to simulate a beveled paper edge.
- **Connection Lines:** Use 2px solid lines in a muted Mahogany or Taupe. Avoid dashed lines unless representing uncertain/unverified connections.
- **Chips/Badges:** Used for "Direct Ancestor" or "DNA Match" labels. These should have a Forest Green background with white, all-caps `label-sm` text.
- **Input Fields:** Soft cream backgrounds with a Mahogany bottom-border that thickens on focus, mimicking a signature line on a document.
- **Timelines:** Vertical tracks using the Mahogany color, with nodes using the Forest Green for significant life events.