---
name: Fresh Harvest Agritech
colors:
  surface: '#f9f9ff'
  surface-dim: '#cfdaf2'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f0f3ff'
  surface-container: '#e7eeff'
  surface-container-high: '#dee8ff'
  surface-container-highest: '#d8e3fb'
  on-surface: '#111c2d'
  on-surface-variant: '#404941'
  inverse-surface: '#263143'
  inverse-on-surface: '#ecf1ff'
  outline: '#717970'
  outline-variant: '#c0c9be'
  surface-tint: '#2e6a41'
  primary: '#003b1b'
  on-primary: '#ffffff'
  primary-container: '#14532d'
  on-primary-container: '#87c695'
  inverse-primary: '#96d5a3'
  secondary: '#006e2f'
  on-secondary: '#ffffff'
  secondary-container: '#6bff8f'
  on-secondary-container: '#007432'
  tertiary: '#5d1d00'
  on-tertiary: '#ffffff'
  tertiary-container: '#822c00'
  on-tertiary-container: '#ff9f7a'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#b1f2be'
  primary-fixed-dim: '#96d5a3'
  on-primary-fixed: '#00210d'
  on-primary-fixed-variant: '#12512c'
  secondary-fixed: '#6bff8f'
  secondary-fixed-dim: '#4ae176'
  on-secondary-fixed: '#002109'
  on-secondary-fixed-variant: '#005321'
  tertiary-fixed: '#ffdbce'
  tertiary-fixed-dim: '#ffb599'
  on-tertiary-fixed: '#370e00'
  on-tertiary-fixed-variant: '#7f2b00'
  background: '#f9f9ff'
  on-background: '#111c2d'
  surface-variant: '#d8e3fb'
typography:
  headline-xl:
    fontFamily: Manrope
    fontSize: 44px
    fontWeight: '800'
    lineHeight: 52px
  headline-xl-mobile:
    fontFamily: Manrope
    fontSize: 30px
    fontWeight: '800'
    lineHeight: 38px
  headline-lg:
    fontFamily: Manrope
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Manrope
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  headline-md:
    fontFamily: Manrope
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-sm:
    fontFamily: Manrope
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  title-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
  title-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
  label-sm:
    fontFamily: Inter
    fontSize: 10px
    fontWeight: '600'
    lineHeight: 14px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.25rem
  gutter-desktop: 1.5rem
  margin: 1rem
  margin-tablet: 1.5rem
  margin-desktop: 2.5rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style
The design system establishes a high-trust, resilient, and transparent digital infrastructure for the agricultural supply chain in Bangladesh. It connects rural growers, wholesale regional hubs (*aroths*), and urban commercial buyers with speed and geographic clarity.

The aesthetic fuses modern high-utility B2B enterprise software with the vibrant, tactile freshness of farm-direct produce. It sits at the intersection of **Clean Modernism** and **Tactile Utility**: crisp data density, structured logistical feeds, and hyper-legible status tracking balanced by organic, rich field tones and soft, human-scale geometry. The emotional tone is dependable, grounded, fresh, and industrious—instilling confidence in pricing, cold-chain transparency, and field-to-fork delivery speeds.

## Colors
The palette is rooted in agricultural vitality and logistic certitude:

- **Primary (`#14532D` - Deep Forest Green):** Anchors navigation, structural headers, high-emphasis action surfaces, and corporate governance tokens. It communicates maturity, trust, and deep agricultural roots.
- **Secondary (`#22C55E` - Leaf Green):** Represents freshness, positive fulfillment status, stock verification, and dynamic calls-to-action.
- **Tertiary (`#EA580C` - Harvest Sunburst):** A warm, high-visibility orange-gold used strategically for inventory alerts, auction deadlines, harvest windows, transit alerts, and urgent cart/bidding milestones.
- **Neutral (`#1E293B` - Slate Deep):** Delivers clean contrast against backdrops for typography, analytical metrics, and crisp linear data tables.
- **Canvas / Background (`#F9FAF6` - Warm Crisp Cream):** Replaces harsh sterile whites with an organic, sun-bleached linen-tinted paper feel, reducing field glare and digital eye fatigue.
- **Surfaces & Borders:** Container cards sit on `#FFFFFF` with borders tinted in `#E2E8D8` to keep dividers feeling biological yet engineered.

## Typography
The system employs **Manrope** for primary headings and structural numerical calls, delivering geometric balance with friendly, organic curves. **Inter** handles high-density marketplace tables, dispatch tracking slips, SKU specifications, and body content, offering pristine multi-resolution legibility.

All numerical and monetary metrics (e.g., Taka rates per maund/kg, metric tonnage, moisture readings) utilize tabular figures (`tnum`) to maintain structural vertical alignment across live ticker rows and invoice manifests.

## Layout & Spacing
The layout relies on a responsive 12-column grid system for desktop and tablet viewports, collapsing into a fluid 4-column system for field agents on mobile devices.

- **Mobile (<768px):** 4 columns, `margin` = `1rem`, `gutter` = `1rem`. Prioritizes full-width interactive cards, thumb-friendly tap targets, and sticky bottom utility bars for route and cart tracking.
- **Tablet (768px–1024px):** 8 columns, `margin-tablet` = `1.5rem`, `gutter` = `1.25rem`. Facilitates split-screen order logs alongside map-based origin routing.
- **Desktop (>1024px):** 12 columns, max-width `1440px`, `margin-desktop` = `2.5rem`, `gutter-desktop` = `1.5rem`. Enables side-by-side terminal layouts with live price charts, multi-district inventory filters, and logistics scheduling.

## Elevation & Depth
Elevation emphasizes tonal separation and low-intensity ambient diffusion over artificial drop shadows:

- **Surface Levels:** 
  - *Base Layer:* `#F9FAF6` (Canvas).
  - *Card Tier:* Pure `#FFFFFF` resting atop canvas, defined primarily by a fine 1px border (`#E2E8D8`).
  - *Overlay Tier:* Modals, bottom sheets, and popovers use pure `#FFFFFF` with an ambient glow (`box-shadow: 0 12px 32px -4px rgba(20, 83, 45, 0.08), 0 4px 12px -2px rgba(30, 41, 59, 0.04)`).
- **Tactile Boundaries:** To perform reliably under bright outdoor sunlight across agricultural hubs, contrast is maintained via precise hairline borders (`1px solid #E2E8D8`) rather than shadow gradients alone.

## Shapes
A roundedness level of `2` provides a friendly, contemporary curve that balances agro-organic softness with structured data discipline.

- **Base Components (Inputs, Small Badges, Buttons):** `0.5rem` (`8px`) corner radius.
- **Cards and Analytical Panels:** `1rem` (`16px`) corner radius.
- **Modals, Regional Drawers, and Floating Filter Panels:** `1.5rem` (`24px`) corner radius.
- **Pill Exceptions:** Status chips, logistics tags, and geolocation trackers use full rounded ends (`9999px`) to emphasize clickable micro-states.

## Components

### Buttons
- **Primary:** Background `#14532D`, label `#FFFFFF`, border-radius `0.5rem`. Hover shifts to `#166534`. Active state subtly presses downward (`scale(0.99)`).
- **Secondary / Direct Buy:** Background `#22C55E`, label `#052E16`, bold tracking for quick field acceptance.
- **Outline / Filter:** Background transparent, border `1px solid #E2E8D8`, text `#1E293B`. Hover shifts background to `#F0FDF4` and border to `#86EFAC`.

### Chips & Status Badges
- **Origin/District Tags:** Pill-shaped, background `#F0FDF4`, border `1px solid #BBF7D0`, text `#14532D` (e.g., "Bogra Hub", "Jessore Cold-Store").
- **Quality Grade Chips:** Pill-shaped, background `#FEF3C7`, text `#92400E` (e.g., "Grade A - Export Quality").
- **Live Dispatch:** Background `#FFEDD5`, text `#C2410C`, paired with a pulsating green or orange dot for real-time truck tracking.

### Inputs & Selector Controls
- **Fields:** Background `#FFFFFF`, border `1px solid #CBD5E1`, border-radius `0.5rem`, padding `0.75rem 1rem`. Focus state rings `#14532D` with an offset outline of `2px solid rgba(20, 83, 45, 0.2)`.
- **Location Selector:** Dropdown displaying dual-tier hierarchy (District / Upazila) integrated with a pin icon and real-time transit ETA indicators.

### Cards
- **Product Listing Card:** Pure white container with `1rem` radius and a `1px solid #E2E8D8` border. Image container framed in an inner soft cream border. Footer clearly splits live rate per kg/maund, minimum order quantity (MOQ), and an integrated one-tap booking action.
- **Logistics Route Card:** Displays truck load progress bars, real-time temperature telemetry (`°C`), and multi-stop progress nodes using primary green and harvest orange accents.

### Checkboxes & Radios
- Square with soft `4px` corners for checkboxes; circular for radios. In active state, filled with `#14532D` and a crisp white indicator.