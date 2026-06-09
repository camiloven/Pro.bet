---
name: Velocity Betting System
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#393939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#c4c9ac'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#8e9379'
  outline-variant: '#444933'
  surface-tint: '#abd600'
  primary: '#ffffff'
  on-primary: '#283500'
  primary-container: '#c3f400'
  on-primary-container: '#556d00'
  inverse-primary: '#506600'
  secondary: '#b3c5ff'
  on-secondary: '#002b75'
  secondary-container: '#0266ff'
  on-secondary-container: '#f9f7ff'
  tertiary: '#ffffff'
  on-tertiary: '#690003'
  tertiary-container: '#ffdad5'
  on-tertiary-container: '#ca0a0f'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#c3f400'
  primary-fixed-dim: '#abd600'
  on-primary-fixed: '#161e00'
  on-primary-fixed-variant: '#3c4d00'
  secondary-fixed: '#dae1ff'
  secondary-fixed-dim: '#b3c5ff'
  on-secondary-fixed: '#001849'
  on-secondary-fixed-variant: '#003fa4'
  tertiary-fixed: '#ffdad5'
  tertiary-fixed-dim: '#ffb4aa'
  on-tertiary-fixed: '#410001'
  on-tertiary-fixed-variant: '#930005'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  headline-xl:
    fontFamily: Archivo Narrow
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Archivo Narrow
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Archivo Narrow
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 28px
  odds-display:
    fontFamily: Archivo Narrow
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-mono:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 4px
  gutter: 12px
  margin-mobile: 16px
  margin-desktop: 32px
  container-max: 1200px
---

## Brand & Style
The design system is engineered for a high-stakes, high-energy sports betting environment. It prioritizes speed, precision, and the psychological thrill of the "win." The aesthetic sits at the intersection of **Modern Corporate** and **Glassmorphism**, leveraging high-density data visualization and sharp, aggressive accents to maintain a professional yet electric atmosphere.

The target audience is data-conscious bettors who value real-time updates and clarity. The UI evokes a sense of "digital command center" functionality, using deep charcoal backgrounds to eliminate visual noise and allow vibrant primary actions to pop with maximum urgency.

## Colors
This design system utilizes a high-contrast dark palette designed for late-night viewing and high-visibility data points.

- **Primary (Electric Lime):** Used exclusively for "winning" states, primary CTA buttons (Place Bet), and active indicators. It signifies success and action.
- **Secondary (Electric Blue):** Dedicated to statistical data, live scores, and informational tooltips. It provides a technical, data-driven counterpoint to the lime.
- **Tertiary (Alert Red):** Reserved for "losing" indicators, odds decreasing, and critical errors.
- **Neutral/Background:** A multi-layered charcoal system. The base is a deep black (`#121212`), with surfaces and cards utilizing a slightly lighter grey (`#1E1E1E`) to create separation.

## Typography
Typography is split into three functional roles to ensure clarity during fast-paced movement.

- **Headlines & Odds:** We use **Archivo Narrow** for its condensed profile, allowing more information (like team names and betting lines) to fit on a single horizontal plane without losing impact.
- **Body Text:** **Inter** provides maximum legibility for rules, terms, and descriptions.
- **Labels & Stats:** **JetBrains Mono** is used for secondary data points, timestamps, and ticket IDs, reinforcing the technical, "calculated" nature of the platform.

## Layout & Spacing
The layout follows a 4px baseline grid to maintain tight, information-dense interfaces. 

- **Mobile:** A 4-column fluid grid with 12px gutters. Speed is prioritized; therefore, critical "Bet" buttons should be pinned to the bottom or span the full width of the card.
- **Desktop:** A 12-column fixed grid. Sidebars are used for persistent "Bet Slips" and navigation, while the center area handles live feeds.
- **Information Density:** Use compact vertical spacing for list items (sports leagues) and wider spacing for promotional hero cards.

## Elevation & Depth
This design system employs **Glassmorphism** to create a sense of layering without using heavy drop shadows that muddy a dark interface.

- **Background:** Solid charcoal (`#121212`).
- **Cards:** Semi-transparent surface (`#1E1E1E` at 80% opacity) with a `1px` white border at 10% opacity. A subtle `20px` backdrop blur is applied to create the frosted glass effect.
- **Active State:** When a card or odds-box is selected, the border color switches to the Primary Electric Lime at 100% opacity, and a subtle outer glow (0px 0px 12px) of the same color is applied.

## Shapes
The shape language is "Soft-Technical." We use a small 4px (Soft) radius for standard elements like buttons and input fields to maintain a precision-engineered look. 

- **Interactive Odds Boxes:** 4px radius.
- **Floating Action Buttons:** Fully pill-shaped to differentiate from data-heavy grid elements.
- **Section Headers:** Sharp 0px left-side accents with a 4px right-side radius to suggest forward motion.

## Components

- **Buttons:** 
  - **Primary:** Solid Electric Lime with black text. High contrast is mandatory.
  - **Secondary:** Transparent background, 1px white border, white text.
- **Odds Cards:** Use a glassmorphic background. Winning odds are highlighted with a lime text color. Increased or decreased odds are marked with small blue (up) or red (down) chevrons.
- **Bet Slip:** A persistent or sliding panel using a slightly darker, more opaque glass effect to indicate its priority over the main feed.
- **Chips:** Used for filtering sports (e.g., "NBA", "NFL"). Inactive: Dark grey background. Active: Blue background with white text.
- **Progress Indicators:** For live games, use a thin blue bar for elapsed time.
- **Input Fields:** Darker than the surface (`#121212`) with a focus state that changes the border to Primary Lime.