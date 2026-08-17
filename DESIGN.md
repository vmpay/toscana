---
name: L'Eredità d'Estate
colors:
  surface: '#f8fcde'
  surface-dim: '#d8ddc0'
  surface-bright: '#f8fcde'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f6d8'
  surface-container: '#ecf1d3'
  surface-container-high: '#e6ebcd'
  surface-container-highest: '#e1e5c8'
  on-surface: '#191d0b'
  on-surface-variant: '#46483e'
  inverse-surface: '#2e321e'
  inverse-on-surface: '#eff4d5'
  outline: '#77786d'
  outline-variant: '#c7c7ba'
  surface-tint: '#5a623d'
  primary: '#272f0f'
  on-primary: '#ffffff'
  primary-container: '#3d4523'
  on-primary-container: '#a9b287'
  inverse-primary: '#c2cb9e'
  secondary: '#705d00'
  on-secondary: '#ffffff'
  secondary-container: '#ffda49'
  on-secondary-container: '#735f00'
  tertiary: '#2b2c27'
  on-tertiary: '#ffffff'
  tertiary-container: '#42423d'
  on-tertiary-container: '#afaea7'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dee7b8'
  primary-fixed-dim: '#c2cb9e'
  on-primary-fixed: '#171e02'
  on-primary-fixed-variant: '#424a28'
  secondary-fixed: '#ffe174'
  secondary-fixed-dim: '#e7c433'
  on-secondary-fixed: '#221b00'
  on-secondary-fixed-variant: '#554500'
  tertiary-fixed: '#e4e3db'
  tertiary-fixed-dim: '#c8c7bf'
  on-tertiary-fixed: '#1b1c17'
  on-tertiary-fixed-variant: '#474742'
  background: '#f8fcde'
  on-background: '#191d0b'
  surface-variant: '#e1e5c8'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 36px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Montserrat
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: 0.01em
  body-md:
    fontFamily: Montserrat
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-caps:
    fontFamily: Montserrat
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
  container-max: 1140px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 64px
---

## Brand & Style

The design system is built upon the concept of a timeless Italian summer—capturing the warmth of afternoon sun on limestone and the quiet elegance of an olive grove. The personality is sophisticated and romantic, yet grounded in a minimalist European sensibility.

The visual style leans into a **Modern Editorial** approach with **Minimalist** and **Tactile** influences. It avoids digital coldness by utilizing organic textures and soft-lit surfaces. The emotional goal is to evoke a sense of heritage, curated intimacy, and sun-drenched tranquility, making the user feel like they are interacting with a high-end physical stationery set or a bespoke Mediterranean travelogue.

## Colors

The palette is rooted in the natural tones of the Mediterranean landscape. 

- **Primary (Deep Olive):** Used for primary text, iconography, and high-emphasis borders. It provides a grounded, authoritative contrast against the cream base.
- **Secondary (Subtle Lemon):** Reserved for high-intent actions, accents, and celebratory highlights. It should be used sparingly to maintain sophistication.
- **Tertiary (Ivory Cream):** The foundational surface color. It replaces pure white to provide a warmer, vintage feel that reduces eye strain and feels more like premium paper.
- **Neutral (Muted Sage):** Used for secondary text, metadata, and subtle dividers to bridge the gap between the dark olive and the ivory background.

## Typography

This design system utilizes a classic pairing of a high-contrast serif and a geometric sans-serif to achieve an editorial feel.

- **Playfair Display** handles all expressive hierarchy. It should be typeset with slightly tighter tracking in large formats to emphasize its elegant strokes. 
- **Montserrat** provides functional clarity. Body text should maintain generous line height to preserve the "airy" Mediterranean atmosphere.
- **Labeling** uses Montserrat in all-caps with increased letter spacing to serve as a clean navigational anchor against the more decorative headlines.

## Layout & Spacing

The layout follows a **Fluid Grid** model with generous margins to mimic the white space found in luxury fashion magazines.

- **Rhythm:** An 8px base unit drives all spacing. For vertical rhythm between sections, use large increments (80px, 120px) to allow the content to "breathe."
- **Desktop:** 12-column grid with wide gutters (24px) and significant outer margins (64px) to center the experience.
- **Mobile:** 4-column grid with 20px margins. Headlines should scale down, but body text remains legible at 16px-18px.
- **Alignment:** Centralized alignment is preferred for storytelling sections (Invites, Story, RSVP hero), while functional layouts (Registry, Itinerary) should follow a structured left-aligned grid.

## Elevation & Depth

Depth in this design system is achieved through **Tonal Layers** and **Low-Contrast Outlines** rather than heavy shadows.

- **Surfaces:** Use subtle shifts in opacity of the Primary color (Olive) on top of the Ivory background to create "wells" or "raised" containers. 
- **Outlines:** Instead of shadows, use 1px solid strokes in a faded Olive (#3D4523 at 15% opacity) to define cards and input fields.
- **Glassmorphism:** For floating navigation bars, use a heavy backdrop blur (20px) with a semi-transparent Ivory fill (#FFFDF5 at 80% opacity) to simulate the look of frosted glass or mist over the coast.

## Shapes

The shape language is **Soft** and restrained. We avoid sharp, aggressive corners to maintain the romantic aesthetic, but we avoid "bubbly" pill shapes to preserve sophistication.

- **Standard Elements:** Buttons and cards use a 0.25rem (4px) radius.
- **Image Treatment:** Photography should use the same soft rounding. For a more "vintage postcard" feel, occasionally use an arched top (radius-top: 50%) for featured imagery.

## Components

- **Buttons:** Primary buttons are solid Olive with Ivory text. Secondary buttons are Ivory with an Olive border. Text is always uppercase Montserrat for a structured, clean look.
- **Cards:** Cards should be minimal, defined by a 1px soft border or a very subtle background tint. No heavy dropshadows.
- **Input Fields:** Use "Underline" style inputs (border-bottom only) for a more elegant, stationery-like feel, or soft-rounded boxes with a 1px border.
- **Chips/Tags:** Used for "Dress Code" or "Dietary" labels. These use the Subtle Lemon background with Olive text to draw attention without being loud.
- **Lists:** Use custom icons for list bullets, such as a small olive branch or a simple refined serif numeral.
- **RSVP Toggle:** Use a custom-styled radio group that feels like a physical "check the box" on a wedding invitation, using the primary olive color for the selection state.