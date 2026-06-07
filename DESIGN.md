---
name: Cognitive Precision
colors:
  surface: '#f9f9ff'
  surface-dim: '#cfdaf2'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f0f3ff'
  surface-container: '#e7eeff'
  surface-container-high: '#dee8ff'
  surface-container-highest: '#d8e3fb'
  on-surface: '#111c2d'
  on-surface-variant: '#42474f'
  inverse-surface: '#263143'
  inverse-on-surface: '#ecf1ff'
  outline: '#727780'
  outline-variant: '#c2c7d1'
  surface-tint: '#2b6197'
  primary: '#1b558b'
  on-primary: '#ffffff'
  primary-container: '#3a6ea5'
  on-primary-container: '#e4eeff'
  inverse-primary: '#9fcaff'
  secondary: '#785923'
  on-secondary: '#ffffff'
  secondary-container: '#fed491'
  on-secondary-container: '#785a23'
  tertiary: '#44546a'
  on-tertiary: '#ffffff'
  tertiary-container: '#5c6c83'
  on-tertiary-container: '#e4edff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d2e4ff'
  primary-fixed-dim: '#9fcaff'
  on-primary-fixed: '#001c37'
  on-primary-fixed-variant: '#02497e'
  secondary-fixed: '#ffdeac'
  secondary-fixed-dim: '#e9c080'
  on-secondary-fixed: '#281900'
  on-secondary-fixed-variant: '#5d420c'
  tertiary-fixed: '#d3e4fe'
  tertiary-fixed-dim: '#b7c8e1'
  on-tertiary-fixed: '#0b1c30'
  on-tertiary-fixed-variant: '#38485d'
  background: '#f9f9ff'
  on-background: '#111c2d'
  surface-variant: '#d8e3fb'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
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
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 40px
---

## Brand & Style

This design system is engineered for a technology-forward corporate environment, balancing high-performance utility with a premium aesthetic. The brand personality is authoritative yet approachable, emphasizing "Smart Solutions" through clarity and intentionality.

The design style is **Corporate Modern with a Tech-Infused Edge**. It leverages high-quality typography and generous white space to create a sense of breathability and focus. While the foundation is grounded in professional reliability, subtle futuristic elements—such as precise micro-borders, specific tonal layering, and smooth motion states—differentiate it from legacy corporate interfaces. The visual language avoids clutter, favoring elegant card-based containers and a structured information hierarchy that evokes a feeling of calm control and innovation.

## Colors

The palette is anchored by a deep, trustworthy blue (`#3A6EA5`) used for primary branding and navigational elements. This is complemented by a sophisticated gold accent (`#EEC584`), reserved strictly for high-priority calls to action and critical highlights to ensure they pierce through the professional blue-and-slate foundation.

- **Primary:** Branding, active states, and primary headings.
- **Accent:** High-impact CTAs and "Smart" feature highlights.
- **Neutral/Text:** Dark Slate (`#1E293B`) for body text and headers to ensure maximum readability and a premium feel.
- **Surface & Background:** A two-tier light system using a pure white (`#FFFFFF`) for interactive surfaces against a soft off-white (`#F8FAFC`) background to provide subtle contrast without harsh lines.

## Typography

The design system utilizes **Inter** for its systematic, utilitarian precision and exceptional legibility at all sizes. The type scale is designed to be highly hierarchical, allowing for easy scanning of complex data and professional reports.

Large display headings use a tighter letter-spacing and bold weights to command attention, while body text maintains a generous line height for long-form readability. Labels and "Smart" metadata should utilize the uppercase `label-sm` style to distinguish technical details from narrative content.

## Layout & Spacing

The layout philosophy follows a **fluid grid with fixed-width constraints** for readability. Content is centered within a maximum container width of 1280px to prevent excessive line lengths on ultra-wide monitors.

A 12-column grid is used for desktop layouts, transitioning to a 4-column grid for mobile. Spacing is based on an 8px rhythmic scale. Generous internal padding within cards (minimum 24px or 32px) is essential to maintain the "premium" feel. Layouts should prioritize vertical flow and stack-based modularity over complex, nested sidebars.

## Elevation & Depth

Depth is achieved through **Tonal Layering** and **Ambient Shadows**. This design system avoids heavy gradients in favor of subtle elevation cues that indicate interactivity.

- **Level 0 (Background):** `#F8FAFC`.
- **Level 1 (Cards/Surfaces):** `#FFFFFF` with a very soft, diffused shadow (15% opacity of the Primary color, 12px blur, 4px Y-offset).
- **Level 2 (Hover/Active):** Increased shadow spread and a 1px border using a 10% opacity of the Primary color to define the edge.
- **Interactive Elements:** Use "Low-contrast outlines" for form inputs and secondary buttons to maintain a clean, flat appearance until focused.

## Shapes

The shape language is **Modern and Balanced**. A "Rounded" setting (8px base) provides a approachable feel while maintaining the structural integrity required for a corporate environment.

- **Standard Elements:** 8px (0.5rem) corner radius for buttons, inputs, and small widgets.
- **Large Components:** 16px (1rem) for main content cards and modals.
- **Pill Elements:** Fully rounded (999px) for tags, status indicators, and specific "Smart" toggle switches to denote fluid movement.

## Components

### Buttons
- **Primary:** Solid `#3A6EA5` with white text. 8px radius.
- **Accent (CTA):** Solid `#EEC584` with `#1E293B` text. Reserved for "Get Started" or critical conversions.
- **Ghost:** Transparent background with a 1px `#3A6EA5` border.

### Cards
Cards are the primary container. They must feature the Level 1 shadow and 16px corner radius. Group related data using "Smart Sections"—subtle 1px horizontal dividers in `#E2E8F0`.

### Inputs
Fields use a 1px `#CBD5E1` border that transitions to 2px `#3A6EA5` on focus. Labels sit clearly above the input using the `label-md` type style.

### Chips & Status
Use pill-shaped backgrounds. For status indicators (e.g., "Active", "Processing"), use low-saturation versions of the status color (Success/Green, Warning/Amber) with high-contrast text to maintain the professional aesthetic.

### Data Visualization
Charts and graphs should use a monochromatic blue scale derived from the Primary color, using the Accent color only for the "Key Insight" or current data point.