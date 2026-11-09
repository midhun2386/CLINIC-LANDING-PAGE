---
name: Porcelain & Azure Precision
colors:
  surface: '#f7f9fb'
  surface-dim: '#d8dadc'
  surface-bright: '#f7f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f6'
  surface-container: '#eceef0'
  surface-container-high: '#e6e8ea'
  surface-container-highest: '#e0e3e5'
  on-surface: '#191c1e'
  on-surface-variant: '#3f4850'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#707881'
  outline-variant: '#bfc7d2'
  surface-tint: '#006398'
  primary: '#006194'
  on-primary: '#ffffff'
  primary-container: '#007bb9'
  on-primary-container: '#fdfcff'
  inverse-primary: '#93ccff'
  secondary: '#525f75'
  on-secondary: '#ffffff'
  secondary-container: '#d6e3fe'
  on-secondary-container: '#58657b'
  tertiary: '#006387'
  on-tertiary: '#ffffff'
  tertiary-container: '#007da9'
  on-tertiary-container: '#fcfcff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#cce5ff'
  primary-fixed-dim: '#93ccff'
  on-primary-fixed: '#001d31'
  on-primary-fixed-variant: '#004b73'
  secondary-fixed: '#d6e3fe'
  secondary-fixed-dim: '#bac7e1'
  on-secondary-fixed: '#0e1c2f'
  on-secondary-fixed-variant: '#3a475c'
  tertiary-fixed: '#c4e7ff'
  tertiary-fixed-dim: '#7bd0ff'
  on-tertiary-fixed: '#001e2c'
  on-tertiary-fixed-variant: '#004c69'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  display-hero:
    fontFamily: Plus Jakarta Sans
    fontSize: 4.5rem
    fontWeight: '700'
    lineHeight: '1.08'
    letterSpacing: -0.035em
  display-hero-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 2.75rem
    fontWeight: '700'
    lineHeight: '1.12'
    letterSpacing: -0.025em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 3rem
    fontWeight: '600'
    lineHeight: '1.15'
    letterSpacing: -0.03em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 2rem
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 2rem
    fontWeight: '600'
    lineHeight: '1.25'
    letterSpacing: -0.02em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.375rem
    fontWeight: '600'
    lineHeight: '1.35'
    letterSpacing: -0.015em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.125rem
    fontWeight: '400'
    lineHeight: '1.65'
    letterSpacing: -0.005em
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 1rem
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: 0em
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.875rem
    fontWeight: '400'
    lineHeight: '1.5'
    letterSpacing: 0.005em
  label-caps:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.75rem
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: 0.14em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.875rem
    fontWeight: '600'
    lineHeight: '1.25'
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.75rem
    fontWeight: '500'
    lineHeight: '1.2'
    letterSpacing: 0.02em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-desktop: 2.5rem
  margin: 1.25rem
  margin-tablet: 2.5rem
  margin-desktop: 5rem
  space-xs: 0.375rem
  space-sm: 0.75rem
  space-md: 1.25rem
  space-lg: 2rem
  space-xl: 3.5rem
---

## Brand & Style

This design system establishes an ultra-premium, cinematic aesthetic for luxury cosmetic and restorative dentistry. It balances clinical precision with bespoke hospitality, removing clinical intimidation and replacing it with serene luxury, architectural restraint, and immaculate clarity.

The visual direction merges **Minimalism** with refined **Glassmorphism**:
- Generous pristine negative space evoking sterilized, architectural environments.
- Translucent frosted glass layers with subtle, high-clarity refraction.
- Sharp contrasts between luminous enamel tones and deep oceanic navy surfaces.
- Micro-interactions characterized by deliberate, gliding ease and subtle optical glows.

## Colors

The color system draws inspiration from dental enamel, crystalline water, and midnight architectural interiors:

- **Primary (`#0284C7`)**: Azure Blue. Signifies precision laser technology, medical authority, and clarity. Used for primary CTAs, active states, and focused interaction rings.
- **Secondary (`#0B192C`)**: Medical Midnight Navy. Anchors deep editorial typography, cinematic dark-mode structural containers, footer monoliths, and high-contrast headlines.
- **Tertiary (`#38BDF8`)**: Radiant Cyan / Electric Enamel. Applied as radiant luminescence, focused micro-glows, badges, and gradient accents over navy backdrops.
- **Neutral (`#F8FAFC`)**: Crisp Ice White canvas. Serves as the primary surface baseline, accompanied by pristine porcelain white (`#FFFFFF`) for elevated cards and platinum gray (`#E2E8F0`) for hair-thin structural dividers.

Inverted surfaces leverage `#0B192C` as the background with `#0284C7` and `#38BDF8` luminescent atmospheric gradients (`radial-gradient(ellipse at top, rgba(56, 189, 248, 0.12), transparent 70%)`).

## Typography

The type system uses **Plus Jakarta Sans** uniformly to establish geometric refinement, surgical clarity, and modern warmth. 

- **Display & Headlines**: Tightly tracked (`-0.02em` to `-0.035em`) with crisp optical balance. Used to frame procedural outcomes and architectural dentistry statements.
- **Eyebrow & Badging Labels**: Always rendered in `label-caps` with extreme tracking (`0.14em`) and uppercase transformation to evoke luxury surgical labeling.
- **Body Text**: Tuned for maximum legibility with expansive line-heights (`1.6`–`1.65`) to maintain an open, non-taxing reading rhythm.

## Layout & Spacing

A 12-column fluid grid system with structural maximum containment at `1440px`. The spacing philosophy emphasizes horizontal calm and wide vertical breathing room:

- **Desktop (≥ 1024px)**: 12 columns, `2.5rem` gutters, `5rem` page margins. Section padding scales between `6rem` and `10rem` vertically to frame clinic imagery cinematographically.
- **Tablet (768px – 1023px)**: 8 columns, `1.5rem` gutters, `2.5rem` margins. Complex diagnostic comparison tables compress to dual-column swipe layouts.
- **Mobile (< 768px)**: 4 columns, `1rem` gutters, `1.25rem` margins. Stacks vertically with generous element gaps (`space-lg`) to prevent density.

## Elevation & Depth

Visual depth is achieved through optical clarity, translucency, and soft azure-diffused lighting:

- **Level 1 (Subtle Glass Floor)**: Surface `rgba(255, 255, 255, 0.75)` with `backdrop-filter: blur(16px)`, enclosed by a `1px` border of `rgba(255, 255, 255, 0.9)` and ambient shadow `0 8px 32px -8px rgba(11, 25, 44, 0.04)`.
- **Level 2 (Active Surgical Elevation)**: Surface `#FFFFFF` with `backdrop-filter: blur(24px)`, bounded by a `1px` border of `rgba(2, 132, 197, 0.12)`, casting an ambient diffuse shadow `0 16px 40px -12px rgba(2, 132, 197, 0.08), 0 2px 6px 0 rgba(11, 25, 44, 0.03)`.
- **Level 3 (Dark Atmospheric Monolith)**: Deep backdrop `#0B192C` featuring a soft interior radial bloom of `rgba(56, 189, 248, 0.07)`, a subtle rim border of `rgba(255, 255, 255, 0.08)`, and a dramatic deep elevation shadow `0 24px 64px -16px rgba(11, 25, 44, 0.35)`.
- **Level 4 (Floating Modals & Diagnostic Drawers)**: Pure white `#FFFFFF` layered over an ultra-deep backdrop scrim (`rgba(11, 25, 44, 0.6)` with `backdrop-filter: blur(8px)`), supported by `0 32px 72px -20px rgba(11, 25, 44, 0.18)`.

## Shapes

The design system employs a refined geometric curvature that balances organic tooth contouring with architectural precision:

- **Base Radius (`0.5rem`)**: Used for input controls, interactive tags, and micro-badges.
- **Card Radius (`1rem`)**: Applied to standard content cards, appointment panels, and diagnostic modules.
- **Feature Radius (`1.5rem`)**: Reserved for large hero visual containers, video showreels, and full-section glass enclosures.
- **Full Radius (`9999px`)**: Exclusively reserved for primary action pills, floating appointment booking bar controls, and status pills.

## Components

### Buttons
- **Primary Action Pill**: Gradient fill `linear-gradient(135deg, #0284C7 0%, #0369A1 100%)`, text `#FFFFFF`, fully rounded (`9999px`), padding `0.875rem 2rem`. Subtle glow shadow on hover: `0 8px 24px -4px rgba(2, 132, 197, 0.35)`.
- **Secondary Glass Action**: Backdrop blur surface `rgba(255, 255, 255, 0.8)`, border `1px solid rgba(226, 232, 240, 0.8)`, text `#0B192C`. Hover initiates a light azure rim tint (`#38BDF8`) and background transition to pure `#FFFFFF`.
- **Dark Monolith Action**: Used on navy containers. Transparent background with a `1px` border of `rgba(56, 189, 248, 0.4)`, text `#FFFFFF`, transition to cyan glow on hover.

### Badges & Medical Tags
- Compact indicators using `label-caps`. 
- Frosted ice background `rgba(56, 189, 248, 0.08)`, text `#0284C7`, hairline border `1px solid rgba(56, 189, 248, 0.25)`.
- Active operational badges incorporate a pulsating live indicator dot (`#38BDF8`).

### Cards & Service Tiles
- **Glass Service Tile**: Frosted white background `rgba(255, 255, 255, 0.85)`, `1px` platinum border, `1rem` corner radius, internal padding `2rem`.
- Features an icon container rendered in soft radiant cyan (`rgba(2, 132, 197, 0.06)` with an azure icon).
- Interactive hover: Subtle vertical translation (`-4px`) and activation of a `1px` cyan border flare.

### Before / After Diagnostic Slider
- Bespoke dual-image comparison element framed in `1.5rem` radius with a central hairline slider divider in `#FFFFFF`.
- Central dragging handle: Frosted glass sphere with double directional arrows in `#0284C7` and an ambient glow.

### Form Inputs & Selectors
- Background `#FFFFFF` with border `1px solid #E2E8F0`, corner radius `0.5rem`, padding `0.875rem 1.25rem`.
- Typography: `body-md` in `#0B192C`, placeholder in `#94A3B8`.
- Focus state: Border transitions to `#0284C7` with a non-blurring micro outer halo `0 0 0 3px rgba(56, 189, 248, 0.2)`.

### Checkboxes & Segmented Controls
- Checkbox uses custom `0.25rem` curved squares with a `1px solid #CBD5E1` border; active states fill with `#0284C7` containing a pristine white check mark.
- Segmented procedural duration switches utilize pill containers in `#F1F5F9` with an elevated porcelain white slider pill.