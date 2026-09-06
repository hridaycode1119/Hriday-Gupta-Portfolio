---
name: Modern Editorial Minimalist
colors:
  surface: '#f9f9f9'
  surface-dim: '#dadada'
  surface-bright: '#f9f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f3'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1a1c1c'
  on-surface-variant: '#444748'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f0f1f1'
  outline: '#747878'
  outline-variant: '#c4c7c7'
  surface-tint: '#5f5e5e'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1c1b1b'
  on-primary-container: '#858383'
  inverse-primary: '#c8c6c5'
  secondary: '#5e5e5e'
  on-secondary: '#ffffff'
  secondary-container: '#e1dfdf'
  on-secondary-container: '#626262'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#002109'
  on-tertiary-container: '#009844'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e5e2e1'
  primary-fixed-dim: '#c8c6c5'
  on-primary-fixed: '#1c1b1b'
  on-primary-fixed-variant: '#474646'
  secondary-fixed: '#e4e2e2'
  secondary-fixed-dim: '#c7c6c6'
  on-secondary-fixed: '#1b1c1c'
  on-secondary-fixed-variant: '#464747'
  tertiary-fixed: '#6bff8f'
  tertiary-fixed-dim: '#4ae176'
  on-tertiary-fixed: '#002109'
  on-tertiary-fixed-variant: '#005321'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
typography:
  display-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 112px
    fontWeight: '800'
    lineHeight: 104px
    letterSpacing: -0.04em
  display-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 52px
    fontWeight: '800'
    lineHeight: 54px
    letterSpacing: -0.03em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.03em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 38px
    letterSpacing: -0.02em
  statement-lead:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 48px
    letterSpacing: -0.02em
  statement-lead-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 30px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 22px
  label-mono:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.08em
  nav-link:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 18px
    letterSpacing: -0.01em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  space-2xs: 0.25rem
  space-xs: 0.5rem
  space-sm: 0.75rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
  space-2xl: 4rem
  space-3xl: 6rem
  space-4xl: 10rem
  gutter: 1.5rem
  margin-mobile: 1.25rem
  margin-desktop: 3rem
---

## Brand & Style

This design system expresses an ultra-minimalist, gallery-grade digital presence tailored for elite designers, creative engineers, and architectural studios. Its aesthetic draws from contemporary Swiss typography, brutalist clarity, and high-fashion editorial portfolios. 

The mood is confident, quiet, and hyper-curated. By stripping away extraneous ornamentation, the system places total focus on massive typographic scale, structured grids, nuanced micro-interactions, and immaculate spatial composition. Subtle radial lighting blurs and frosted elements introduce physical depth without cluttering the canvas.

## Colors

The palette is monochromatic and deliberate, designed to let visual artifacts and project imagery take precedence:

- **Primary (`#111111`)**: Deep graphite black for display typography, primary call-to-actions, and structural borders.
- **Secondary (`#666666`)**: Muted charcoal gray reserved for supporting metadata, bracketed notations (`[Web]`), and sub-headers.
- **Tertiary (`#22C55E`)**: Emerald green pulse indicator explicitly indicating live availability and "OPEN TO WORK" status badges.
- **Neutral Canvas (`#FAFAFA`)**: An ultra-clean warm off-white, paired with pure white (`#FFFFFF`) card surfaces and crisp divider rules (`#E5E5E5`).
- **Atmospheric Glows**: Semi-transparent radial accents (`rgba(0, 0, 0, 0.03)` to `rgba(0, 0, 0, 0.06)`) centered behind focal headline blocks to provide soft visual texture.

## Typography

Typography functions as the primary visual architecture:

- **Plus Jakarta Sans** delivers clean geometric curves with tight kerning. Giant display titles (`display-xl`) use uppercase styling with heavy negative tracking (`-0.04em`) to establish an unmistakable monumentality.
- **Space Grotesk** serves as a utilitarian counter-voice for micro-meta tags, technical labels, bracketed filters, and status indicators.
- Lead editorial statements utilize enclosed bracket conventions (e.g. `[A product-focused Designer...]`) to nod toward programmatic and editorial design aesthetics.

## Layout & Spacing

The layout adopts a high-density vertical cadence balanced by wide horizontal breathing room:

- **Grid Architecture**: 12-column layout maxing out at `1440px` centered within a fluid wrapper. Breakpoints occur at `768px` (tablet) and `1024px` (desktop).
- **Hero & Headline Anchoring**: Primary display titles consume 100% width across the top tier, bounded above and below by hair-thin horizontal borders (`1px solid #E5E5E5`).
- **Metadata Triad**: Directly under primary display headers, desktop displays split sub-metadata across 3 anchored columns: Left (Discipline/Role), Center (Location), Right (Availability/Global reach). On mobile viewports, these collapse into a clean vertical stack spaced by `space-xs`.
- **Card Framing**: Showcase project cards maintain generous aspect-ratio framing, utilizing internal padding of `space-2xl` to float inner product viewport snapshots.

## Elevation & Depth

Visual hierarchy is maintained primarily via stark contrast and subtle atmospheric diffusion rather than heavy physical drop shadows:

- **Level 0 (Base)**: Flat canvas surface (`#FAFAFA`) with single-pixel perimeter structural outlines (`#E5E5E5`).
- **Level 1 (Cards & Canvases)**: `#FFFFFF` or pale neutral-toned container frames with soft, multi-stop ambient diffusion: `0 12px 32px -4px rgba(0, 0, 0, 0.04), 0 4px 12px -2px rgba(0, 0, 0, 0.02)`.
- **Level 2 (Floating Micro-Controls & Frosted Pills)**: Translucent white overlays (`rgba(255, 255, 255, 0.85)`) coupled with `backdrop-filter: blur(12px)` and a whisper border (`1px solid rgba(0, 0, 0, 0.06)`).
- **Ambient Radial Backlight**: Subtle background depth driven by soft radial gradients (`radial-gradient(circle at 50% 50%, rgba(0, 0, 0, 0.035) 0%, transparent 70%)`), grounding centered copy blocks.

## Shapes

The geometric identity balances hard editorial lines with rounded, modern hardware corners:

- **Outer Frames & Cards**: Medium border radii (`rounded-lg`, `1rem` to `1.5rem`) reflecting modern high-resolution device screens.
- **Pills & Status Badges**: Fully pill-shaped (`rounded-full` / `9999px`) used for status tags, platform flags, and contextual chips.
- **Structural Dividers**: Crisp, non-rounded `1px` lines spanning column or page widths to anchor structural groupings.

## Components

### Micro Badges & Availability Pill
- **Open To Work Indicator**: Pill-shaped container (`rgba(0, 0, 0, 0.04)` fill, `1px solid #E5E5E5` border, `py-1.5 px-3.5`). Features an active pulse dot: a `6px` circular green (`#22C55E`) indicator accompanied by Space Grotesk `label-mono` text styled in uppercase.
- **Category Filter Chips**: Inline links formatted as bracketed strings (e.g. `ALL`, `[Web]`, `[Design]`). Inactive states use `#666666`, transitioning to `#111111` with an underline or bold weight on active selection.

### Action Links & Typography Anchors
- **Editorial Hyperlink**: Text underlined with a subtle offset (`underline-offset-4`) accompanied by an upward diagonal arrow icon (`↗` or `lucide:arrow-up-right`).
- **Nav Items**: Horizontal flat text list without containers, styled with `nav-link` tokens, spaced evenly across the top navigation bar.

### Showcase Cards
- **Structure**: Outer framed presentation vessel (`#EBEBEB` or `#FFFFFF`) with rounded corners (`1.5rem`), housing an inner elevated product mockup.
- **Overlay Floating Badges**: Frosted glass badges (`rgba(255, 255, 255, 0.7)` backdrop blur) placed in the lower corner of the preview frame, displaying project title, device icons, and quick-link triggers.

### Buttons & Inputs
- **Text Action Buttons**: Minimalist text buttons styled in bold uppercase with subtle border bottoms on hover.
- **Ghost Form Inputs**: Clean transparent backgrounds, single bottom or full hair-line borders (`1px solid #E5E5E5`), transitioning to `#111111` upon focus with zero glow outlines.