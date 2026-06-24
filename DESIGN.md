---
name: Obsidian Chrome
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#393939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1b1b1b'
  surface-container: '#1f1f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353535'
  on-surface: '#e2e2e2'
  on-surface-variant: '#cfc4c5'
  inverse-surface: '#e2e2e2'
  inverse-on-surface: '#303030'
  outline: '#988e90'
  outline-variant: '#4c4546'
  surface-tint: '#c6c6c6'
  primary: '#c6c6c6'
  on-primary: '#303030'
  primary-container: '#000000'
  on-primary-container: '#757575'
  inverse-primary: '#5e5e5e'
  secondary: '#c6c6c6'
  on-secondary: '#2f3131'
  secondary-container: '#484949'
  on-secondary-container: '#b8b8b8'
  tertiary: '#c6c6c7'
  on-tertiary: '#2f3131'
  tertiary-container: '#000000'
  on-tertiary-container: '#747576'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e2e2e2'
  primary-fixed-dim: '#c6c6c6'
  on-primary-fixed: '#1b1b1b'
  on-primary-fixed-variant: '#474747'
  secondary-fixed: '#e3e2e2'
  secondary-fixed-dim: '#c6c6c6'
  on-secondary-fixed: '#1a1c1c'
  on-secondary-fixed-variant: '#464747'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c7'
  on-tertiary-fixed: '#1a1c1c'
  on-tertiary-fixed-variant: '#454747'
  background: '#131313'
  on-background: '#e2e2e2'
  surface-variant: '#353535'
typography:
  display-lg:
    fontFamily: Hanken Grotesk
    fontSize: 80px
    fontWeight: '700'
    lineHeight: '1.0'
    letterSpacing: -0.04em
  headline-lg:
    fontFamily: Hanken Grotesk
    fontSize: 48px
    fontWeight: '600'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  title-md:
    fontFamily: Hanken Grotesk
    fontSize: 24px
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: 0.05em
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: 0.01em
  body-sm:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: 0.02em
  label-caps:
    fontFamily: Hanken Grotesk
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1.0'
    letterSpacing: 0.2em
spacing:
  unit: 8px
  container-max: 1440px
  gutter: 32px
  margin-desktop: 80px
  margin-mobile: 20px
---

## Brand & Style

The design system is engineered for a high-end luxury fashion audience, blending the raw, industrial power of a "garage" with the refined elegance of haute couture. The personality is unapologetically masculine, bold, and authoritative.

The visual direction combines **Minimalism** with **Glassmorphism**. It utilizes expansive whitespace (or "blackspace" in this context) to allow product imagery to breathe, paired with high-tech frosted surfaces that evoke the look of precision-engineered automotive glass. The aesthetic is monochromatic and sharp, emphasizing structure and premium materiality.

## Colors

The palette is strictly monochromatic to maintain a high-fashion, editorial feel. 

- **Matte Black (#000000):** Used for primary backgrounds and high-impact structural elements. It creates a "void" that makes silver and white elements pop.
- **Metallic Silver (#C0C0C0):** Used for interactive elements, secondary text, and borders. This color should be treated as a metal; where possible, use subtle linear gradients to mimic brushed aluminum.
- **White (#FFFFFF):** Reserved for high-priority typography and essential icons to ensure maximum legibility and focus.
- **Neutral Surface (#121212):** A slight lift from true black to define containers and card backgrounds without losing the dark aesthetic.

## Typography

This design system uses **Hanken Grotesk** to achieve a modern, sharp, and systematic look reminiscent of luxury brand marks. 

- **Display & Headlines:** Set with tight tracking and heavy weights. They should feel architectural and imposing.
- **Labels:** Always use the `label-caps` style for categories, small headers, and buttons to reinforce the premium branding.
- **Body:** Generous line-height is mandatory to maintain readability against the dark background. 
- **Alignment:** Prefer left-aligned or centered layouts; avoid justified text.

## Layout & Spacing

The layout philosophy follows a **Fixed Grid** for desktop and a **Fluid Grid** for mobile. 

- **Desktop:** A 12-column grid with a maximum width of 1440px. Large margins (80px+) are used to create an editorial, "gallery" feel.
- **Spacing Rhythm:** Based on an 8px base unit. Use larger increments (64px, 96px, 128px) for vertical section spacing to maintain the "luxury" of space.
- **Mobile:** Scale down to a 4-column grid. Tighten vertical spacing but maintain the 20px side margins to ensure content doesn't feel cramped.

## Elevation & Depth

Depth is conveyed through transparency and light rather than traditional drop shadows.

- **Glassmorphism:** Navigation bars and modal overlays use a background blur (`backdrop-filter: blur(20px)`) with a 1px Silver (#C0C0C0) border at 10% opacity.
- **Tonal Layers:** Objects closer to the user are lighter. The base is #000000, secondary cards are #121212.
- **Premium Shadows:** When shadows are necessary (e.g., floating action buttons), use extremely large, soft blurs (60px+) with very low opacity (15%) tinted with a hint of Metallic Silver to create a "glow" rather than a shadow.

## Shapes

The design system utilizes **Sharp (0)** roundedness. 

The absence of curves communicates strength, precision, and an uncompromising masculine aesthetic. All buttons, input fields, images, and cards must have hard 90-degree corners. The only exception is the brand logo or specific "garage" badge elements which may remain circular as per the reference brand mark.

## Components

- **Buttons:** Primary buttons are solid White (#FFFFFF) with Black (#000000) text in `label-caps`. Secondary buttons are Ghost-style with a 1px Silver border. Hover states should feature a subtle metallic gradient shift.
- **Input Fields:** Minimalist design—bottom border only (1px Silver). Label sits above in `label-caps`. 
- **Cards:** No borders. Background is either #121212 or a high-contrast product image. Content should be overlaid using glassmorphic panels at the bottom.
- **Chips/Tags:** Small, sharp-edged boxes with 1px Silver borders and 12px uppercase text.
- **Lists:** Separated by thin 1px lines at 5% opacity Silver. 
- **Micro-interactions:** All transitions should be "Slow & Smooth" (e.g., 400ms ease-out). Hovering over an image should produce a slight zoom or a silver "sheen" sweep across the surface.