---
name: Executive Editorial
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
  secondary: '#2b6954'
  on-secondary: '#ffffff'
  secondary-container: '#adedd3'
  on-secondary-container: '#306d58'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#1b1c1c'
  on-tertiary-container: '#848483'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e5e2e1'
  primary-fixed-dim: '#c8c6c5'
  on-primary-fixed: '#1c1b1b'
  on-primary-fixed-variant: '#474746'
  secondary-fixed: '#b0f0d6'
  secondary-fixed-dim: '#95d3ba'
  on-secondary-fixed: '#002117'
  on-secondary-fixed-variant: '#0b513d'
  tertiary-fixed: '#e4e2e2'
  tertiary-fixed-dim: '#c8c6c6'
  on-tertiary-fixed: '#1b1c1c'
  on-tertiary-fixed-variant: '#474747'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
typography:
  headline-xl:
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: -0.01em
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1'
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 4px
  container-max: 1280px
  article-max: 720px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 64px
---

## Brand & Style

The design system is engineered for a premium professional blog platform catering to industry leaders, founders, and consultants. It prioritizes content clarity and intellectual authority through a **Minimalist Editorial** aesthetic. 

The visual narrative is built on the tension between high-contrast serif typography and expansive white space, evoking the feeling of a prestige print journal. The emotional response should be one of calm focus, maturity, and uncompromising quality. Elements are structured with surgical precision, utilizing thin lines and subtle tonal shifts rather than heavy ornamentation.

## Colors

The palette is anchored in high-contrast neutrals to maintain a sophisticated, timeless look. 

- **Primary (#1A1A1A):** Used for headlines and core brand elements. It provides the "ink" of the digital page.
- **Secondary (#064E3B):** A muted emerald used sparingly for high-value calls to action, text links within articles, and subtle brand accents.
- **Tertiary (#4A4A4A):** Applied to secondary UI labels, metadata, and supporting text to reduce visual noise.
- **Neutral (#FAFAFA):** The foundation of the system, providing a warm, off-white background that reduces eye strain compared to pure white.

Surface backgrounds use a subtle tiered approach: `Neutral` for the main canvas and a slightly darker ghost-grey for input fields or secondary containers.

## Typography

Typography is the primary vehicle for brand expression in this design system.

- **Headlines:** Use **Playfair Display**. Its high-contrast strokes reflect a sophisticated, editorial character. For `headline-xl`, use tight tracking to maintain a modern, "tight" look.
- **Body Text:** Use **Inter**. It provides exceptional legibility for long-form professional essays. Body text is set with a generous line height (1.6) to ensure a comfortable reading rhythm.
- **UI & Metadata:** Labels use Inter in medium or semi-bold weights. Metadata (dates, categories) should often be set in uppercase with increased letter spacing to distinguish it clearly from body prose.

## Layout & Spacing

The layout philosophy follows a **Fixed Grid** approach for content containers to ensure optimal line lengths for reading.

- **Main Container:** Max width of 1280px for standard pages.
- **Article Reading Column:** Restricted to 720px and centered to prevent scanning fatigue.
- **Rhythm:** A 4px baseline grid ensures vertical consistency.
- **Desktop:** 12-column grid with 24px gutters. Use large margins (64px) to frame the content.
- **Mobile:** Single column with 20px side margins. Large display headlines should scale down to 40px to remain readable without excessive wrapping.

## Elevation & Depth

This design system avoids heavy shadows and skeuomorphism, favoring **Tonal Layers** and **Low-Contrast Outlines**.

- **Surfaces:** Use `#FFFFFF` (pure white) for elevated elements like cards or menus against the `#FAFAFA` background.
- **Borders:** Instead of shadows, use 1px solid borders in a very light grey or the primary color at 10% opacity to define boundaries.
- **Shadows:** When necessary for functional depth (e.g., dropdown menus), use "Ambient Shadows"—extremely soft, blurred shadows with no offset: `0 10px 40px rgba(0,0,0,0.04)`.
- **Active States:** Subtle shifts in background color (e.g., moving from `#FAFAFA` to `#F2F2F2`) are preferred over elevation changes.

## Shapes

The shape language is **Soft (0.25rem)**. 

While the design is minimalist, sharp corners are avoided to keep the interface feeling contemporary and approachable. Buttons and input fields use a 4px radius (`rounded`). Larger components like feature images or modal containers can use 8px (`rounded-lg`). Circle radii are reserved strictly for user avatars.

## Components

- **Buttons:** Primary buttons are solid `#1A1A1A` with `#FAFAFA` text. Secondary buttons are outlined with a 1px border. All buttons use `label-md` typography.
- **Article Cards:** Use a vertical stack—large image, category label (uppercase), Playfair Display headline, and a 2-line Inter summary. No borders; use generous white space for separation.
- **Input Fields:** Minimalist design with a 1px bottom border only, or a very light 4px rounded frame. Focus state is indicated by a color shift of the border to the Secondary emerald.
- **Chips/Tags:** Small, rectangular with a 2px radius. Use a light grey background (`#EEEEEE`) and `label-sm` text.
- **Lists:** Clean dividers (1px, 5% black). Use `body-md` for list items with increased vertical padding (16px) to maintain the airy editorial feel.
- **Navigation:** Top-bar navigation is sticky but shrinks on scroll. Use a very thin bottom divider to separate it from the content.