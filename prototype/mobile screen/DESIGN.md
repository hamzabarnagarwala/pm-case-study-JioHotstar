---
name: Electric Aurora Entertainment
colors:
  surface: '#0f1321'
  surface-dim: '#0f1321'
  surface-bright: '#353948'
  surface-container-lowest: '#090e1c'
  surface-container-low: '#171b2a'
  surface-container: '#1b1f2e'
  surface-container-high: '#252939'
  surface-container-highest: '#303444'
  on-surface: '#dfe1f6'
  on-surface-variant: '#bcc9ce'
  inverse-surface: '#dfe1f6'
  inverse-on-surface: '#2c303f'
  outline: '#869398'
  outline-variant: '#3d494d'
  surface-tint: '#4cd6fb'
  primary: '#4cd6fb'
  on-primary: '#003642'
  primary-container: '#00b4d8'
  on-primary-container: '#00414f'
  inverse-primary: '#00677d'
  secondary: '#fbabff'
  on-secondary: '#580065'
  secondary-container: '#ae05c6'
  on-secondary-container: '#ffd8fd'
  tertiary: '#adc6ff'
  on-tertiary: '#002e6a'
  tertiary-container: '#76a4ff'
  on-tertiary-container: '#00387e'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#b3ebff'
  primary-fixed-dim: '#4cd6fb'
  on-primary-fixed: '#001f27'
  on-primary-fixed-variant: '#004e5f'
  secondary-fixed: '#ffd6fd'
  secondary-fixed-dim: '#fbabff'
  on-secondary-fixed: '#36003e'
  on-secondary-fixed-variant: '#7c008e'
  tertiary-fixed: '#d8e2ff'
  tertiary-fixed-dim: '#adc6ff'
  on-tertiary-fixed: '#001a42'
  on-tertiary-fixed-variant: '#004395'
  background: '#0f1321'
  on-background: '#dfe1f6'
  surface-variant: '#303444'
typography:
  display-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 56px
    fontWeight: '800'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '800'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 22px
    fontWeight: '700'
    lineHeight: 28px
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 10px
    fontWeight: '700'
    lineHeight: 12px
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  margin: 2rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system is tailored for an immersive, premium, next-generation entertainment and streaming platform. The brand personality is electric, magnetic, expansive, and high-energy. Designed to serve hundreds of millions of viewers across sports, cinema, global drama, and live spectacles, the interface evokes the anticipation of a live arena combined with the cinematic depth of modern high-fidelity screens.

The visual style blends **Modern Glassmorphism** with **High-Contrast Digital Luminescence**:
- Deep midnight indigo and abyssal navy canvases (#050814, #0a0f24) allow content artwork to pop without distraction.
- Fluid, multi-stop energetic aura gradients transitioning seamlessly from electric cyan to royal cobalt and neon magenta/fuchsia provide focal cues, hero backdrops, and active-state highlights.
- Semi-translucent glass panels with micro-borders and soft ambient chromatic glows create depth, preserving an uninterrupted cinematic stream.

## Colors

The palette is engineered around dark mode cinematic excellence, balancing sharp luminance against low-reflective deep space backdrops.

- **Primary (`#00b4d8` - Electric Cyan):** Used for primary focal actions, live badges, progress indicators, and interactive highlights.
- **Secondary (`#d946ef` - Neon Fuchsia / Magenta):** Used for premium badges, VIP markers, energetic secondary calls to action, and interactive hover shifts.
- **Tertiary (`#3b82f6` - Royal Cobalt):** Bridges cyan and fuchsia in continuous gradient fills, hero badges, and subdued interactive states.
- **Neutral Dark Canvas (`#050814` to `#0a0f24`):** The primary canvas background, creating deep blacks that maximize dynamic range on OLED and HDR screens.
- **Surface Overlays & Cards:** Low-opacity layers (`rgba(15, 23, 42, 0.65)` to `rgba(255, 255, 255, 0.05)`) with subtle 1px luminous edge borders.
- **Text & Foreground:** Pure crisp white (`#ffffff`) for headline titles and key actions; cool silver (`#94a3b8`) for secondary metadata and inactive controls.

## Typography

The typography leverages **Plus Jakarta Sans** across all levels, mirroring the geometric precision, warmth, and modern clarity seen in the wordmark. 

- **Display & Headlines:** Set in bold and extrabold weights with tight tracking (`-0.02em` to `-0.03em`) to project strong cinematic presence on large hero carousels and TV interfaces.
- **Body:** Neutral, humanist geometry with open apertures to sustain high legibility against dark translucent surfaces and video backdrops.
- **Labels & Badges:** Upper-case or high-weight medium/small styles with slightly expanded tracking for content metadata, video resolutions (4K, UHD, HDR), audio standards, and match stats.

## Layout & Spacing

The layout model is optimized for content consumption across mobile handhelds, tablets, desktops, and living room television screens.

- **Grid Architecture:** 12-column fluid responsive grid on desktop with 24px gutters and 32px safe margins; 8 columns on tablet with 16px gutters; 4 columns on mobile with 16px margins.
- **Aspect Ratio Locking:** Media thumbnails adhere strictly to 16:9 (horizontal landscape), 2:3 (vertical movie poster), or 1:1 (channel and sports team avatars).
- **Carousel & Rails:** Horizontal scroll rails allow edge-to-edge content overflow with smooth gradient masks at container edges.
- **Breakpoints:**
  - Mobile: `< 640px` (stacked rows, full-width hero, bottom navigation bar).
  - Tablet: `640px – 1024px` (multi-column media rails, compact sidebar).
  - Desktop / TV: `> 1024px` (expanded media tiles, fixed persistent left navigation rail, expanded hero billboard with background video backdrop).

## Elevation & Depth

Visual hierarchy relies on light, diffusion, and chromatic luminescence rather than heavy opaque drop shadows:

- **Surface Tiers:**
  - *Base:* Deepest canvas `#050814`.
  - *Layer 1 (Card & Rail Containers):* Semi-opaque obsidian `rgba(10, 15, 36, 0.7)` with `backdrop-filter: blur(16px)` and a subtle `1px` top border highlight of `rgba(255, 255, 255, 0.08)`.
  - *Layer 2 (Floating Modals, Flyouts, Trays):* `rgba(15, 23, 42, 0.85)` with `backdrop-filter: blur(24px)`.
- **Chromatic Aura Shadows:**
  - Active elements and hero focus cards emit a radial blur glow: `0 8px 32px rgba(0, 180, 216, 0.25)` or `0 8px 32px rgba(217, 70, 239, 0.25)`.
- **Specular Highlights:** Interactive elements feature an ultra-fine 1px inset highlight simulating chrome light catch on edges, inspired by the polished platinum shooting star mark.

## Shapes

The design uses balanced, modern rounded contours (`roundedness: 2` — base radius of 8px / 0.5rem) to pair geometric confidence with approachable soft-touch usability.

- **Content Posters & Tiles:** Base radius `0.5rem` (8px) for crisp imagery; large media cards scale up to `rounded-lg` (16px / 1rem).
- **Controls & Buttons:** Interactive pills and play controls use soft 8px to fully pill-rounded (`rounded-full`) geometry for fluid touch targets.
- **Badges & Tags:** Tight 4px (`rounded-sm`) to 6px radii to keep live sports scores and video tag indicators compact and distinct from media content.

## Components

### Buttons
- **Primary Play / Action:** Gradient fill transitioning at 135° from `#00b4d8` through `#3b82f6` to `#d946ef`, with bold white typography, 12px vertical by 28px horizontal padding, and a smooth ambient glow on hover (`0 0 20px rgba(0, 180, 216, 0.4)`).
- **Secondary Watchlist / Info:** Frosted glass surface (`rgba(255, 255, 255, 0.08)`), 1px solid `rgba(255, 255, 255, 0.15)` border, text in `#ffffff`.
- **Icon Buttons:** Circular 44px frosted glass discs with centered SVG icons in white or electric cyan.

### Chips & Category Filters
- Compact horizontal pills with `0.5rem` to `rounded-full` styling. Inactive chips use translucent obsidian backgrounds (`rgba(255, 255, 255, 0.05)`) with silver text. Selected chips illuminate with solid cyan or a cyan-to-magenta subtle gradient border.

### Media Cards & Content Rails
- Feature 16:9 or 2:3 content art with a subtle dark gradient vignette at the bottom for title legibility.
- On hover/focus, cards scale smoothly (1.05x), reveal a metallic platinum or electric cyan border glow, and expose inline quick-actions (Play, Add to List, Audio toggle).

### Progress & Live Indicators
- **Video Scrubbers:** Track background `rgba(255, 255, 255, 0.2)` with a filled gradient bar (`#00b4d8` to `#d946ef`) and a gleaming circular thumb indicator.
- **Live Tag:** Pill badge in vibrant hot magenta (`#d946ef`) with pulsing white dot animation and bold uppercase label.

### Inputs & Search Fields
- Dark field container `rgba(255, 255, 255, 0.06)` with rounded 12px corners, placeholder text in `#64748b`, and an active state that transitions the border to `#00b4d8` with a soft cyan focus ring.