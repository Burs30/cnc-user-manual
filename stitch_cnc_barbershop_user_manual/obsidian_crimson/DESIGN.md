---
name: Obsidian & Crimson
colors:
  surface: '#1e0f10'
  surface-dim: '#1e0f10'
  surface-bright: '#473535'
  surface-container-lowest: '#180a0b'
  surface-container-low: '#271718'
  surface-container: '#2b1b1c'
  surface-container-high: '#372626'
  surface-container-highest: '#423030'
  on-surface: '#f9dcdb'
  on-surface-variant: '#e3bebd'
  inverse-surface: '#f9dcdb'
  inverse-on-surface: '#3e2c2c'
  outline: '#aa8989'
  outline-variant: '#5b4040'
  surface-tint: '#ffb3b4'
  primary: '#ffb3b4'
  on-primary: '#680016'
  primary-container: '#c41e3a'
  on-primary-container: '#ffdada'
  inverse-primary: '#ba1434'
  secondary: '#e6c364'
  on-secondary: '#3d2e00'
  secondary-container: '#785d00'
  on-secondary-container: '#fdd977'
  tertiary: '#80d5d1'
  on-tertiary: '#003735'
  tertiary-container: '#00716e'
  on-tertiary-container: '#9cf2ed'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdad9'
  primary-fixed-dim: '#ffb3b4'
  on-primary-fixed: '#40000a'
  on-primary-fixed-variant: '#920023'
  secondary-fixed: '#ffe08f'
  secondary-fixed-dim: '#e6c364'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#584400'
  tertiary-fixed: '#9cf1ed'
  tertiary-fixed-dim: '#80d5d1'
  on-tertiary-fixed: '#00201f'
  on-tertiary-fixed-variant: '#00504d'
  background: '#1e0f10'
  on-background: '#f9dcdb'
  surface-variant: '#423030'
typography:
  h1:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  h2:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  body:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: '0'
  label:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1'
    letterSpacing: 0.08em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  container-padding: 24px
  gutter: 16px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
  section-gap: 80px
---

## Brand & Style

This design system establishes a high-end, masculine grooming aesthetic centered on precision and exclusivity. The brand personality is disciplined, sharp, and uncompromisingly modern. By utilizing a "Dark Luxury" approach, the interface mimics the atmosphere of a premium, dimly lit barbershop where craftsmanship is the primary focus.

The design style is a hybrid of **Minimalism** and **High-Contrast Bold**. It relies on flat surfaces, razor-sharp alignment, and a aggressive lack of depth indicators like shadows or gradients. The emotional response is one of confidence and status, achieved through the stark contrast between deep charcoal foundations and surgical crimson accents.

## Colors

The palette is strictly curated to eliminate warmth and visual noise. The foundation is a pure, flat black-charcoal (#0F0F0F), providing a void-like canvas that makes typography and accents pop. 

- **Primary Action:** Crimson (#C41E3A) is used exclusively for high-intent actions, signaling urgency and passion.
- **Accents:** Gold (#C9A84C) is reserved for status indicators, "Master Barber" designations, or premium membership badges.
- **Surfaces:** Surface containers (#1A1A1A) provide the only structural variance, creating a subtle lift without the need for traditional shadows.
- **Interaction:** Borders and ghost elements use ultra-low opacity white to maintain a sleek, almost invisible technical grid.

## Typography

The design system utilizes **Inter** for its utilitarian precision and neutral character. The type scale is designed to create a heavy visual hierarchy:

- **Headlines:** Use an extra-bold weight and tight tracking to create a "blocky" and authoritative presence.
- **Body:** Set with generous line-height (1.6) to ensure maximum readability against the dark background, preventing text "glow" or eye strain.
- **Labels:** Strictly uppercase with increased letter spacing (0.08em) to evoke the feel of high-end product labeling and industrial stamping.

## Layout & Spacing

This design system follows a **Fixed Grid** philosophy for desktop and a strict **Fluid Grid** for mobile. The layout is built on an 8px rhythmic increment.

- **Margins:** Standard card and container padding is locked at 24px to ensure breathing room.
- **Grid:** A 12-column grid with 16px gutters is used for layout organization. 
- **Alignment:** All content must be hard-aligned to the left to maintain the structured, masculine aesthetic. Centered text should be avoided except for hero headlines.

## Elevation & Depth

Depth is conveyed through **Tonal Layering** and **Low-Contrast Outlines**. 

1. **Base Layer:** The page background (#0F0F0F) represents the furthest point of depth.
2. **Surface Layer:** Cards and containers (#1A1A1A) sit directly on the background.
3. **Detail Layer:** Borders (rgba(255,255,255,0.05)) define the boundaries of surfaces.

Shadows are strictly prohibited. The interface should feel like a solid, physical object where depth is carved out rather than projected. This creates a flat, architectural feel consistent with premium grooming packaging.

## Shapes

The shape language is a deliberate contrast between structured containers and organic action elements:

- **Primary Actions:** Buttons use a full pill-shape (56px radius), creating a distinct "touchable" silhouette that stands out against the rectangular grid.
- **Containers:** Cards and surfaces use a 12px radius, providing a modern "soft-rectilinear" feel that isn't as aggressive as sharp 0px corners.
- **Selection Elements:** Radio buttons and checkboxes follow the pill-shape logic (circular) to signify interactability.

## Components

### Buttons
- **Primary:** Crimson (#C41E3A) background with White (#FAFAF8) text. 56px height, 56px border-radius.
- **Ghost:** Transparent background, 1px border (rgba(255,255,255,0.1)), White text.
- **Interaction:** On hover, the primary button should shift to a slightly brighter crimson; ghost buttons should increase border opacity to 0.2.

### Cards
- **Construction:** Surface color #1A1A1A, 12px radius, 24px internal padding.
- **Border:** A consistent 1px stroke of rgba(255,255,255,0.05) is mandatory to separate the card from the background.

### Input Fields
- **Style:** Background #0F0F0F (inset look) with a 1px border. 
- **Focus:** The border color transitions from the default subtle border to the Gold (#C9A84C) accent to indicate active state.

### Lists & Bookings
- **Time Slots:** Use the Label style for times, contained within ghost-style small capsules.
- **Service Items:** Use H2 for pricing and Body for descriptions, separated by the system border (rgba(255,255,255,0.05)).

### Additional Elements
- **Selection Chips:** Used for barber selection or service categories. When selected, the background becomes Crimson; when unselected, they remain Ghost style.