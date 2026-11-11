---
name: Luminous Pulse
colors:
  surface: '#0f131e'
  surface-dim: '#0f131e'
  surface-bright: '#353946'
  surface-container-lowest: '#0a0e19'
  surface-container-low: '#171b27'
  surface-container: '#1b1f2b'
  surface-container-high: '#262a36'
  surface-container-highest: '#303441'
  on-surface: '#dfe2f2'
  on-surface-variant: '#c1c6d7'
  inverse-surface: '#dfe2f2'
  inverse-on-surface: '#2c303c'
  outline: '#8b90a0'
  outline-variant: '#414755'
  surface-tint: '#aec6ff'
  primary: '#aec6ff'
  on-primary: '#002e6a'
  primary-container: '#4e8eff'
  on-primary-container: '#00275d'
  inverse-primary: '#005ac3'
  secondary: '#d2bbff'
  on-secondary: '#3f008e'
  secondary-container: '#6001d1'
  on-secondary-container: '#c9aeff'
  tertiary: '#ffb0cd'
  on-tertiary: '#640039'
  tertiary-container: '#f751a1'
  on-tertiary-container: '#570032'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#d8e2ff'
  primary-fixed-dim: '#aec6ff'
  on-primary-fixed: '#001a42'
  on-primary-fixed-variant: '#004395'
  secondary-fixed: '#eaddff'
  secondary-fixed-dim: '#d2bbff'
  on-secondary-fixed: '#25005a'
  on-secondary-fixed-variant: '#5a00c6'
  tertiary-fixed: '#ffd9e4'
  tertiary-fixed-dim: '#ffb0cd'
  on-tertiary-fixed: '#3e0022'
  on-tertiary-fixed-variant: '#8c0053'
  background: '#0f131e'
  on-background: '#dfe2f2'
  surface-variant: '#303441'
typography:
  display-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 56px
    fontWeight: '800'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 44px
    fontWeight: '800'
    lineHeight: 52px
    letterSpacing: -0.02em
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
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
    letterSpacing: 0.04em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 10px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.08em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 0.75rem
  margin: 3rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system establishes an immersive, cinematic OTT entertainment experience centered around energy, forward momentum, and visual spectacle. Built for massive audiences consuming premium live sports, blockbuster cinema, and episodic drama, the visual language balances deep theater darkness with vivid chromatic energy.

The aesthetic fuses modern high-contrast digital interfaces with subtle glassmorphic luminosity. Deep obsidian and twilight canvas backdrops allow key brand elements—dynamic cyan-to-fuchsia spectral gradients, faceted metallic emblems, and edge-lit glows—to command attention without distracting from video content. Interactions are fluid, magnetic, and responsive, evoking the excitement of live broadcasting and the polished refinement of luxury digital media.

## Colors

The color architecture is built strictly for dark-mode immersion, rooted in the signature brand gradient transitioning diagonally from bright cyan (`#00A8FF` / `#0077FE`) through electric violet (`#7C3AED`) to hot magenta (`#EC4899`). 

### Core Palette Application
- **Canvas & Backdrops:** Obsidian dark canvas (`#070B16`), surface tier-1 (`#0B1120`), and floating panel tier-2 (`#0F172A`).
- **Signature Gradient:** Applied to prominent promotional cards, key CTAs, live sport match score badges, progress indicators, and interactive focus states. A 135-degree linear gradient from `#0077FE` through `#7C3AED` to `#EC4899`.
- **Text & Foreground:** Pure crisp white (`#FFFFFF`) for primary titles and active navigation, silver mist (`#94A3B8`) for secondary metadata and timestamps, and slate shadow (`#475569`) for disabled or tertiary states.
- **Accents & Badges:** Electric magenta (`#EC4899`) is prioritized for "LIVE" tags and urgent notifications; luminous cyan (`#00B4D8`) highlights interactive states and metadata pills (e.g., "4K HDR", "Dolby Atmos").

## Typography

The typography leverages **Plus Jakarta Sans** across all hierarchies to reflect the friendly, modern, geometric character seen in the hero wordmark. 

- **Display & Headline:** Geometric, dense, and confident. Heavy weights (700 and 800) with slight negative tracking command immediate visual authority on hero carousels and cinematic title cards.
- **Body:** Open, clean letterforms engineered for dark backdrops. Standard body copy maintains a minimum opacity of 85% white (`#FFFFFFE0`) to ensure contrast compliance and prevent optical vibration against deep backgrounds.
- **Labels & Badges:** Micro-labels ("LIVE", "SUBSCRIBE", "4K") employ tight uppercase formatting, bold weights, and generous tracking (+0.04em to +0.08em) for crisp legibility at small sizes on television screens and mobile viewports.

## Layout & Spacing

The spatial foundation utilizes an 8pt layout grid within a responsive fluid multi-column architecture tailored for wide media consumption:

- **Desktop & TV (12 Columns):** 48px outer canvas margin, 24px gutters. Media rails feature partial cut-off on trailing cards to encourage continuous horizontal scrolling.
- **Tablet (8 Columns):** 32px outer margin, 16px gutters.
- **Mobile (4 Columns):** 16px outer margin, 12px gutters, with full edge-to-edge video preview stages and compact 16:9 or 2:3 poster layouts.
- **Component Padding:** Standard cards and dialogs maintain generous internal breathing space (`space-md` to `space-lg`), keeping media art uncluttered. Section headers align cleanly with the leftmost content column.

## Elevation & Depth

Visual hierarchy does not rely on traditional drop shadows, but rather on tonal depth, glassmorphic translucency, and vibrant luminous glows:

- **Base Level (Canvas):** `#070B16` solid obsidian background.
- **Layer 1 (Card & Content Containers):** `#0B1120` surface with a subtle 1px border (`rgba(255, 255, 255, 0.08)`).
- **Layer 2 (Overlays, Floating Controls, Navigation Bars):** Frosted glass backdrop blur (`backdrop-filter: blur(20px)`) over a semi-transparent surface (`rgba(11, 17, 32, 0.75)`), bound by a top border highlight (`rgba(255, 255, 255, 0.15)`).
- **Active Focus & Hover Glow:** Active cards, primary play buttons, and keyboard/D-pad navigation states emit an exterior radiant glow: `0px 8px 28px rgba(0, 119, 254, 0.35), 0px 0px 12px rgba(236, 72, 153, 0.25)`.

## Shapes

The design system adopts a balanced rounded visual signature (Level 2).
- Standard UI controls, thumbnails, posters, and input fields use `0.5rem` (8px) border radius.
- Larger modular content panels, modals, and spotlight banners scale to `1rem` (16px) or `1.5rem` (24px).
- Play/Action buttons, status chips, and circular icon triggers opt for fully rounded pills (`9999px`) to create an inviting contrast against rectangular video containers.
- Decorative spark and star motifs mirror the sharp, multi-pointed geometry of the brand emblem, used sparingly as micro-interaction sparks or celebratory moments.

## Components

### Buttons & CTAs
- **Primary CTA ("Watch Now", "Subscribe"):** Pill-shaped with the full cyan-to-magenta signature gradient, white bold text, and a soft ambient glow on hover (`0px 4px 20px rgba(124, 58, 237, 0.4)`).
- **Secondary CTA ("Details", "Add to Watchlist"):** Frosted glass pill with `rgba(255, 255, 255, 0.1)` background, 1px white border (`rgba(255, 255, 255, 0.2)`), and white text. Hover state brightens fill to `rgba(255, 255, 255, 0.2)`.
- **Icon Buttons:** Circular pills (`40px` or `48px`) housing pure white iconography, using blurred dark surfaces for maximum contrast over video backdrops.

### Chips & Metadata Badges
- **Live Badge:** Pill badge filled with solid fuchsia/magenta (`#EC4899`), featuring a pulsing white dot indicator and uppercase `label-sm` bold typography.
- **Spec Chips (4K, HDR, 5.1, Rating):** Pill-shaped with dark translucent backgrounds (`rgba(255, 255, 255, 0.08)`), thin border, and light gray text (`#94A3B8`).

### Content Cards & Media Rails
- **Aspect Ratios:** 16:9 for sports/episodes; 2:3 vertical for movie posters.
- **Default State:** Crisp thumbnail with 8px radius, bottom gradient scrim (`rgba(7, 11, 22, 0) 0%` to `rgba(7, 11, 22, 0.9) 100%`) for metadata legibility.
- **Hover/Focused State:** Smooth 1.05x scale elevation, ambient colored border highlight transitioning from cyan to fuchsia, and automatic video preview playback.

### Form Inputs & Search
- Sleek horizontal inputs with deep slate background (`#0B1120`), border (`rgba(255, 255, 255, 0.12)`), pill or 8px corners, leading search icons in silver (`#94A3B8`), and focus rings illuminated with cyan (`#0077FE`).