---
name: Panther in the Tulip Reverie
colors:
  surface: '#131315'
  surface-dim: '#131315'
  surface-bright: '#39393b'
  surface-container-lowest: '#0e0e10'
  surface-container-low: '#1c1b1d'
  surface-container: '#201f21'
  surface-container-high: '#2a2a2c'
  surface-container-highest: '#353437'
  on-surface: '#e5e1e4'
  on-surface-variant: '#d1c3cb'
  inverse-surface: '#e5e1e4'
  inverse-on-surface: '#313032'
  outline: '#998d95'
  outline-variant: '#4e444a'
  surface-tint: '#e7b8dd'
  primary: '#e7b8dd'
  on-primary: '#462541'
  primary-container: '#b388aa'
  on-primary-container: '#43223f'
  inverse-primary: '#785271'
  secondary: '#e4b5ff'
  on-secondary: '#451e5d'
  secondary-container: '#5f3878'
  on-secondary-container: '#d6a7f0'
  tertiary: '#bfc9c3'
  on-tertiary: '#29322e'
  tertiary-container: '#8e9892'
  on-tertiary-container: '#27302c'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffd7f4'
  primary-fixed-dim: '#e7b8dd'
  on-primary-fixed: '#2e102b'
  on-primary-fixed-variant: '#5e3b59'
  secondary-fixed: '#f4d9ff'
  secondary-fixed-dim: '#e4b5ff'
  on-secondary-fixed: '#2e0447'
  on-secondary-fixed-variant: '#5d3676'
  tertiary-fixed: '#dbe5de'
  tertiary-fixed-dim: '#bfc9c3'
  on-tertiary-fixed: '#151d1a'
  on-tertiary-fixed-variant: '#3f4944'
  background: '#131315'
  on-background: '#e5e1e4'
  surface-variant: '#353437'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 56px
    fontWeight: '400'
    lineHeight: 64px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 36px
    fontWeight: '400'
    lineHeight: 44px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '500'
    lineHeight: 40px
  headline-md:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
  title-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: 0.01em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.08em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 10px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.12em
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
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system translates the visual dichotomy of the majestic black panther resting amidst an endless twilight meadow of silken pink tulips and satin bows into an immersive, museum-grade digital exhibition. The emotional atmosphere evokes silent reverence, surreal romance, dark luxury, and dreamlike contemplation.

The design movement combines **Painterly Dark-Luxe Editorial** with **Atmospheric Glassmorphism**. UI elements do not shout; they levitate delicately over obsidian depths like museum gallery placards, illuminated by the diffuse mauve and twilight lilac glow of dusk. The interface serves as a quiet frame for the visual poetry, maintaining pristine restraint, measured spatial breathing room, and luminous micro-interactions.

## Colors

The palette directly honors the reference painting:

- **Primary (`#b388aa`)**: Dusky twilight mauve, reflecting the diffuse petal light and the pale evening sky. Serves as the primary brand touchstone, focal interactive accents, and soft highlights.
- **Secondary (`#7b5294`)**: Silk violet ribbon tone. Used for active states, deep ambient glows, key markers, and tonal progress indicators.
- **Tertiary (`#1f2824`)**: Deep emerald-shadow foliage. Employed in subtle backdrop gradients, deep accents, and naturalistic grounding elements.
- **Neutral (`#0a0a0c`)**: Nocturnal velvet obsidian, mirrored from the sleek fur of the panther and nightfall. Forms the bedrock surface and foundation layers.
- **Surface & Shading Tones**: Tiers range from `#141218` (Surface Container Low) to `#1e1924` (Surface Elevated). Text uses pearlescent off-white (`#f4effa`) down to muted dusk mauve (`#9d93a8`) for secondary descriptions.

## Typography

The typographic hierarchy pairs the high-contrast elegance of **Playfair Display** with the clear, contemporary legibility of **Plus Jakarta Sans**.

- **Display & Headlines (`Playfair Display`)**: Conveys the romantic, cinematic weight of fine art curatorial titles. Italics may be selectively applied to single words or narrative chapters to heighten the poetic rhythm.
- **Body & Subtitles (`Plus Jakarta Sans`)**: Delivers effortless reading for curatorial prose, artwork background, and sensory descriptions with generous line heights.
- **Labels & Overlays (`Plus Jakarta Sans`)**: Tracked out (`0.08em` to `0.12em`) in all-caps or medium weights to echo luxury exhibition wayfinding, audio chapter timers, and spatial camera controls without intruding on the central artwork.

## Layout & Spacing

The layout philosophy centers on **Unobtrusive Framing and Fluid Grids**:

- **Grid Architecture**: A 12-column fluid grid on desktop (`>1024px`) with `3rem` margins and `1.5rem` gutters. Tablet (`768px - 1023px`) transitions to an 8-column format with `2rem` margins. Mobile (`<768px`) scales to a 4-column structure with `1.25rem` margins.
- **Negative Space**: Spacing emphasizes contemplative stillness. Outer boundaries allow the focal imagery to breathe, while UI toolbars and curatorial side panels hug safe zones with translucent padding.
- **Rhythm**: UI clusters use tight intra-component spacing (`space-xs` and `space-sm`) surrounded by generous contextual breathing space (`space-lg` to `space-xl`) to establish distinct focal islands.

## Elevation & Depth

Visual hierarchy is maintained through subtle **translucent dark glass** and **luminous violet-mauve ambient rim light** rather than harsh mechanical drop shadows:

- **Level 0 (Canvas Base)**: Pure `#0a0a0c` velvet obsidian, serving as the backdrop for full-bleed visuals and canvas viewports.
- **Level 1 (Subsurface Panels & Cards)**: Nocturnal glass composed of `#141218` at 70% opacity with a `16px` backdrop blur (`backdrop-filter: blur(16px)`) and a delicate `1px` border of `rgba(179, 136, 170, 0.15)`.
- **Level 2 (Active Overlays, Modals, Camera HUDs)**: `#1e1924` at 85% opacity, `24px` backdrop blur, a hairline border of `rgba(226, 154, 185, 0.28)`, and an ambient shadow: `0 12px 36px -6px rgba(10, 10, 12, 0.7), 0 0 20px 0 rgba(123, 82, 148, 0.15)`.
- **Level 3 (Tooltips & Popovers)**: `#251e2d` with sharp contrast, hairline silver-lilac borders (`rgba(244, 239, 250, 0.2)`), and an evocative purple-tinted halo.

## Shapes

With a roundedness token of `2`, the shape language embodies a balanced, approachable elegance:

- Standard elements (buttons, text inputs, segmented pills, badge tags) adopt an exact `0.5rem` (`8px`) border radius.
- Cards, modal containers, and floating HUD viewports scale harmoniously to `rounded-lg` (`1rem` / `16px`) or `rounded-xl` (`1.5rem` / `24px`).
- Circular treatments are reserved strictly for circular controls like camera waypoint nodes, audio scrub heads, and miniature media avatars.

## Components

### Buttons
- **Primary**: Twilight mauve background (`#b388aa`) with deep obsidian text (`#0a0a0c`), styled in medium `Plus Jakarta Sans`. On hover, transitions smoothly to luminous rose (`#e29ab9`) with an ambient lilac bloom (`box-shadow: 0 0 16px rgba(179, 136, 170, 0.35)`). Radius: `0.5rem`.
- **Secondary (Ghost Glass)**: Translucent background (`rgba(30, 25, 36, 0.6)`) with a hairline mauve outline (`rgba(179, 136, 170, 0.3)`) and pearlescent text (`#f4effa`). Hover elevates the outline to `rgba(226, 154, 185, 0.7)`.
- **Minimal / Icon Button**: Seamless transparent background, pearlescent icon, expanding into a subtle soft purple circular wash on hover.

### Chips & Badges
- Compact tags formatted in uppercase `label-sm` with `0.12em` letter spacing.
- Subdued obsidian background (`rgba(20, 18, 24, 0.8)`) with a `1px` border tinted in secondary violet (`rgba(123, 82, 148, 0.4)`). Active filters turn into soft twilight mauve fills with obsidian text.

### Cards & Curatorial Dossiers
- Framed in frosted velvet obsidian (`rgba(20, 18, 24, 0.75)` with `16px` blur) and bounded by a `1px` gradient border shifting from `rgba(179, 136, 170, 0.25)` at the top edge to `rgba(31, 40, 36, 0.1)` at the base.
- Generous internal padding (`space-lg`) paired with `Playfair Display` section headers and `Plus Jakarta Sans` descriptions.

### Lists & Chapter Selectors
- Dividers are drawn with whispered opacity (`rgba(179, 136, 170, 0.1)`).
- List rows feature interactive hover states that illuminate a subtle linear gradient fading in from the left edge (`linear-gradient(90deg, rgba(123, 82, 148, 0.15), transparent)`).

### Input Fields & Search
- Low-profile inputs using `#141218` background, `0.5rem` corners, and neutral-muted placeholder typography.
- Active focus invokes a gentle lilac border (`#b388aa`) paired with a discreet `0 0 0 3px rgba(179, 136, 170, 0.2)` glow ring.

### Checkboxes & Radios
- Box/Circle borders in `rgba(179, 136, 170, 0.4)`. When checked, filled with vibrant twilight mauve (`#b388aa`) displaying a velvet obsidian checkmark or inner core, accompanied by a soft violet focus ring.

### Curatorial Experience Controls (Specialized)
- **Camera Stop Waypoint**: Circular nodes with central obsidian core, haloed by double pulsing rings of twilight lilac (`#b388aa`).
- **Audio Reverie Player**: Horizontal minimalist timeline with a needle-thin track in muted dusk violet and a pearlescent scrubber head that expands gently on hover.