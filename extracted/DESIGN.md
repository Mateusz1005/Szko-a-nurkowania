---
name: Oceanic Abyssal Glass
colors:
  surface: '#041329'
  surface-dim: '#041329'
  surface-bright: '#2c3951'
  surface-container-lowest: '#010e24'
  surface-container-low: '#0d1c32'
  surface-container: '#112036'
  surface-container-high: '#1c2a41'
  surface-container-highest: '#27354c'
  on-surface: '#d6e3ff'
  on-surface-variant: '#bcc9ce'
  inverse-surface: '#d6e3ff'
  inverse-on-surface: '#233148'
  outline: '#869398'
  outline-variant: '#3d494d'
  surface-tint: '#4cd6fb'
  primary: '#4cd6fb'
  on-primary: '#003642'
  primary-container: '#00b4d8'
  on-primary-container: '#00414f'
  inverse-primary: '#00677d'
  secondary: '#ffb4a3'
  on-secondary: '#630f00'
  secondary-container: '#8f1b01'
  on-secondary-container: '#ffa08a'
  tertiary: '#27e0a9'
  on-tertiary: '#003827'
  tertiary-container: '#00bb8b'
  on-tertiary-container: '#004430'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#b3ebff'
  primary-fixed-dim: '#4cd6fb'
  on-primary-fixed: '#001f27'
  on-primary-fixed-variant: '#004e5f'
  secondary-fixed: '#ffdad2'
  secondary-fixed-dim: '#ffb4a3'
  on-secondary-fixed: '#3d0600'
  on-secondary-fixed-variant: '#8c1900'
  tertiary-fixed: '#54fdc4'
  tertiary-fixed-dim: '#27e0a9'
  on-tertiary-fixed: '#002116'
  on-tertiary-fixed-variant: '#00513b'
  background: '#041329'
  on-background: '#d6e3ff'
  surface-variant: '#27354c'
typography:
  display-hero:
    fontFamily: Plus Jakarta Sans
    fontSize: 56px
    fontWeight: '800'
    lineHeight: 64px
  display-hero-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '800'
    lineHeight: 44px
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
  headline-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
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
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 10px
    fontWeight: '700'
    lineHeight: 14px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 2.5rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system establishes a high-tier aquatic narrative tailored for a premier urban diving academy. It balances deep-sea tranquility, safety-critical professionalism, and the adrenaline of open-water exploration. The interface captures the sensation of descending through sunlit crystal shallows into the profound, quiet calm of the abyss.

### Design Style: Hydro-Luminescent Glassmorphism
The aesthetic combines deep oceanic canvases with frosted, light-refracting surfaces, bioluminescent cyan halos, and vivid high-visibility safety accents. 

- **Atmosphere:** Dark, layered, tranquil yet energetic; evokes immersion, buoyancy, and precision.
- **Visual Mechanics:** Semi-translucent containers, specular edge reflections, underwater caustic glows, and streamlined pill and soft-rounded controls.
- **Safety Metaphor:** High-contrast coral elements function like dive-line markers and emergency ascent floats—demanding instant action against dark waters.

## Colors

The palette simulates the light spectrum penetrating water: deep absorption in the foundation, vivid luminescence in interactive elements, and high-visibility coral for conversion points.

### Palette Architecture
- **Primary (`#00B4D8` - Sunlit Cyan):** Represents the surface layer breaking into light. Used for primary branding, active indicators, interactive links, and glow effects.
- **Secondary (`#FF6B4A` - Coral Reef Orange):** High-energy safety color. Reserved strictly for primary Call-to-Action (CTA) elements, urgent alerts, booking buttons, and conversion badges.
- **Tertiary (`#06D6A0` - Lagoon Mint):** Secondary interactive triggers, certification indicators, validation states, and specialty badge highlights.
- **Neutral Abyss (`#0A192F` - Deep Ocean Navy):** Base dark canvas. Tonal surface elevations are derived by layering lighter, translucent navy tints (`#0D2040`, `#112E56`) over this root tone.

### Surface Color Roles
- **Canvas Base:** `#0A192F`
- **Surface Elevation 1 (Card Base):** `rgba(13, 32, 64, 0.70)`
- **Surface Elevation 2 (Hover / Flyout):** `rgba(17, 46, 86, 0.85)`
- **Surface Outline / Specular Edge:** `rgba(72, 202, 228, 0.20)`
- **Text High-Contrast:** `#F0F9FF`
- **Text Muted / Sub-ocean:** `#94A3B8`

## Typography

Typography pairs **Plus Jakarta Sans** for expressive, modern headlines and micro-labels with **Inter** for neutral, hyper-legible technical content (gear descriptions, depth limits, medical checks).

- Headings use negative letter-spacing (`-0.02em` on `display-hero` through `headline-lg`) to maintain a clean, solid presence against dark backgrounds.
- Micro-labels, certification flags, and depth statistics use uppercase casing with generous tracking (`0.05em` to `0.08em`) to mimic dive computer readouts.
- Line heights in body copy are set generously (`1.5` to `1.6`) to provide maximum scanning comfort against high-contrast deep backgrounds.

## Layout & Spacing

The layout model uses a fluid 12-column grid anchored by responsive outer boundaries to simulate expansive oceanic breathing room.

### Form Factors & Breakpoints
- **Mobile (< 768px):** 4-column layout. Margin: `1.25rem` (`margin-mobile`), Gutter: `1rem` (`gutter-mobile`). All cards, schedules, and instructor grids collapse into single-column flows or horizontal scroll carousels.
- **Tablet (768px – 1024px):** 8-column layout. Margin: `2rem`, Gutter: `1.5rem`. Course cards reflow into 2-column matrices.
- **Desktop (> 1024px):** 12-column layout. Maximum content bounding container of `1280px`. Margin: `2.5rem` (`margin`), Gutter: `1.5rem` (`gutter`). Supports complex course path matrices and multi-panel equipment tables.

### Rhythm Rules
- Component internals employ a strict 8px step system (`space-sm` = 8px, `space-md` = 16px, `space-lg` = 24px).
- Sections maintain a deep-sea separation of `space-xl` multiplied by 2 to 3 times to establish distinct narrative depths between course catalogs, pool training specs, and safety certifications.

## Elevation & Depth

Visual hierarchy uses frosted glassmorphism, subtle caustic backdrops, and bioluminescent rim lighting.

### Surface Tiers
- **Tier 0 (Abyss Floor):** Solid `#0A192F` canvas, accented occasionally by smooth radial gradients (`radial-gradient(circle at 50% 0%, #0D2040 0%, #0A192F 75%)`).
- **Tier 1 (Submerged Panels - Cards, Tables):** `rgba(13, 32, 64, 0.65)` backdrop with `backdrop-filter: blur(16px)` and a 1px border colored `rgba(72, 202, 228, 0.15)`.
- **Tier 2 (Floating Controls - Hover states, Dropdowns):** `rgba(17, 46, 86, 0.85)` with `backdrop-filter: blur(24px)` and a 1px specular highlight on the top edge using `rgba(255, 255, 255, 0.25)`.
- **Tier 3 (Modals, Sticky Navigation, Overlays):** `rgba(10, 25, 47, 0.90)` with `backdrop-filter: blur(32px)` and full bounding border `rgba(0, 180, 216, 0.35)`.

### Ambient Glows & Lighting
- **Cyan Hydro-Glow:** `box-shadow: 0 8px 32px -4px rgba(0, 180, 216, 0.25)` applied to primary active elements and highlighted course cards.
- **Coral Beacon Glow:** `box-shadow: 0 4px 20px 0 rgba(255, 107, 74, 0.40)` applied strictly to primary CTA buttons to guarantee instantaneous visual focus.

## Shapes

The interface embraces a streamlined, hydrodynamic form language reflecting maritime equipment, mask lenses, and fluid water dynamics.

- **Standard Containers (`roundedness: 2` = 0.5rem / 8px):** Applied to form fields, nested micro-cards, and data badges.
- **Structural Cards (`rounded-lg` = 1rem / 16px):** Course modules, instructor biographies, pool technical cards, and glass panels.
- **Feature Modals & Hero Tiles (`rounded-xl` = 1.5rem / 24px):** Major thematic sections and image containers.
- **Action Elements & Badges (`rounded-full`):** All buttons, PADI/CMAS badges, level pills, and filter chips feature full rounded pill contours for a buoyant, tactile aesthetic.

## Components

### Buttons
- **Primary CTA (Ascent/Book):** Pill-shaped (`rounded-full`), solid `#FF6B4A` background, pure white text (`#FFFFFF`), `font-weight: 700`. Hover state triggers a subtle scale shift (`scale(1.02)`) and intensifies the coral glow (`box-shadow: 0 6px 24px rgba(255, 107, 74, 0.50)`).
- **Secondary (Course Overview):** Glass pill (`rgba(0, 180, 216, 0.10)`), 1px solid border (`#00B4D8`), text in `#00B4D8`. On hover: solid `#00B4D8` with `#0A192F` dark navy typography.
- **Tertiary (Text/Ghost):** Transparent background with cyan underline animation expanding from center on hover.

### Badges & Certifications (PADI / CMAS)
- **Certification Badges:** Rigid pill shape with a dark translucent core (`rgba(10, 25, 47, 0.8)`), 1px perimeter ring colored according to affiliation (`#00B4D8` for PADI, `#06D6A0` for CMAS). Includes official insignia icon + tracking-wide uppercase typography (`label-sm`).
- **Difficulty/Depth Pills:** Subdued blue-gray tint with an integrated icon (e.g., diving mask or anchor) indicating minimum depth requirements (e.g., "18M • OWD").

### Cards (Course & Expedition Panels)
- Surface: Glassmorphic Tier 1 (`rgba(13, 32, 64, 0.65)` background, `backdrop-filter: blur(16px)`).
- Border: `1px solid rgba(72, 202, 228, 0.15)`.
- Internal Layout: Image banner with underwater depth mask at top, followed by `space-md` interior padding, certification pill over header, and primary CTA placed flush at the base.
- Hover Interaction: Card shifts `translateY(-4px)` with border color shifting to `#00B4D8` and an ambient cyan glow surfacing underneath.

### Chips & Filters
- Inactive: Pill shape, `rgba(255, 255, 255, 0.05)` fill, `1px solid rgba(255, 255, 255, 0.12)`, text `#94A3B8`.
- Active: Filled `#00B4D8`, text `#0A192F`, `font-weight: 600`, accompanied by a subtle water-ripple ring animation on click.

### Form Inputs & Selectors
- Background: `rgba(10, 25, 47, 0.60)`.
- Border: `1px solid rgba(72, 202, 228, 0.25)`, radius `0.5rem`.
- Focus State: Border transitions to `#00B4D8`, box shadow `0 0 0 3px rgba(0, 180, 216, 0.20)`, background clears to `rgba(13, 32, 64, 0.90)`.
- Labels: `label-md` anchored above with subtle cyan tinting on focus.

### Checkboxes & Radio Controls
- Radio / Checkbox Base: Custom styled geometric ring with `rgba(0, 180, 216, 0.30)` stroke and transparent fill.
- Checked State: Solid `#00B4D8` fill with pure white aquatic tick or center bubble dot, surrounded by an ambient cyan halo.

### Specialized Component: Water Depth & Condition Gauge
- An interactive vertical slider or visual telemetry readout widget indicating pool training temperature (e.g., "31°C"), dive depth ladder (5m to 45m), and visibility metrics, featuring glass surfaces and teal tick marks.