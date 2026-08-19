---
name: Ceria Belajar
colors:
  surface: '#fbf9f8'
  surface-dim: '#dbd9d9'
  surface-bright: '#fbf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3f3'
  surface-container: '#efeded'
  surface-container-high: '#eae8e7'
  surface-container-highest: '#e4e2e2'
  on-surface: '#1b1c1c'
  on-surface-variant: '#414755'
  inverse-surface: '#303030'
  inverse-on-surface: '#f2f0f0'
  outline: '#717786'
  outline-variant: '#c1c6d7'
  surface-tint: '#005bc1'
  primary: '#0058bc'
  on-primary: '#ffffff'
  primary-container: '#0070eb'
  on-primary-container: '#fefcff'
  inverse-primary: '#adc6ff'
  secondary: '#705d00'
  on-secondary: '#ffffff'
  secondary-container: '#fdd400'
  on-secondary-container: '#6f5c00'
  tertiary: '#894d00'
  on-tertiary: '#ffffff'
  tertiary-container: '#ac6300'
  on-tertiary-container: '#fffbff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d8e2ff'
  primary-fixed-dim: '#adc6ff'
  on-primary-fixed: '#001a41'
  on-primary-fixed-variant: '#004493'
  secondary-fixed: '#ffe170'
  secondary-fixed-dim: '#e9c400'
  on-secondary-fixed: '#221b00'
  on-secondary-fixed-variant: '#544600'
  tertiary-fixed: '#ffdcbf'
  tertiary-fixed-dim: '#ffb874'
  on-tertiary-fixed: '#2d1600'
  on-tertiary-fixed-variant: '#6a3b00'
  background: '#fbf9f8'
  on-background: '#1b1c1c'
  surface-variant: '#e4e2e2'
typography:
  headline-xl:
    fontFamily: Quicksand
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Quicksand
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 38px
  headline-lg:
    fontFamily: Quicksand
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-md:
    fontFamily: Quicksand
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Be Vietnam Pro
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Be Vietnam Pro
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-lg:
    fontFamily: Be Vietnam Pro
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
  label-sm:
    fontFamily: Be Vietnam Pro
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  gutter: 20px
  margin-mobile: 16px
  margin-desktop: 64px
---

## Brand & Style

The brand personality is **Playful Professional**. It balances the joy and wonder of childhood with the academic rigor expected by parents. The design must evoke feelings of safety, growth, and enthusiastic discovery. 

The aesthetic leverages a **Modern-Playful** approach, utilizing soft geometry and a "layered paper" look to create depth without overwhelming the user. While the colors are vibrant, the use of generous whitespace ensures the interface remains organized and trustworthy for parents navigating educational programs. The UI should feel like a premium educational toy: tactile, responsive, and intuitively structured.

## Colors

This design system utilizes a vibrant, high-energy palette to stimulate engagement:

- **Primary (Bright Blue):** Used for main actions, navigation, and trust-building elements.
- **Secondary (Sun Yellow):** Used for highlights, achievements, and capturing attention in a friendly way.
- **Accent (Friendly Orange & Green):** Orange is used for urgency/notices, while Green signifies progress, success, and nature-themed learning modules.
- **Neutrals:** Soft charcoals and warm grays are used for text and borders to maintain readability and avoid the "harshness" of pure black.
- **Backgrounds:** Off-white or extremely subtle cream tints are preferred over stark white to create a warmer, more inviting atmosphere.

## Typography

Typography plays a dual role: the headlines provide the "Playful" character, while the body text provides the "Professional" clarity.

- **Headlines (Quicksand):** Round terminals and a high x-height make these feel approachable. Use Primary or Neutral-Dark for headlines.
- **Body & Labels (Be Vietnam Pro):** A contemporary sans-serif that ensures long-form reading (like program descriptions or blogs) is effortless for parents.
- **Hierarchy:** Use heavy weights (700) for headers to create strong visual anchors. Maintain a 1.5x line-height for body text to ensure maximum legibility for busy parents scanning information.

## Layout & Spacing

The layout philosophy is **Fluid & Spaced**. We avoid cramped interfaces to mirror the freedom of a learning environment.

- **Grid:** Use a 12-column grid for desktop and a 4-column grid for mobile. 
- **Rhythm:** Spacing follows an 8px base unit. Component internal padding should favor "breathability" (e.g., using `md` or `lg` padding for cards).
- **Adaptability:** On mobile, margins should be tight (16px) to maximize screen real estate for large touch targets, while desktop layouts should use wide margins (64px+) to prevent line lengths from becoming too long.

## Elevation & Depth

To achieve the "Playful Professional" look, we use **Ambient Soft Shadows** rather than flat lines or harsh borders.

- **Surfaces:** Use white or very light tinted containers against a subtly darker background to create a "layered paper" effect.
- **Shadows:** Shadows should be long, diffused, and slightly tinted with the Primary color (e.g., a 10% opacity blue shadow). This makes elements feel like they are floating gently above the surface.
- **Interaction Depth:** When a user hovers over a card or button, it should "lift" (the shadow becomes more diffused and the element scales slightly, roughly 1.02%). On click, it should "sink" back to the surface.

## Shapes

The shape language is consistently **Rounded**. 

- **Containers:** Standard cards and input fields use `rounded-lg` (16px).
- **CTAs:** Large buttons use `rounded-xl` (24px) or full pill-shape to look "squishy" and inviting to click.
- **Illustrations:** Use hand-drawn, organic shapes for background decorative elements (blobs or sprinkles) to break the rigidity of the grid. Icons must be hand-drawn/doodle-style with slightly irregular line weights to maintain the playful vibe.

## Components

- **Buttons:** Large, high-contrast buttons. Primary CTAs use the Sun Yellow with Blue text for maximum visibility. Secondary buttons use an outline style with a 2px thickness.
- **Cards:** Cards should have a white background, soft shadow, and a 1px subtle border. They are used to group "Program Calistung" modules.
- **Chips:** Small, rounded indicators for age groups (e.g., "3-5 Tahun"). Use different pastel tints of the accent colors for different categories.
- **Input Fields:** Thick 2px borders that change color to Primary when focused. Use large placeholder text to make forms feel less intimidating.
- **Lists:** Use custom icons (like a small sun or star) instead of standard bullets to keep the learning theme consistent.
- **Feedback Elements:** Use Green for "Sukses" and Orange for "Peringatan," always accompanied by a friendly icon to soften the tone of the message.