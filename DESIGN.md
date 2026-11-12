---
name: Smart Circular Interface
colors:
  surface: '#f7f9ff'
  surface-dim: '#d7dadf'
  surface-bright: '#f7f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f1f4f9'
  surface-container: '#ebeef3'
  surface-container-high: '#e5e8ee'
  surface-container-highest: '#e0e3e8'
  on-surface: '#181c20'
  on-surface-variant: '#404943'
  inverse-surface: '#2d3135'
  inverse-on-surface: '#eef1f6'
  outline: '#707973'
  outline-variant: '#bfc9c1'
  surface-tint: '#2c694e'
  primary: '#0f5238'
  on-primary: '#ffffff'
  primary-container: '#2d6a4f'
  on-primary-container: '#a8e7c5'
  inverse-primary: '#95d4b3'
  secondary: '#386380'
  on-secondary: '#ffffff'
  secondary-container: '#b2dcfe'
  on-secondary-container: '#37627f'
  tertiary: '#5a4400'
  on-tertiary: '#ffffff'
  tertiary-container: '#775b06'
  on-tertiary-container: '#fcd579'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#b1f0ce'
  primary-fixed-dim: '#95d4b3'
  on-primary-fixed: '#002114'
  on-primary-fixed-variant: '#0e5138'
  secondary-fixed: '#c9e6ff'
  secondary-fixed-dim: '#a1cced'
  on-secondary-fixed: '#001e2f'
  on-secondary-fixed-variant: '#1d4b67'
  tertiary-fixed: '#ffdf96'
  tertiary-fixed-dim: '#e7c268'
  on-tertiary-fixed: '#251a00'
  on-tertiary-fixed-variant: '#5a4400'
  background: '#f7f9ff'
  on-background: '#181c20'
  surface-variant: '#e0e3e8'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.015em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 34px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.005em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  title-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.03em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system establishes an architectural, high-trust environment bridging complex industrial clean-tech hardware with enterprise software and consumer touchpoints. The aesthetic communicates rigor, environmental stewardship, and modern operational efficiency without falling into naive "eco" clichés. 

### Visual Archetype & Principles
- **Modern High-Contrast Precision:** Visual structure relies on crisp borders, intentional white space, and rich chromatic accents. Surfaces are pure, functional, and devoid of frivolous ornamentation.
- **Zero Clutter, Maximum Density Balance:** Complex CRM telemetry, sensor streams, and inventory flows share the same typographic and spatial clarity as the direct-to-consumer Bin purchasing and subscription onboarding flows.
- **Inclusive & Resilient (WCAG AAA Focus):** High-ratio contrast standards govern all interactive states, data states, and textual layouts, ensuring effortless legibility in high-glare environments (e.g., floor audits, warehouse dispatch, fleet management).
- **Physical-Digital Continuity:** Interactive digital touchpoints echo the industrial precision of the Smart Bin IA hardware—sturdy geometries, intentional tactile controls, and high-visibility status telemetry.

## Colors

The palette directly honors structural materials, clean energy, and sorted waste streams while rigorously meeting accessible contrast criteria.

### Palette Architecture
- **Primary / Verde Orgánico (`#2D6A4F`):** Anchors core brand actions, positive environmental telemetry, confirmed automated sorting triggers, and primary CTA vectors. Paired with pure white (`#FFFFFF`) or light surface neutral (`#F8F9FA`), it achieves >7:1 AAA contrast.
- **Secondary / Azul PET (`#1B4965`):** Represents industrial stability, enterprise CRM structures, operational telemetry, and navigation rails. Drives deep authority across data visualization and recurring service agreements.
- **Accent / Amarillo Reciclables (`#E9C46A`):** High-visibility highlight dedicated to system warnings, pending container bin pick-ups, telemetry outliers, and accent tags. For text applications, deep tinting (`#7A5E0B`) is enforced to preserve contrast ratios.
- **Base & Canvas (`#FFFFFF` & `#F8F9FA`):** Crisp, untinted backgrounds keep visual noise at absolute zero. Tonal differentiation across enterprise card grids and CRM tables uses `#F1F3F5` and `#E9ECEF`.
- **Text & Structure (`#212529`):** Neutral dark charcoal for all body and heading content, eliminating eye fatigue associated with stark `#000000` while preserving unmatched readability.
- **System States:**
  - **Success / Bin Operational:** `#1B4332`
  - **Attention / Fill Threshold:** `#D97706`
  - **Critical Alert / AI Jam:** `#BC4749`
  - **Focus Outline:** High-visibility double-ring with `#1B4965` outer and `#FFFFFF` offset.

## Typography

The typographic hierarchy combines the confident, geometric presence of **Plus Jakarta Sans** for headlines and high-impact values with the neutral, hyper-legible engineering of **Inter** for UI controls, transactional tables, and data streams.

### Typographic Rules
- **Proportional Tabular Numerics:** For bin weight telemetry, sensor capacities, pricing models, and sorting counters, activate OpenType `tnum` (tabular figures) across all `Inter` styles to ensure aligned numerical comparisons.
- **Editorial Legibility:** Body copy should maintain a measure of 45 to 75 characters per line. Body copy never falls below 13px to ensure accessibility across mobile operational units.
- **Heading Restraint:** Display and headline levels rely on strict negative tracking (`-0.01em` to `-0.02em`) to maintain structural density on dashboard cards and marketing banners.

## Layout & Spacing

The layout model uses an 8px base spatial grid adapted for both complex CRM workflows and high-converting B2B/B2C e-commerce checkout funnels.

### Grid & Responsiveness
- **Desktop (1200px+):** 12-column responsive fluid grid. `margin: 2.5rem`, `gutter: 1.5rem`. Enables multi-column pipeline views, live telemetry matrices, and inventory control boards alongside split-screen hardware customizers.
- **Tablet (768px – 1199px):** 8-column grid. `margin: 2rem`, `gutter: 1.25rem`. Collapses secondary sidebars into fixed utility trays; CRM lead records adopt structured stacked cards.
- **Mobile (< 768px):** 4-column grid. `margin: 1rem`, `gutter: 1rem`. Bottom navigation replaces vertical toolbars; sensor telemetry simplifies to linear vertical cards; checkout steps transition to single-column accordions.

### Rhythmic Discipline
- Spacing within components relies strictly on standard multiples: `space-xs` (4px) for badge and chip insets, `space-sm` (8px) for input padding and compact gaps, `space-md` (16px) for module padding, and `space-xl` (40px) for macro section separations.

## Elevation & Depth

This design system deliberately minimizes dramatic dropshadows to preserve a modern, precise look. Depth is conveyed primarily through tonal separation, crisp borders, and subtle ambient light.

### Elevation Hierarchy
- **Level 0 (Flat / Canvas):** Pure background surfaces (`#FFFFFF` and `#F8F9FA`). No shadows or borders. Used for base viewport canvasing and background structural divisions.
- **Level 1 (Card & Module Resting):** Crisp 1px structural border in `#DEE2E6` over `#FFFFFF`. Zero drop shadow. Used for dashboard widgets, telemetry modules, and checkout summary rows.
- **Level 2 (Active & Interactive Hover):** Tonal surface lift paired with an ambient tinted shadow: `box-shadow: 0 4px 12px -2px rgba(27, 73, 101, 0.08), 0 2px 4px -1px rgba(27, 73, 101, 0.04)`. Border shifts to `#1B4965`.
- **Level 3 (Overlays, Flyouts & Modals):** Crisp 1px border in `#CED4DA` supported by directional ambient depth: `box-shadow: 0 12px 32px -4px rgba(33, 37, 41, 0.12), 0 4px 8px -2px rgba(33, 37, 41, 0.04)`. Accompanied by a non-blurry, accessible backdrop scrim (`rgba(33, 37, 41, 0.6)`).

## Shapes

The design system incorporates a disciplined, engineered shape profile (`roundedness: 1`). Soft, subtle radii (4px base, 8px on cards, 12px on modals) reflect the precise manufactured tolerances of the Smart Bin IA hardware casing.

### Radii Tokens
- **Base (0.25rem / 4px):** Applied to buttons, text inputs, table cell selections, status tags, and inline badges.
- **Large (0.5rem / 8px):** Applied to telemetry cards, dashboard widgets, pricing tier wrappers, and service contract cards.
- **Extra Large (0.75rem / 12px):** Reserved exclusively for root dialogs, global slide-over panels, and primary hardware showcase viewports.
- **Pill (Fully Rounded):** Never used for primary structural containers; strictly reserved for circular notification counters and small status indicator chips.

## Components

### Buttons
- **Primary Button (Verde Orgánico):** Solid `#2D6A4F` background, `#FFFFFF` text (`label-lg`), 4px border radius. 44px minimum touch height (`padding: 0.625rem 1.25rem`). Active state: `#1E4735`. Hover state: `#245640`. Focused: 2px offset ring in `#1B4965`.
- **Secondary Button (Azul PET):** Ghost or outlined variant with 1.5px solid `#1B4965`, `#1B4965` text. On hover: fills with `#1B4965` at 8% opacity.
- **Maintenance / Accent Button:** Reserved for service contract triggers, dispatch alerts, and warranty activations. Uses `#E9C46A` surface with contrasting dark neutral `#212529` text.

### Chips & Badges
- **Bin Sensor Status:** Structured pill chips. Text set in `label-sm` (`font-weight: 600`).
  - *Organic / Compost Ready:* `#2D6A4F` tinted surface (10% tint), `#1B4332` text, 1px solid `#2D6A4F` border.
  - *Plastic / PET Detected:* `#1B4965` tinted surface (10% tint), `#1B4965` text, 1px solid `#1B4965` border.
  - *Service Pending:* `#E9C46A` solid tint, `#614B00` text, 1px solid `#D4A33B` border.

### Input Fields & Selectors
- Standard height: 40px (compact CRM grid) or 48px (consumer checkout).
- Surface: `#FFFFFF` with 1px border `#CED4DA`. Focused state shifts border to 2px `#1B4965` with 0px blur ring, ensuring distinct clarity.
- Error state: 1.5px solid `#BC4749` accompanied by an inline icon and descriptive text in `#BC4749`.

### Checkboxes & Radios
- Size: 18px x 18px with a crisp 1.5px border `#6C757D`.
- Selected state: Inset checkmark/disc in `#FFFFFF` backed by a solid `#2D6A4F` surface. Provides clear visible distinction from standard form text.

### Cards & Telemetry Surfaces
- Pure `#FFFFFF` surface with a 1px border in `#E9ECEF`.
- Card headers enforce a clear boundary with an internal `0.75rem` vertical split, housing the module title in `title-md` (`#212529`) alongside live operational status indicators.

### Clean-Tech Domain Components
- **Bin Fill Gauge:** Horizontal segmented tracker showing volumetric AI sorting metrics (Organic vs. PET vs. Non-recyclable), utilizing strictly defined brand colors without ambiguous intermediate gradients.
- **Service Plan Switcher:** Side-by-side selectable module comparing standard self-service cycles with "Smart Total Maintenance" plans, displaying SLA guarantees, dispatch schedules, and automatic replacement criteria.