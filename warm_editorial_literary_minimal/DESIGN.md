---
name: Warm Editorial Literary Minimal
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
  on-surface-variant: '#58423c'
  inverse-surface: '#30312f'
  inverse-on-surface: '#f2f0ed'
  outline: '#8b716a'
  outline-variant: '#dfc0b7'
  surface-tint: '#a73918'
  primary: '#a43716'
  on-primary: '#ffffff'
  primary-container: '#c54f2c'
  on-primary-container: '#fffbff'
  inverse-primary: '#ffb5a0'
  secondary: '#615e58'
  on-secondary: '#ffffff'
  secondary-container: '#e7e2da'
  on-secondary-container: '#67645e'
  tertiary: '#006575'
  on-tertiary: '#ffffff'
  tertiary-container: '#008093'
  on-tertiary-container: '#f8fdff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdbd1'
  primary-fixed-dim: '#ffb5a0'
  on-primary-fixed: '#3b0900'
  on-primary-fixed-variant: '#862201'
  secondary-fixed: '#e7e2da'
  secondary-fixed-dim: '#cbc6bf'
  on-secondary-fixed: '#1d1b17'
  on-secondary-fixed-variant: '#494641'
  tertiary-fixed: '#a5eeff'
  tertiary-fixed-dim: '#6bd5eb'
  on-tertiary-fixed: '#001f25'
  on-tertiary-fixed-variant: '#004e5a'
  background: '#fbf9f6'
  on-background: '#1b1c1a'
  surface-variant: '#e4e2df'
typography:
  display-lg:
    fontFamily: Newsreader
    fontSize: 3.5rem
    fontWeight: '400'
    lineHeight: '1.15'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Newsreader
    fontSize: 2.25rem
    fontWeight: '400'
    lineHeight: '1.2'
    letterSpacing: -0.015em
  headline-lg:
    fontFamily: Newsreader
    fontSize: 2rem
    fontWeight: '500'
    lineHeight: '1.25'
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Newsreader
    fontSize: 1.5rem
    fontWeight: '500'
    lineHeight: '1.3'
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Newsreader
    fontSize: 1.25rem
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.0625rem
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.9375rem
    fontWeight: '400'
    lineHeight: '1.55'
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.8125rem
    fontWeight: '400'
    lineHeight: '1.5'
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.875rem
    fontWeight: '600'
    lineHeight: '1.25'
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.75rem
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.04em
  code-sm:
    fontFamily: Courier Prime
    fontSize: 0.8125rem
    fontWeight: '400'
    lineHeight: '1.45'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-md: 1.5rem
  gutter-lg: 2rem
  margin: 1rem
  margin-md: 2rem
  margin-lg: 3rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system pairs the tactile intimacy of physical editorial print with the precision of a modern bibliographic engine. It targets readers, researchers, and digital collectors searching through the OpenLibrary index who desire a distraction-free, contemplative interface.

The design movement combines **warm editorial minimalism** with structured cataloguing:
- Deep respect for whitespace, evoking parchment, unbound book proofs, and archival catalog cards.
- Literary warmth replaces stark clinical monochrome without sacrificing algorithmic utility.
- Pacing is measured and deliberate; interface elements feel balanced, calm, and scholarly.

## Colors

The palette reproduces the tactile quality of archival paper, terracotta bookbindings, and printer's ink.

- **Canvas Background (`#FAF8F5`)**: A soft bone white that prevents screen glare and gives the page an organic paper feel.
- **Surface Elevation (`#FFFFFF`)**: Pure white cards reserved strictly for interactive tiles, floating dialogs, and reader views.
- **Primary Accent (`#D95D39`)**: Terracotta lacquer used for primary call-to-actions, active links, focus indicators, and key metadata highlights.
- **Typography & Structure**: Dark charcoal (`#1E1E1E`) for primary body text, titles, and high-legibility data points; muted earth-taupe (`#6B6862`) for metadata labels, publication years, and secondary context.
- **Subtle Surface & Borders**: Warm cream (`#F3EFE9`) for badges, tags, and code preview containers; subtle warm sand (`#E5E0D8`) for structural dividers and card outlines.

## Typography

The type system creates an editorial conversation between literary tradition and technical precision.

- **Headlines (`Newsreader`)**: Selected for its graceful optical sizes, scholarly character, and legibility at large weights. Used for book titles, author showcases, section banners, and search query highlights.
- **Controls & Metadata (`Plus Jakarta Sans`)**: Neutral, contemporary, and geometrically balanced. Retains clarity in small cataloging lines, button labels, query inputs, and dense metadata tables.
- **Technical Inspection (`Courier Prime`)**: Used specifically for OpenLibrary raw JSON previews, ISBN-13 strings, and schema definitions to evoke typewriter index cards.

## Layout & Spacing

A fluid grid system that prioritizes single-column mobile ergonomics and transitions into an editorial multi-column catalog on larger viewports.

- **Mobile (< 640px)**: 4-column layout with `margin: 1rem` and `gutter: 1rem`. Cards and book listing items take full canvas width with generous vertical breathing room (`space-lg`).
- **Tablet (640px - 1024px)**: 8-column layout with `margin: 2rem` and `gutter: 1.5rem`. Enables side-by-side search results and metadata sidebars.
- **Desktop (> 1024px)**: 12-column layout with `margin: 3rem`, constrained to a maximum content width of `1280px` for optimal reading line length.

## Elevation & Depth

Visual hierarchy relies on crisp surface separation, warm border definitions, and low-opacity ambient drop shadows rather than heavy synthetic blur.

- **Card Surfaces**: Pure white `#FFFFFF` layered over the `#FAF8F5` bone background, outlined by a 1px solid `#E5E0D8` border.
- **Floating Modals & Dropdowns**: Elevated with a subtle warm-tinted shadow (`0 8px 24px -4px rgba(30, 30, 30, 0.06), 0 2px 6px -1px rgba(30, 30, 30, 0.04)`) combined with the standard `#E5E0D8` border.
- **Active & Pressed States**: Physical depression simulated by reducing card drop shadows to zero and applying a 1px tint shift to `#D95D39`.

## Shapes

The interface balances soft, modern rounded corners with classic publication grids.

- **Cards & Major Panels**: Standardize on `rounded-xl` (1rem) for search result items and `rounded-2xl` (1.5rem) for hero display units and API explorer consoles.
- **Controls & Badges**: Form inputs, query chips, and status pills utilize standard `rounded-lg` (0.75rem) or fully pill-shaped radiuses (`9999px`) to maintain interactive affordance.

## Components

### Buttons
- **Primary**: Terracotta `#D95D39` background, `#FFFFFF` text, `font-weight: 600`. Subtle hover shift to `#C24C29` with a 150ms ease transition. Padding: `0.75rem 1.25rem`.
- **Secondary / Ghost**: Transparent background, 1px border with `#E5E0D8`, `#1E1E1E` text. Hovers transition to `#F3EFE9`.

### Input Fields & Search Bars
- Background: `#FFFFFF`.
- Border: 1px solid `#E5E0D8`, expanding to a 1.5px `#D95D39` focus ring with zero outer glow.
- Placeholder text: `#6B6862`.
- Integrated clear and filter action icons tinted in `#6B6862`.

### Chips & Suggested Query Tags
- Background: `#F3EFE9`, text `#1E1E1E`, subtle border in `#E5E0D8`.
- Interactive chips shift to `#E5E0D8` background on tap/hover; selected query chips invert to `#1E1E1E` background with `#FAF8F5` text.

### Book Cards
- Dual-tier elevation: Pure `#FFFFFF` surface container, 1px `#E5E0D8` border, `rounded-xl` corners.
- Book cover asset rendered with an internal `0 2px 8px rgba(0,0,0,0.08)` spine shadow to suggest physical volume.
- Title rendered in `Newsreader` (`headline-sm`), author and edition year in `Plus Jakarta Sans` (`body-sm`, `#6B6862`).

### API JSON Preview Console
- Container: `#F3EFE9` background, 1px `#E5E0D8` border, `rounded-xl` corners, monospace `code-sm` font.
- Syntax highlights: Terracotta `#D95D39` for keys, `#1E1E1E` for string values, `#6B6862` for structural braces and nulls.
- Includes a 1-click "Copy JSON" secondary pill button docked to top-right corner.