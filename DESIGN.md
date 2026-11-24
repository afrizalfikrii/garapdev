---
name: Garap.dev Neo-Brutalist Terminal
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0edec'
  surface-container-high: '#ebe7e7'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1c1b1b'
  on-surface-variant: '#4f4632'
  inverse-surface: '#313030'
  inverse-on-surface: '#f3f0ef'
  outline: '#81765f'
  outline-variant: '#d2c5ab'
  surface-tint: '#765b00'
  primary: '#765b00'
  on-primary: '#ffffff'
  primary-container: '#ffc700'
  on-primary-container: '#6e5400'
  inverse-primary: '#f5bf00'
  secondary: '#b81313'
  on-secondary: '#ffffff'
  secondary-container: '#dc3129'
  on-secondary-container: '#fffbff'
  tertiary: '#006875'
  on-tertiary: '#ffffff'
  tertiary-container: '#00e3fd'
  on-tertiary-container: '#00616d'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdf94'
  primary-fixed-dim: '#f5bf00'
  on-primary-fixed: '#251a00'
  on-primary-fixed-variant: '#594400'
  secondary-fixed: '#ffdad5'
  secondary-fixed-dim: '#ffb4aa'
  on-secondary-fixed: '#410001'
  on-secondary-fixed-variant: '#930006'
  tertiary-fixed: '#9cefff'
  tertiary-fixed-dim: '#00daf3'
  on-tertiary-fixed: '#001f24'
  on-tertiary-fixed-variant: '#004f58'
  background: '#fcf9f8'
  on-background: '#1c1b1b'
  surface-variant: '#e5e2e1'
typography:
  display-xl:
    fontFamily: Bricolage Grotesque
    fontSize: 56px
    fontWeight: '800'
    lineHeight: 60px
    letterSpacing: -0.03em
  display-xl-mobile:
    fontFamily: Bricolage Grotesque
    fontSize: 36px
    fontWeight: '800'
    lineHeight: 40px
    letterSpacing: -0.025em
  headline-lg:
    fontFamily: Bricolage Grotesque
    fontSize: 40px
    fontWeight: '800'
    lineHeight: 44px
    letterSpacing: -0.025em
  headline-lg-mobile:
    fontFamily: Bricolage Grotesque
    fontSize: 28px
    fontWeight: '800'
    lineHeight: 32px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Bricolage Grotesque
    fontSize: 28px
    fontWeight: '800'
    lineHeight: 34px
    letterSpacing: -0.02em
  headline-sm:
    fontFamily: Bricolage Grotesque
    fontSize: 22px
    fontWeight: '700'
    lineHeight: 28px
    letterSpacing: -0.015em
  body-lg:
    fontFamily: DM Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: 0em
  body-md:
    fontFamily: DM Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-sm:
    fontFamily: DM Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  label-lg:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '700'
    lineHeight: 20px
    letterSpacing: 0.02em
  label-md:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.04em
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.05em
spacing:
  gutter: 1.5rem
  margin: 1.5rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system powers Garap.dev, an Indonesian freelance developer brand built on unapologetic clarity, technical confidence, and street-level craft. The target audience consists of startup founders, product managers, and agencies looking for a sharp, reliable engineering partner who ships fast without corporate fluff.

The UI evokes the energy of a developer terminal colliding with tactile print zines—direct, high-contrast, and functional. It merges **Neo-Brutalism** (thick `#111111` borders, hard offset shadows, raw geometric structure, and sticker-style badges) with **Developer Terminal** aesthetics (monospaced metadata, command-line snippets, and high-legibility dark-mode code blocks).

Strict visual rules govern the aesthetic:
- **Zero softness:** No gradients, no purple, no glassmorphism, no backdrop blurs, and no ambient glow effects.
- **Tactile flatness:** Depth is achieved strictly through solid `2px`–`3px` borders and hard, unblurred offset shadows.
- **Playful precision:** Slightly rotated sticker-style badges inject personality without compromising the structured, grid-aligned layout.

## Colors

The palette is strictly constrained to four high-contrast colors that reinforce the neo-brutalist terminal identity:

- **Background / Canvas (`#F5EBD7`):** A warm cream paper tone that replaces sterile white, reducing eye strain while giving cards and borders a tactile, print-inspired foundation.
- **Ink & Borders (`#111111`):** Near-black used for all primary body text, headings, `2px`–`3px` structural borders, and hard offset shadows.
- **Primary Accent (`#FFC700`):** Bold, high-visibility yellow reserved for primary CTAs, active states, highlighted badges, and key interactive focal points.
- **Secondary Accent (`#FF4B3E`):** Tomato red used sparingly for urgent status indicators, destructive actions, and secondary sticker badges.

### Dark Terminal Sections
For dedicated terminal snippets, code blocks, and high-contrast feature bands, invert the surface to `#111111` with `#FFC700` primary text and `#F5EBD7` secondary text. Never introduce gradients, purple hues, or semi-transparent overlays.

## Typography

The typographic hierarchy pairs expressive, heavy display headings with clean, readable body copy and crisp monospaced metadata:

- **Headings (`Bricolage Grotesque`):** Used at Extra Bold (`800`) and Bold (`700`) weights with tight negative letter spacing (`-0.015em` to `-0.03em`) to create dense, impactful headlines that command attention.
- **Body (`DM Sans`):** Provides a neutral, highly legible reading experience for project descriptions, case studies, and service details.
- **Labels & Terminal (`JetBrains Mono`):** Used for all UI labels, status tags, pricing figures, timestamps, and inline terminal snippets. Uppercase styling with slight positive tracking (`0.04em`–`0.05em`) is encouraged for `label-md` and `label-sm` badges.

On mobile viewports, `display-xl` and `headline-lg` step down to `display-xl-mobile` (`36px`) and `headline-lg-mobile` (`28px`) to prevent horizontal overflow while preserving aggressive hierarchy.

## Layout & Spacing

This design system uses a **12-column fluid grid** with a maximum container width of `1280px` on desktop, ensuring content stays structured and scannable without stretching excessively on ultrawide monitors.

- **Desktop (`>= 1024px`):** 12 columns, `24px` (`1.5rem`) gutters, and `48px` outer canvas margins.
- **Tablet (`768px - 1023px`):** 8 columns, `24px` (`1.5rem`) gutters, and `32px` outer margins.
- **Mobile (`< 768px`):** 4 columns, `16px` (`1rem`) gutters, and `16px`–`24px` outer margins. Multi-column card grids collapse to single-column stacks.

Because all cards and buttons carry `6px` hard offset shadows, always maintain at least `space-md` (`1rem`) between adjacent interactive elements so shadows never collide or clip.

## Elevation & Depth

Hierarchy is conveyed strictly through **bold borders** and **hard offset shadows**—never through soft ambient blurs, translucency, or surface gradients.

- **Borders:** Every card, button, input field, and container is framed with a solid `2px` or `3px` `#111111` border.
- **Hard Offset Shadows:** Elevated elements (cards, primary buttons, modal dialogs, and dropdowns) use a crisp `6px 6px 0 #111111` shadow with `0px` blur radius.
- **Interactive Press State:** On hover, interactive elements may shift `-2px` on both axes (`8px 8px 0 #111111` shadow). On active/click, elements translate `4px` down and right while reducing the shadow to `2px 2px 0 #111111`, simulating a physical mechanical key press.

## Shapes

The shape language is **Sharp (`0px`)**. All cards, buttons, input fields, terminal blocks, and containers feature crisp `90-degree` corners (`border-radius: 0px`) to reinforce the raw, grid-locked neo-brutalist aesthetic.

The only exception is **sticker-style badges**, which may use `0px` or subtle `2px` corners combined with a slight rotation (`-2deg` to `3deg`) to break the rigid grid and add human, zine-like character.

## Components

### Buttons
- **Primary CTA:** `#FFC700` background, `#111111` text in `JetBrains Mono` (`label-lg`), `2px solid #111111` border, `6px 6px 0 #111111` shadow.
- **Secondary / Destructive:** `#FF4B3E` background with `#111111` or `#F5EBD7` text, `2px solid #111111` border, `6px 6px 0 #111111` shadow.
- **Ghost / Outline:** Transparent or `#F5EBD7` background, `2px solid #111111` border, no shadow at rest; gains `4px 4px 0 #111111` on hover.

### Cards
- **Standard Card:** `#F5EBD7` background, `3px solid #111111` border, `6px 6px 0 #111111` shadow, `space-lg` (`1.5rem`) internal padding.
- **Terminal / Code Card:** `#111111` background, `#FFC700` primary text, `#F5EBD7` secondary text, `3px solid #111111` border, `6px 6px 0 #FFC700` or `#111111` shadow. Include a top header bar with monospaced file/command title.

### Badges & Chips
- **Sticker Badges:** `JetBrains Mono` (`label-sm` or `label-md`), `#FFC700` or `#FF4B3E` fill, `2px solid #111111` border, `3px 3px 0 #111111` shadow, and a slight CSS rotation (`transform: rotate(-2deg)` or `rotate(2deg)`).

### Input Fields
- `#F5EBD7` background, `2px solid #111111` border, `0px` border radius, `DM Sans` (`body-md`) input text with `JetBrains Mono` (`label-md`) field labels positioned above.
- On focus, apply a `4px 4px 0 #FFC700` or `4px 4px 0 #111111` hard offset shadow without any glow or outline blur.

### Checkboxes & Radio Buttons
- `20px × 20px` sharp-cornered (`0px`) boxes with `2px solid #111111` borders. Checked states fill with `#FFC700` and display a bold `#111111` checkmark or inner square.

### Lists
- Structured with `2px solid #111111` horizontal dividers between rows. Interactive list items highlight with `#FFC700` background on hover.