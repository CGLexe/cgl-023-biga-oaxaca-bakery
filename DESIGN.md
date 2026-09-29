---
name: Biga Oaxaca Neo-Neapolitan
colors:
  surface: '#fdf9f0'
  surface-dim: '#dddad1'
  surface-bright: '#fdf9f0'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f7f3ea'
  surface-container: '#f1ede5'
  surface-container-high: '#ece8df'
  surface-container-highest: '#e6e2d9'
  on-surface: '#1c1c16'
  on-surface-variant: '#59413e'
  inverse-surface: '#31302b'
  inverse-on-surface: '#f4f0e7'
  outline: '#8d706d'
  outline-variant: '#e1bfbb'
  surface-tint: '#b02d28'
  primary: '#6a0005'
  on-primary: '#ffffff'
  primary-container: '#8f1414'
  on-primary-container: '#ff9b91'
  inverse-primary: '#ffb4ab'
  secondary: '#bb0203'
  on-secondary: '#ffffff'
  secondary-container: '#e0291d'
  on-secondary-container: '#fffbff'
  tertiary: '#4e2700'
  on-tertiary: '#ffffff'
  tertiary-container: '#6f3a00'
  on-tertiary-container: '#ffa04b'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad6'
  primary-fixed-dim: '#ffb4ab'
  on-primary-fixed: '#410002'
  on-primary-fixed-variant: '#8e1313'
  secondary-fixed: '#ffdad5'
  secondary-fixed-dim: '#ffb4a8'
  on-secondary-fixed: '#410000'
  on-secondary-fixed-variant: '#930001'
  tertiary-fixed: '#ffdcc3'
  tertiary-fixed-dim: '#ffb77d'
  on-tertiary-fixed: '#2f1500'
  on-tertiary-fixed-variant: '#6e3900'
  background: '#fdf9f0'
  on-background: '#1c1c16'
  surface-variant: '#e6e2d9'
typography:
  headline-hero:
    fontFamily: Bebas Neue
    fontSize: 80px
    fontWeight: '400'
    lineHeight: 80px
    letterSpacing: 0.04em
  headline-hero-mobile:
    fontFamily: Bebas Neue
    fontSize: 48px
    fontWeight: '400'
    lineHeight: 50px
    letterSpacing: 0.03em
  headline-lg:
    fontFamily: Bebas Neue
    fontSize: 48px
    fontWeight: '400'
    lineHeight: 52px
    letterSpacing: 0.04em
  headline-lg-mobile:
    fontFamily: Bebas Neue
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 36px
    letterSpacing: 0.03em
  headline-md:
    fontFamily: Bebas Neue
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 36px
    letterSpacing: 0.03em
  headline-sm:
    fontFamily: Space Grotesk
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  title-md:
    fontFamily: Space Grotesk
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Space Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
    letterSpacing: 0em
  body-md:
    fontFamily: Space Grotesk
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
    letterSpacing: 0em
  body-sm:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-lg:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.06em
  label-md:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.08em
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 9px
    fontWeight: '500'
    lineHeight: 12px
    letterSpacing: 0.1em
spacing:
  gutter: 1.25rem
  gutter-desktop: 2rem
  margin: 1rem
  margin-tablet: 2rem
  margin-desktop: 3.5rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.75rem
  space-xl: 3rem
---

## Brand & Style

This design system expresses the raw, artisanal precision of modern Neapolitan dough-craft grounded in the cultural epicenter of Oaxaca Centro. The visual tone bridges rustic fermentation science and sharp contemporary bistro culture—minimalist and editorial, with brutalist structural discipline and tactile, warm culinary intimacy.

The UI avoids nostalgic clichés (no faux chalkboards, generic checkered prints, or cartoonish rustic illustrations). Instead, it mirrors high-end dining journals, natural wine rosters, and bespoke architecture: generous flour-canvas negative space, confident structural division lines, unapologetic condensed display typography, and punchy neon-warm culinary highlights. The interface evokes late-evening wood smoke, raw unbleached stone, terracotta-stained lime wash walls, and blistering, charred crusts.

## Colors

The palette is anchored by the physical palette of the pizzeria space in Oaxaca: deep fermented terracotta, bright San Marzano pomodoro red, candlelight amber, raw stone, and charred oak.

- **Primary (`#8F1414`)**: Deep fermented crimson/terracotta. Used for primary interaction surfaces, authoritative headers, key brand anchors, and strong structural boundaries.
- **Secondary (`#D92318`)**: Vibrant Italian tomato red. Used for urgent interactive callouts, active state indicators, sold-out strikes, and high-impact badges.
- **Tertiary (`#FF9A3C`)**: Candlelight/neon amber. Used for ambient warmth, special natural wine badges, seasonal fermentation callouts, and subtle hover halos.
- **Neutral Palette**:
  - `canvas`: `#FBF9F4` (Warm unbleached flour / paper canvas)
  - `surface`: `#F3EFE6` (Ecru dough stage)
  - `surface-elevated`: `#EAE4D7` (Raw limestone table surface)
  - `border-subtle`: `#DCD4C4` (Muted boundary tone)
  - `border-strong`: `#181414` (Deep ink architectural lines)
- **Ink & Dark Accents**:
  - `ink-primary`: `#181414` (Espresso blister / wood-fired char)
  - `ink-secondary`: `#524843` (Cacao & charred flour tone)
  - `ink-tertiary`: `#8C817A` (Muted stone gray)

Color rules:
- Dark mode inversion is strictly reserved for late-night menu modes or bar view overlays (`#181414` canvas with `#F3EFE6` typography and `#FF9A3C` active accents).
- High structural contrast must be preserved: text sits directly on unbleached warm neutrals or sits reversed in pure `#FBF9F4` against deep crimson blocks.

## Typography

The typographic hierarchy juxtaposes monumental architectural condensed display forms (`Bebas Neue`) against technical grotesque body copy (`Space Grotesk`) and archival culinary specs rendered in monospace (`JetBrains Mono`).

- **Bebas Neue**: Used strictly in uppercase for section heads, large menu titles, bill totals, and hero statements. It commands space like physical metal signage or classic print posters.
- **Space Grotesk**: Brings utilitarian warmth to pizza descriptions, ingredients, background notes, and guest communication. Its idiosyncratic geometry gives editorial edge without sacrificing readability.
- **JetBrains Mono**: Used in uppercase for prices, batch numbers, fermentation timing (e.g. `48H BIGA / 72% HYDRATION`), origin certificates (e.g. `OAXACA CENTRO`), and allergen chips.

## Layout & Spacing

The layout is built upon an architectural grid inspired by modular print layouts and structural concrete framework:

- **Desktop (1024px and up)**: 12-column layout with fixed outer margins of `3.5rem` and gutters of `2rem`. Two-column split layouts dominate—one side fixed with editorial imagery or dominant typography, the other side handling menu lists or reservations.
- **Tablet (768px - 1023px)**: 8-column layout with `2rem` margins and `1.25rem` gutters.
- **Mobile (below 768px)**: 4-column layout with tight `1rem` margins and `1rem` gutters.

Spacing Rhythm:
- Vertical rhythm enforces dramatic tension: generous whitespace around category titles (`space-xl`), balanced by tight, compact technical line groupings (`space-xs` and `space-sm`) for ingredient breakdowns and price markers.
- Layout items use clear hairline boundary separations instead of excessive loose padding to retain the tactile bistro-ticket atmosphere.

## Elevation & Depth

This design system avoids soft, floating diffused dropshadows. Visual depth is tactile, grounded, and physical:

- **Structural Outlines & Low-Contrast Borders**: Layers are delineated through crisp 1px solid structural rules (`#DCD4C4` on light surfaces; `#181414` for focal items).
- **Tonal Stepping**: Depth is conveyed through color stacking:
  - Base level: `canvas` (`#FBF9F4`)
  - Intermediate cards & trays: `surface` (`#F3EFE6`)
  - Active drawers & popovers: `surface-elevated` (`#EAE4D7`) or solid deep crimson (`#8F1414`) with white typography.
- **Hard Cast Shadows (Brutalist Depth)**: Modals, active floating order receipts, and floating action buttons utilize flat, unblurred offset drop-shadows:
  - Spec: `box-shadow: 4px 4px 0px 0px #181414;`
- **Backdrop Overlays**: Modals and slide-over reservation drawers sit over a high-opacity wash of `#181414` at 65% opacity, paired with an immediate dark edge contrast.

## Shapes

The shape system is strictly sharp (`roundedness: 0`). Elements have 0px border-radius, reflecting architectural stone blocks, raw pizza boxes, printed paper tabs, and brutalist restaurant counters.

- Buttons, cards, popups, inputs, and image containers maintain razor-sharp right angles.
- Badges and chips maintain hard rectangular perimeters with clean border trims.
- Circular geometry is exclusively reserved for authentic circular artifacts: round stamp badges (e.g. "FERMENTADO EN OAXACA"), wine pairing circles, or circular thumbnail avatars for culinary team profiles.

## Components

### Buttons
- **Primary**: Solid background `#8F1414` (Deep Crimson), text `#FBF9F4` in `JetBrains Mono` bold uppercase (`label-lg`), border 1px solid `#8F1414`. On hover, background shifts to `#D92318` (Bright Tomato) with a `2px 2px 0px #181414` hard shadow.
- **Secondary / Outline**: Background transparent, text `#181414`, border 1px solid `#181414`. On hover, fills solid `#181414` with `#FBF9F4` text.
- **Tertiary / Utility**: Monospaced underline action with no border, text `#8F1414`, accompanied by an arrow glyph (`→`).

### Chips & Badges
- **Status / Dietary Badge**: Rectangular boxes with 1px border.
  - Spicy / Fermented: `#D92318` text, `#F3EFE6` background, border `#D92318`.
  - Natural Wine / Chef Special: `#181414` text, `#FF9A3C` background, border `#181414`.
  - Typography: `label-sm` uppercase.

### Menu List & Cards
- **Menu Items**: Borderless top-to-bottom layout with a clean dotted or hairline border divider (`1px solid #DCD4C4`). Left-aligned pizza name in `headline-sm` or `title-md`, right-aligned monospaced price in `label-lg` (`$280 MXN`). Ingredient list sits directly below in `body-md` muted ink.
- **Bistro Order Cards**: Surface `#F3EFE6`, framed in 1px solid `#181414`. Header shows the table or order number in uppercase `Bebas Neue`, followed by monospaced itemized breakdown.

### Form Inputs & Selectors
- **Text Inputs**: Crisp bottom-only or fully enclosed 1px borders in `#181414`. Canvas background `#FBF9F4`. Text in `Space Grotesk`. Floating or top-placed labels in `JetBrains Mono` uppercase (`label-md`). Focus state produces an inner or outer hairline accent in `#8F1414` without fuzzy outline rings.
- **Checkboxes & Radios**: 0px border-radius squares. Selected state for checkboxes displays a solid `#8F1414` fill with a sharp white checkmark. Radio buttons display an interior solid square block rather than a soft dot.

### Specialized Culinary Components
- **Fermentation Tracker / Dough Spec**: Horizontal ticker or metric pill showing technical stats (`HYDRATION: 70%` | `FERMENTATION: 48H` | `FLOUR: CAPUTO TIPO 00 + MAÍZ CRIOLLO NATIVO`).
- **Table Reservation Slot**: Segmented time grid with sharp square blocks. Available: `#FBF9F4` with `#181414` border; Selected: solid `#8F1414` with `#FBF9F4` text; Booked/Unavailable: diagonal hatched line overlay with muted text.
- **Ticket Stub Toast**: Floating system notifications styled as a clipped printed kitchen ticket with a hard drop shadow (`4px 4px 0px #181414`).