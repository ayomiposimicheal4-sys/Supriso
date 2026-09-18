---
name: Lush Celebration
colors:
  surface: '#fbf9f6'
  surface-dim: '#dbdad7'
  surface-bright: '#fbf9f6'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3f0'
  surface-container: '#efeeeb'
  surface-container-high: '#eae8e5'
  surface-container-highest: '#e4e2df'
  on-surface: '#1b1c1a'
  on-surface-variant: '#414945'
  inverse-surface: '#30312f'
  inverse-on-surface: '#f2f0ed'
  outline: '#717975'
  outline-variant: '#c0c8c3'
  surface-tint: '#3b6758'
  primary: '#00241a'
  on-primary: '#ffffff'
  primary-container: '#0c3b2e'
  on-primary-container: '#79a694'
  inverse-primary: '#a2d0be'
  secondary: '#b90a5b'
  on-secondary: '#ffffff'
  secondary-container: '#fe4c8d'
  on-secondary-container: '#590028'
  tertiary: '#19201c'
  on-tertiary: '#ffffff'
  tertiary-container: '#2e3531'
  on-tertiary-container: '#969e98'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#beedd9'
  primary-fixed-dim: '#a2d0be'
  on-primary-fixed: '#002117'
  on-primary-fixed-variant: '#234e40'
  secondary-fixed: '#ffd9e0'
  secondary-fixed-dim: '#ffb1c4'
  on-secondary-fixed: '#3f001a'
  on-secondary-fixed-variant: '#8f0044'
  tertiary-fixed: '#dde4de'
  tertiary-fixed-dim: '#c1c8c3'
  on-tertiary-fixed: '#161d1a'
  on-tertiary-fixed-variant: '#414844'
  background: '#fbf9f6'
  on-background: '#1b1c1a'
  surface-variant: '#e4e2df'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 56px
    fontWeight: '600'
    lineHeight: 64px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 48px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '700'
    lineHeight: 28px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
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
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.04em
  currency-display:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '800'
    lineHeight: 40px
    letterSpacing: -0.02em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-sm: 1rem
  margin: 2rem
  margin-sm: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system channels the warmth of luxury boutique hospitality combined with the spontaneous delight of modern digital gifting. It is crafted for a consumer demographic that values emotional resonance, intentionality, and seamless execution—transforming ordinary milestones into unforgettable celebrations. 

The aesthetic is grounded in a **Tactile Luxury Minimalism** fused with celebratory warmth:
- Generous ivory breathing room prevents visual clutter and evokes premium editorial print.
- Tactile, pillowy surfaces paired with subtle micro-bounce feedback emulate the physical pleasure of untying ribbon and lifting a gift box lid.
- Restraint meets celebration: deep, heritage-grade forest tones anchor institutional reliability and trust, while spirited rose and magenta accents provide vibrant pops of kinetic joy.

## Colors

The palette balances heirloom sophistication with high-spirited celebration:

- **Primary (`#0C3B2E` / Deep Emerald):** Represents heritage, packaging craft, and security. Used for primary branding elements, high-emphasis buttons, key headers, and reassuring trust indicators. A deeper variant (`#08291F`) serves high-contrast states and crisp text on tinted backgrounds.
- **Secondary (`#E6397B` / Celebration Rose):** The spark of delight. Reserved for high-energy accents, notification badges, conversion sparks, celebratory ribbons, unboxing CTAs, and active festive states. An electric variant (`#F43F5E`) handles active/hover interactions.
- **Tertiary (`#E8EFE9` / Muted Sage):** A soft, calming bridge between lush greens and background neutrals. Applied to secondary chips, informational containers, receipt cards, and subtle separators.
- **Neutral (`#FAF8F5` / Warm Ivory):** The warm paper-like foundation. Prevents clinical harshness and creates an inviting, physical stationery ambiance. Paired with pure porcelain (`#FFFFFF`) for elevated cards and modals.
- **Text & Borders:** Body copy rests at `#1A2E26` (a tinted deep charcoal-green) to avoid sterile `#000000`. Hairlines and borders utilize `#E5E0D8` to retain the tactile stationery look.

## Typography

The typography system pairs **Playfair Display** (editorial grace, emotional warmth, boutique heritage) with **Plus Jakarta Sans** (humanist geometry, high readability, optimistic modernism).

- **Headlines & Narrative Moments:** Use Playfair Display for gift titles, landing heroes, recipient greetings, and emotional storytelling. Keep italic variations strictly for expressive single words (e.g., *Surprise*, *Delivered*).
- **Functional Interface & Pricing:** Plus Jakarta Sans delivers crisp legibility across input fields, item descriptions, and status trackers.
- **Currency & Figures:** The Nigerian Naira (₦) symbol and large numerical values rely on `currency-display` or `label-lg` with tabular figures enabled (`font-variant-numeric: tabular-nums`) to maintain vertical alignment in carts, checkouts, and split-pay receipts.

## Layout & Spacing

This design system uses a fluid layout model anchored by deliberate white space to give each curated gift the prominence of a boutique display case.

- **Breakpoints:**
  - Mobile (`< 640px`): 4 columns, `margin-sm` (1rem / 16px), `gutter-sm` (1rem / 16px). Single-column card stacks, fixed sticky bottom action bars for thumb-reach checkout.
  - Tablet (`640px - 1024px`): 8 columns, `margin` (2rem / 32px), `gutter` (1.5rem / 24px). Two-column discovery grids.
  - Desktop (`> 1024px`): 12 columns, max content container width `1200px`, centered on the canvas with generous responsive page gutters.
- **Rhythm & Padding:** Component spacing adheres to strict multiples of 4px/8px. Internal card and modal padding prefers `space-lg` to `space-xl` to prevent visual compression and evoke luxury packaging standards.

## Elevation & Depth

Visual hierarchy uses tinted ambient shadows and surface shifts rather than stark borders:

- **Base Layer (Canvas):** Warm Ivory (`#FAF8F5`). Flat foundation.
- **Surface Layer (Cards, Modules):** Crisp Porcelain (`#FFFFFF`) elevated by a brand-tinted ambient shadow: `box-shadow: 0 10px 30px -10px rgba(12, 59, 46, 0.08)`. This soft emerald-tinted drop shadow anchors the component naturally into the ivory canvas.
- **Floating Overlays (Gift Previews, Modals, Drawers):** Elevated with high-diffusion depth: `box-shadow: 0 20px 40px -12px rgba(12, 59, 46, 0.16)`. Combined with a subtle 1px border of `rgba(12, 59, 46, 0.06)`.
- **Interactive Depth & Bounce:** Buttons and interactive cards feature a `translate-y-0` resting state that transitions to `-2px` on hover and `+1px` on active press via an energetic micro-bounce cubic-bezier curve (`cubic-bezier(0.34, 1.56, 0.64, 1)`).

## Shapes

The shape architecture is defined by sweeping, organic curves that feel approachable, comforting, and tactile.

- **Base Components (Inputs, Buttons, Badges):** 0.5rem (8px) to full pill (`9999px`) shapes for interactive targets and pills.
- **Standard Containers (`rounded-lg` / 1rem / 16px):** Used for standard cards, order summaries, and item pickers.
- **Featured Enclosures (`rounded-xl` / 1.5rem to 2rem / 24px-32px):** Applied to hero gift packages, celebration dialogs, delivery timeline modals, and unboxing reveals.
- **Embellishments:** Badges, tags, and promotional ribbon trims adopt smooth capsule profiles or soft chamfered scalloped edges reminiscent of high-grade cardstock and gift tags.

## Components

### Buttons
- **Primary (Emerald CTA):** Solid `#0C3B2E` with pure `#FFFFFF` text. Pill-shaped or `rounded-xl` (16px), minimum height 48px (54px for hero mobile CTAs). Features subtle tactile shadow. Active states scale down to `0.98` with a spring response.
- **Celebration Accent (Magenta/Rose):** Solid `#E6397B` with `#FFFFFF` text. Used for festive triggers ("Send Instantly", "Reveal Gift", "Add Confetti").
- **Secondary / Soft:** Surface tinted with `#E8EFE9` (Muted Sage), text in `#0C3B2E`. Hover transitions to a 10% deeper sage tone.
- **Tertiary (Ghost):** Transparent background, `#0C3B2E` text, underline animation starting from center outward on hover.

### Chips & Badges
- **Gift Tag Chips:** Soft rounded-full pills. Height 32px. Background `#FAF8F5`, hairline border `#E5E0D8`, text in `#0C3B2E`. When active/selected: `#0C3B2E` background with `#FFFFFF` text.
- **Celebratory Ribbon Badges:** Angular or pill ribbons placed at card corners in `#E6397B` with uppercase micro-copy (`label-sm`), adding festive flair to bespoke or trending gifts.

### Cards
- **Product & Experience Cards:** Built on pure porcelain `#FFFFFF` with 24px corner radius (`rounded-2xl`). Generous 16px to 20px padding. Integrated emerald drop shadow. Images have an internal 16px radius and expand slightly (`scale: 1.03`) on hover.
- **Greeting & Message Cards:** Styled like luxury cotton stationery. Off-white `#FAF8F5` surface with a subtle debossed border (`1px solid #E5E0D8`) and Playfair Display typography.

### Input Fields
- Height 52px, 12px corner radius. Background `#FFFFFF`, 1.5px border `#E5E0D8`. 
- Focus state: Border transitions to `#0C3B2E` with an emerald glow ring (`box-shadow: 0 0 0 3px rgba(12, 59, 46, 0.12)`).
- Prefix currency displays (e.g., `₦`) are weighted in bold sans-serif with subtle divider lines.

### Checkboxes & Radio Buttons
- 20px diameter. Unchecked: 1.5px border `#D3CFC9` on `#FFFFFF`. 
- Checked: Fill `#0C3B2E` with a crisp `#FFFFFF` checkmark or inner dot. Micro-bounce spring animation on trigger.

### Lists & Progress Trackers
- **Gift Delivery Tracker:** Horizontal step-indicator with connecting satin-green lines. Completed nodes display a small gift box or check icon wrapped in `#E8EFE9` with `#0C3B2E` icons.
- **Split Breakdown:** Clean tabular list itemizing base gift, personalized handwritten card, ribbon packaging, and delivery fees in Nigerian Naira with bold tabular figures.

### Unboxing & Celebration Components
- **Interactive Gift Reveal Box:** A specialized card simulating a parcel with dynamic ribbon pull interactions, particle confetti trigger states, and custom audio-haptic feedback on mobile clients.