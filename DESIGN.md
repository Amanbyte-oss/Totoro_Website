---
name: Midnight TotoroHaven
colors:
  surface: '#0b1326'
  surface-dim: '#0b1326'
  surface-bright: '#31394d'
  surface-container-lowest: '#060e20'
  surface-container-low: '#131b2e'
  surface-container: '#171f33'
  surface-container-high: '#222a3d'
  surface-container-highest: '#2d3449'
  on-surface: '#F8FAFC'
  on-surface-variant: '#ddc1b1'
  inverse-surface: '#dae2fd'
  inverse-on-surface: '#283044'
  outline: '#a58c7d'
  outline-variant: '#564336'
  surface-tint: '#ffb787'
  primary: '#ffb787'
  on-primary: '#FFFFFF'
  primary-container: '#f38020'
  on-primary-container: '#592900'
  inverse-primary: '#964900'
  secondary: '#bcc7de'
  on-secondary: '#263143'
  secondary-container: '#3e495d'
  on-secondary-container: '#aeb9d0'
  tertiary: '#b9c7e0'
  on-tertiary: '#233144'
  tertiary-container: '#91a0b7'
  on-tertiary-container: '#29374a'
  error: '#F43F5E'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdcc7'
  primary-fixed-dim: '#ffb787'
  on-primary-fixed: '#311300'
  on-primary-fixed-variant: '#723600'
  secondary-fixed: '#d8e3fb'
  secondary-fixed-dim: '#bcc7de'
  on-secondary-fixed: '#111c2d'
  on-secondary-fixed-variant: '#3c475a'
  tertiary-fixed: '#d5e3fd'
  tertiary-fixed-dim: '#b9c7e0'
  on-tertiary-fixed: '#0d1c2f'
  on-tertiary-fixed-variant: '#3a485c'
  background: '#0b1326'
  on-background: '#dae2fd'
  surface-variant: '#2d3449'
  on-surface-muted: '#94A3B8'
  border-subtle: '#1E293B'
typography:
  headline-display:
    fontFamily: Manrope
    fontSize: 44px
    fontWeight: '700'
    lineHeight: 52px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Manrope
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Manrope
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-sm:
    fontFamily: Manrope
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
  eyebrow:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.08em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  container-margin: 1rem
  gutter: 0.75rem
  stack-xs: 0.25rem
  stack-sm: 0.5rem
  stack-md: 1rem
  stack-lg: 2rem
  stack-xl: 4rem
---

## Brand & Style

The design system for this manga reader is built on a "Night" theme, prioritizing a premium, immersive, and sleek experience that recedes into the background to highlight the artwork. The aesthetic is a blend of **Minimalism** and **Corporate Modern**, utilizing deep, low-light surfaces and vibrant accents to create a high-contrast, energetic visual rhythm.

The target audience consists of enthusiasts who value a focused reading environment. By using a dark palette, the UI reduces eye strain and enhances the "theatrical" feel of manga consumption. The brand personality is professional yet spirited, mirroring the reliability of a high-end tool with the playful energy of the genre's culture.

## Colors

The palette is anchored by a deep "Night" foundation. The primary background uses `#0F172A`, a rich, dark blue-black that provides superior depth compared to pure black.

- **Primary (#F38020):** A vibrant orange derived from the branding, used for critical actions, active states, and brand signatures. It cuts through the dark backgrounds with high energy.
- **Secondary (#1E293B):** Used for elevated surfaces like cards, headers, and bottom navigation bars. This provides a subtle tonal lift from the base background.
- **Tertiary (#334155):** Reserved for interactive components in their rest state, such as input fields and filter chips.
- **Neutral (#0F172A):** The core canvas color.

Text is primarily rendered in `#F8FAFC` for maximum clarity, while supporting metadata uses `#94A3B8` to maintain a clear visual hierarchy.

## Typography

The system utilizes **Manrope** for headlines to provide a modern, geometric character that feels both technical and premium. **Inter** is used for body and UI labels to ensure clinical legibility across dense content lists and reader settings.

Hierarchy is strictly enforced:
- **Display and Large Headlines** are used for title screens and major section headers.
- **Body styles** are optimized for metadata (author names, descriptions) and reader menus.
- **Eyebrow text** is used for small category tags or "New Chapter" indicators to provide emphasis without bulk.

On mobile devices, headlines scale down by 20% to ensure titles of manga do not wrap excessively, maintaining the clean grid look.

## Layout & Spacing

This design system uses a **Fluid Grid** model optimized for media-heavy content. The vertical rhythm is based on a 4px baseline, ensuring consistent alignment between text and imagery.

- **Mobile:** A 2-column or 3-column grid for manga covers with 12px gutters and 16px side margins.
- **Tablet/Desktop:** A multi-column fluid grid that expands to fill the screen, allowing the artwork to scale. 
- **Content Density:** In the reader view, the layout transitions to a "No Grid" model where the content (manga pages) dictates the safe areas, with UI overlays appearing only on user interaction.

Internal card spacing is generous (16px) to prevent metadata from feeling cramped against the vibrant cover art.

## Elevation & Depth

Hierarchy is established through **Tonal Layers** rather than traditional shadows. This keeps the interface feeling "flat" and fast, consistent with modern app trends.

- **Level 0 (Base):** `#0F172A` - Used for the main application background.
- **Level 1 (Surface):** `#1E293B` - Used for navigation bars, cards, and bottom sheets.
- **Level 2 (Interactive):** `#334155` - Used for buttons and inputs.

Depth is further reinforced with **Low-contrast outlines**. Components like cards use a 1px border of `#1E293B` to define edges against the base background without creating visual noise. Primary buttons may use a subtle glow (low-spread orange shadow) to indicate they are the focal point.

## Shapes

The shape language is **Rounded**, reflecting the approachable and friendly nature of the brand icon. 

- **Standard Elements (Buttons, Inputs):** 8px (0.5rem) radius.
- **Manga Covers/Cards:** 16px (1rem) radius to soften the high-intensity artwork.
- **Navigation Indicators:** Pill-shaped (full radius) to clearly distinguish them from content-based actions.

This consistency in rounding ensures that even in a high-contrast dark theme, the app feels comfortable and easy to navigate.

## Components

- **Buttons:** Primary buttons use the brand orange with white text. Secondary buttons use the `tertiary` surface with `on-surface` text.
- **Manga Cards:** Vertical orientation. The cover art is the hero, with a subtle gradient overlay at the bottom to ensure readability of the title text which sits directly on the card.
- **Chips:** Used for genres and tags. They use a `#1E293B` background with `label-sm` typography and a full-pill radius.
- **Bottom Navigation:** Uses a frosted glass effect (backdrop blur) over the `secondary` color to allow the manga content to peek through slightly during scrolls.
- **Input Fields:** Darker than the surface (`#0F172A`) with a subtle `tertiary` border. On focus, the border shifts to the brand orange.
- **Reader Controls:** Highly translucent dark overlays with crisp white icons. Sliders for brightness and progress use the brand orange for the active track.