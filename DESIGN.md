---
name: Aura & Bean
colors:
  surface: '#fcf9f3'
  surface-dim: '#dcdad4'
  surface-bright: '#fcf9f3'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3ed'
  surface-container: '#f0eee8'
  surface-container-high: '#ebe8e2'
  surface-container-highest: '#e5e2dc'
  on-surface: '#1c1c18'
  on-surface-variant: '#4b4640'
  inverse-surface: '#31312d'
  inverse-on-surface: '#f3f0ea'
  outline: '#7d766f'
  outline-variant: '#cec5bd'
  surface-tint: '#615e5b'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1d1b19'
  on-primary-container: '#878380'
  inverse-primary: '#cbc5c2'
  secondary: '#97472e'
  on-secondary: '#ffffff'
  secondary-container: '#fe997a'
  on-secondary-container: '#772f18'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#101f08'
  on-tertiary-container: '#778969'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e7e1de'
  primary-fixed-dim: '#cbc5c2'
  on-primary-fixed: '#1d1b19'
  on-primary-fixed-variant: '#494644'
  secondary-fixed: '#ffdbd0'
  secondary-fixed-dim: '#ffb59f'
  on-secondary-fixed: '#3a0a00'
  on-secondary-fixed-variant: '#793019'
  tertiary-fixed: '#d5e9c3'
  tertiary-fixed-dim: '#b9cda8'
  on-tertiary-fixed: '#101f08'
  on-tertiary-fixed-variant: '#3b4c2f'
  background: '#fcf9f3'
  on-background: '#1c1c18'
  surface-variant: '#e5e2dc'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 56px
    fontWeight: '600'
    lineHeight: 64px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 38px
    fontWeight: '600'
    lineHeight: 46px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '500'
    lineHeight: 48px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '500'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '500'
    lineHeight: 36px
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 30px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.02em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.04em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.06em
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
The design system channels an elevated ritual: the quiet, sensory luxury of third-wave specialty coffee. Its core personality is artisanal, calm, deliberate, and warm. Designed for discerning coffee enthusiasts, specialty roasters, and mindful urban consumers, the interface rejects fast-paced digital clutter in favor of an immersive, editorial ambiance reminiscent of a curated architectural cafe.

The visual direction merges **Warm Editorial Minimalism** with delicate **Tactile Atmosphere**. Generous margins, intentional typographic contrast, and restrained interactions replicate the measured pace of manual brewing. Every element emphasizes clarity, heritage craft, and human touch, avoiding sterile tech tropes in favor of soft, natural warmth.

## Colors
The palette evokes natural coffee cultivation and brewing: roasted beans, unbleached linen, sun-baked clay, and fresh coffee cherries.

- **Primary (`#1A1816` - Deep Espresso):** Anchors typographic hierarchy, high-priority interactive states, and foundational layout structure.
- **Neutral Background (`#F9F6F0` - Warm Linen Cream):** Replaces clinical stark white with a tactile, soft canvas that reduces glare and elevates depth.
- **Secondary Accent (`#C86D51` - Terracotta / Rust):** Denotes focal calls-to-action, origin highlights, roast profiles, and celebratory badges.
- **Tertiary Accent (`#879A78` - Muted Sage):** Signifies organic certifications, processing methods, harvest details, and successful system feedback.
- **Surface Elevation (`#FFFFFF` - Crisp Milk White):** Reserved for elevated interactive cards, dropdown menus, and modular dialogs to create deliberate contrast against the linen canvas.
- **Subtle Outline (`#E7E1D6` - Warm Taupe):** Defines structural container edges and separators without introducing sharp or harsh lines.

## Typography
Typographic rhythm balances the editorial authority of high-contrast display serif forms with the ergonomic, modern utility of geometric grotesque letterforms.

- **Headlines & Titles:** Set in `Playfair Display`. The optical elegance and refined serifs convey craftsmanship, vintage apothecary labels, and editorial menus. Use italics sparingly for sensory tasting notes or regional descriptors.
- **Body & Functional UI:** Set in `Plus Jakarta Sans`. Its open apertures and subtle geometric curves provide high legibility for product descriptions, brewing guides, and transaction checkout flows.
- **Labels & Micro-copy:** Formatted with modest letter spacing (`0.02em` to `0.06em`) and medium/semibold weights to ensure readability on bag labels, sensory attribute tags, and navigation bars.

## Layout & Spacing
The layout follows an asymmetrical 12-column responsive fluid grid designed to display imagery and text with magazine-grade pacing.

- **Breakpoints & Grids:**
  - **Desktop (≥1200px):** 12 columns, `gutter: 1.5rem` (24px), `margin: 2.5rem` (40px) or centered within a `max-width: 1360px` canvas.
  - **Tablet (768px - 1199px):** 8 columns, `gutter: 1.25rem` (20px), `margin: 2rem` (32px).
  - **Mobile (<768px):** 4 columns, `gutter: 1rem` (16px), `margin: 1.25rem` (20px).
- **Rhythm & Whitespace:** Generous vertical rhythm separates narrative storytelling sections with `space-xl` (40px) to double-interval tokens (80px), ensuring items feel museum-spaced rather than cramped.

## Elevation & Depth
Depth is expressed through subtle atmospheric layers rather than sharp, heavy drop shadows:

1. **Frosted Glassmorphism (Headers & Sticky Controls):** Fixed navigation bars and contextual control docks utilize `background: rgba(249, 246, 240, 0.82)` with `backdrop-filter: blur(16px)` and a bottom border of `rgba(231, 225, 214, 0.6)`. This maintains continuity as users scroll over deep visual media.
2. **Ambient Tonal Shadows:** Floating product cards and modal dialogs rely on diffused, warm-tinted shadows:
   - *Subtle Card Rest:* `0 4px 20px -2px rgba(26, 24, 22, 0.04), 0 1px 3px 0 rgba(26, 24, 22, 0.02)`
   - *Interactive Hover:* `0 12px 32px -4px rgba(26, 24, 22, 0.08), 0 2px 6px 0 rgba(26, 24, 22, 0.03)`
   - *Flyout / Drawer / Modal:* `0 24px 48px -8px rgba(26, 24, 22, 0.12), 0 4px 12px 0 rgba(26, 24, 22, 0.04)`
3. **Warm Border Delimitation:** Surfaces are bound by a 1px soft border in `#E7E1D6`, preventing cards from relying solely on shadow contrast for edge detection.

## Shapes
The design system employs a soft, sculpted structural language (`roundedness: 2` base):

- **Buttons & Small Chips:** `0.5rem` to `0.75rem` (8px–12px) for structured action targets, or organic pills (`9999px`) for filter pills and brewing parameter tags.
- **Product Cards & Content Containers:** Strictly `0.75rem` to `1rem` (12px–16px) corner radiuses, reflecting the smooth, tactile form of ceramic cups and polished stone surfaces.
- **Modals, Sheets & Image Wrappers:** `1rem` to `1.5rem` (16px–24px) for expansive visual blocks and immersive overlays.

## Components

- **Buttons:**
  - *Primary:* Espresso fill (`#1A1816`), warm cream text (`#F9F6F0`), 12px border radius, subtle hover elevation shift, and 200ms ease transition.
  - *Secondary / Accent:* Terracotta fill (`#C86D51`) or stroke outline (`1.5px solid #C86D51`), crisp white text or terracotta text. Used for conversion triggers ("Add to Cart", "Subscribe & Save").
  - *Tertiary / Ghost:* Transparent background with `#1A1816` text and an underline transition that slides in from the left on hover.

- **Chips & Attribute Tags:**
  - Used for flavor notes (e.g., "Bergamot", "Stone Fruit"), roast levels, and processing methods (Washed, Natural, Anaerobic).
  - Built with pill-shaped contours, delicate borders (`#E7E1D6`), soft backgrounds (`#FFFFFF` or `#F0ECE1`), and `label-sm` or `label-md` typography.
  - Sage green accent chips (`#879A78` background at 12% tint with solid sage text) for organic and direct-trade markers.

- **Product & Origin Cards:**
  - Set against pure white `#FFFFFF` or elevated cream `#F3EFE7` with 12px–16px radiuses and 1px `#E7E1D6` border.
  - Generous internal padding (`space-lg`), high-fidelity vertical photography with a 4:5 aspect ratio, clear price placement in `label-lg`, and tasting notes stacked as clean metadata rows.

- **Input Fields & Selectors:**
  - Form containers with 10px–12px radiuses, `#FFFFFF` fill, 1px `#E7E1D6` default border.
  - Active focus transitions to a 1.5px border in Espresso (`#1A1816`) with an outer subtle halo (`rgba(200, 109, 81, 0.15)`). Placeholder text set in warm muted taupe.

- **Checkboxes & Radio Controls:**
  - Rounded custom controls with an Espresso fill and white micro-check when selected. Unselected state features a 1.5px `#D5CEC2` border on warm white.

- **Sensory Tasting Radar & Roast Sliders:**
  - Custom artisanal components: minimalist slider tracks using 4px warm taupe rails with smooth terracotta thumb indicators, paired with typographic indicators along the scale (Light, Medium-Light, Omni, Dark).