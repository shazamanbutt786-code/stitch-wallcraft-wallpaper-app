---
name: Breeze Dark
colors:
  surface: '#111319'
  surface-dim: '#111319'
  surface-bright: '#373940'
  surface-container-lowest: '#0c0e14'
  surface-container-low: '#191b22'
  surface-container: '#1d1f26'
  surface-container-high: '#282a30'
  surface-container-highest: '#33353b'
  on-surface: '#e2e2ea'
  on-surface-variant: '#cac4d6'
  inverse-surface: '#e2e2ea'
  inverse-on-surface: '#2e3037'
  outline: '#938e9f'
  outline-variant: '#484554'
  surface-tint: '#ccbeff'
  primary: '#ccbeff'
  on-primary: '#350097'
  primary-container: '#987bff'
  on-primary-container: '#2e0085'
  inverse-primary: '#6543ce'
  secondary: '#5de6ff'
  on-secondary: '#00363e'
  secondary-container: '#00cbe6'
  on-secondary-container: '#00515d'
  tertiary: '#40dfae'
  on-tertiary: '#003828'
  tertiary-container: '#00a47d'
  on-tertiary-container: '#003123'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e7deff'
  primary-fixed-dim: '#ccbeff'
  on-primary-fixed: '#1f0060'
  on-primary-fixed-variant: '#4c25b5'
  secondary-fixed: '#a2eeff'
  secondary-fixed-dim: '#2fd9f4'
  on-secondary-fixed: '#001f25'
  on-secondary-fixed-variant: '#004e5a'
  tertiary-fixed: '#64fcc9'
  tertiary-fixed-dim: '#40dfae'
  on-tertiary-fixed: '#002116'
  on-tertiary-fixed-variant: '#00513c'
  background: '#111319'
  on-background: '#e2e2ea'
  surface-variant: '#33353b'
typography:
  display:
    fontFamily: Space Grotesk
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.03em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Space Grotesk
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 34px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Space Grotesk
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
    fontFamily: Space Grotesk
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.02em
  label-md:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.03em
  label-sm:
    fontFamily: Space Grotesk
    fontSize: 10px
    fontWeight: '600'
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
  gutter: 0.75rem
  gutter-tablet: 1rem
  margin: 1rem
  margin-tablet: 1.5rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.25rem
---

## Brand & Style

This design system establishes an atmospheric, hyper-refined dark aesthetic engineered specifically for high-density OLED visual exploration. Designed for a premier wallpaper and visual curation platform, the UI acts as a calibrated gallery frame: unobtrusive when showcasing edge-to-edge artwork, yet vibrantly responsive and tactically precise during navigation and customization.

The visual style merges modern minimalism with subtle dark-field luminance. Deep, velvety midnight backdrops minimize battery draw while providing maximum perceptual contrast for imagery. High-energy neon accents in violet and electric cyan introduce luminescence without visual clutter, directing focus to critical actions, active tags, and live wallpaper controls. The aesthetic conveys precision engineering, cinematic focus, and premium digital craft.

## Colors

The palette is anchored in an OLED-optimized surface hierarchy paired with high-chroma luminous accents.

- **Background Canvas (`#0b0c10`)**: The foundational deep black base layer used for system level backdrops and edge-bleed wallpaper previews.
- **Surface Layer 1 (`#13151b`)**: Main container cards, bottom navigation trays, and persistent app surfaces.
- **Surface Layer 2 (`#1b1e28`)**: Raised content cards, active panels, search bars, and filter sheets.
- **Surface Layer 3 (`#252936`)**: Hover states, interactive controls, inactive chips, and floating overlays.
- **Primary Accent (`#8b6cf7` / `#7c5cfc`)**: Radiant ultraviolet used for hero CTAs, active segmented toggles, key metrics, and selection rings.
- **Secondary Accent (`#22d3ee`)**: Electric cyan used for live wallpaper badges, download triggers, and refresh cues.
- **Tertiary Accent (`#38d9a9`)**: Hyper-mint reserved for success feedback, pro features, and curated curation tags.
- **Content Primary (`#f8fafc`)**: Crisp, high-readability text for titles and essential actions.
- **Content Secondary (`#94a3b8`)**: Slate mid-tone for metadata, resolution specs, and subtle labeling.
- **Border Subtle (`rgba(255, 255, 255, 0.08)`)**: Precision boundary defining card edges and list item dividers.

## Typography

The typographic pairing balances technical acuity with high legibility. 

`Space Grotesk` is implemented across display headers, screen titles, category badges, and numerical metrics (resolutions, file sizes, aspect ratios). Its geometric terminals and futuristic cuts reflect digital craft and visual curation without sacrificing structure.

`Plus Jakarta Sans` handles all running body copy, descriptions, creator bios, and functional instructional text. Its open apertures and clean curves maintain effortless legibility at compact mobile scale against high-contrast slate surfaces.

## Layout & Spacing

The layout is built for mobile-first media consumption utilizing a dynamic 4-column layout on handheld viewports and an 8-column layout on larger tablets.

- **Mobile Viewport (< 600px)**: 16px (`1rem`) outer canvas margins paired with tight 12px (`0.75rem`) internal column gutters optimize screen real estate for immersive 2-column staggered masonry galleries.
- **Tablet / Large Display (≥ 600px)**: 24px (`1.5rem`) outer canvas margins and 16px (`1rem`) gutters expanding the grid into 3 or 4 display columns.
- **Vertical Rhythm**: Spacing scales strictly in 4px/8px multiples. Component gaps rely heavily on `space-xs` and `space-sm` for inline metadata clusters, while vertical card separation relies on `space-md` to preserve thumbnail density.

## Elevation & Depth

Visual hierarchy operates through disciplined surface tonal stepping accented by ultra-subtle neon luminance rather than conventional daylight drop shadows.

- **Level 0 (Canvas Base)**: Deep `#0b0c10` void. Flat, non-reflective.
- **Level 1 (Docked Surfaces & Cards)**: `#13151b` surface surrounded by a 1px ghost border of `rgba(255, 255, 255, 0.06)`.
- **Level 2 (Active Sheets & Modals)**: `#1b1e28` surface with a crisp border of `rgba(255, 255, 255, 0.10)` and an ambient downward soft shadow (`0 12px 32px rgba(0, 0, 0, 0.65)`).
- **Level 3 (Focused & Interactive Controls)**: `#252936` enhanced with a subtle radiant halo. Primary elements feature an edge glow (`0 0 16px rgba(139, 108, 247, 0.25)`), while live wallpaper tags feature a secondary cyan pulse (`0 0 12px rgba(34, 211, 238, 0.20)`).

## Shapes

The shape system adopts a refined, ergonomic curvature (`Level 2: Rounded`). Outer corners of primary media cards and bottom modal sheets utilize `rounded-xl` (1.5rem) to echo the physical hardware contours of modern smartphones.

Standard interactive buttons, input containers, and setting blocks use `rounded-lg` (1rem). Compact meta tags, resolution badges, and status pills employ fully circular pill radii (9999px) to maintain distinct visual semantics from content cards.

## Components

### Buttons
- **Primary Action (e.g., "Set Wallpaper", "Download 4K")**: Solid `#8b6cf7` fill, high-contrast dark text (`#0b0c10`) or pure white (`#ffffff`) at bold weight, subtle outer violet bloom (`0 4px 20px rgba(139, 108, 247, 0.35)`).
- **Secondary Action (e.g., "Favorite", "Share")**: Translucent `#1b1e28` fill, 1px border `rgba(255, 255, 255, 0.12)`, text in `#f8fafc`.
- **Ghost/Icon Button**: Transparent background, hovering into `#252936`, icon styled with `#94a3b8` transitioning to `#22d3ee` on active state.

### Chips & Filter Tags
- **Default State**: Surface `#1b1e28`, 1px border `rgba(255, 255, 255, 0.08)`, typography `label-md` in `#94a3b8`.
- **Selected State**: Subtle tinted fill `rgba(139, 108, 247, 0.15)`, high-contrast border `#8b6cf7`, typography in pure white accompanied by a luminous violet dot indicator.

### Wallpaper Thumbnail Cards
- Seamless corner radii (`1.25rem` to `1.5rem`) with an inset 1px inner border (`rgba(255, 255, 255, 0.08)`) to preserve visual separation between high-key wallpaper art and the `#0b0c10` backdrop.
- Embedded floating metadata pill at bottom-left: semi-translucent backdrop blur (`rgba(19, 21, 27, 0.75)` with `backdrop-filter: blur(8px)`), featuring resolution (e.g., `4K`, `OLED`, `LIVE`) in electric cyan `#22d3ee`.

### Form & Search Inputs
- **Search Bar**: Base `#13151b`, border `rgba(255, 255, 255, 0.08)`, `space-md` horizontal padding. Focus state transitions border to `#8b6cf7` with a 2px outer glow (`0 0 0 2px rgba(139, 108, 247, 0.2)`).
- **Checkboxes & Radios**: 20px boxes/circles with `#1b1e28` idle fill and 1.5px border. Checked state morphs to solid `#8b6cf7` fill with a crisp white check glyph.

### Bottom Navigation Bar
- Frosted floating pill container or anchored bottom sheet tinted `#0b0c10` at 85% opacity with severe backdrop blur (`24px`).
- Active items illuminate with vertical dual-tone emphasis: an electric icon glow and a 4px wide rounded indicator bar anchored below the item.