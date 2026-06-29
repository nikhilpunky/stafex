---
name: Stafex Core
colors:
  surface: '#f7f9fb'
  surface-dim: '#d8dadc'
  surface-bright: '#f7f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f6'
  surface-container: '#eceef0'
  surface-container-high: '#e6e8ea'
  surface-container-highest: '#e0e3e5'
  on-surface: '#191c1e'
  on-surface-variant: '#434652'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#747783'
  outline-variant: '#c4c6d3'
  surface-tint: '#345baf'
  primary: '#002869'
  on-primary: '#ffffff'
  primary-container: '#0b3d91'
  on-primary-container: '#8dadff'
  inverse-primary: '#b1c5ff'
  secondary: '#515f74'
  on-secondary: '#ffffff'
  secondary-container: '#d5e3fc'
  on-secondary-container: '#57657a'
  tertiary: '#4f1c00'
  on-tertiary: '#ffffff'
  tertiary-container: '#732c00'
  on-tertiary-container: '#ff925b'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dae2ff'
  primary-fixed-dim: '#b1c5ff'
  on-primary-fixed: '#001947'
  on-primary-fixed-variant: '#144296'
  secondary-fixed: '#d5e3fc'
  secondary-fixed-dim: '#b9c7df'
  on-secondary-fixed: '#0d1c2e'
  on-secondary-fixed-variant: '#3a485b'
  tertiary-fixed: '#ffdbcc'
  tertiary-fixed-dim: '#ffb693'
  on-tertiary-fixed: '#351000'
  on-tertiary-fixed-variant: '#7a3000'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Inter
    fontSize: 30px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
    letterSpacing: -0.01em
  title-lg:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: '1.4'
    letterSpacing: 0.02em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: 0em
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: 0em
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: 0.05em
  caption:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: '1.4'
    letterSpacing: 0em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 32px
  xxl: 48px
  section: 80px
  gutter: 24px
  container-max: 1280px
---

## Brand & Style
The design system is built on the pillars of **Modern Corporate Professionalism** and **High-Trust Minimalism**. It targets enterprise clients and high-value talent, demanding a UI that feels expert, reliable, and performance-driven. 

The aesthetic draws from contemporary Swiss minimalism—prioritizing clarity, generous whitespace, and a rigid underlying grid. By stripping away decorative excess, the design system allows the authoritative Navy Blue and precision-engineered typography to signal institutional stability. The user experience should feel effortless and deliberate, evoking the same confidence one finds in top-tier global consultancy firms.

## Colors
The palette is dominated by **Stafex Navy (#0B3D91)**, which anchors the interface in trust and tradition. A clean, pure white background ensures maximum "breathability" and a premium feel. 

- **Primary:** Used for brand moments, primary actions, and navigational headers.
- **Secondary (Dark Grey):** Used for supporting text and iconography to maintain a softer visual hierarchy than pure black.
- **Accent Orange:** Reserved exclusively for high-impact Call-to-Action (CTA) elements and critical status indicators. Use sparingly to maintain its disruptive power.
- **Surface:** A very light cool grey used to differentiate card backgrounds or section blocks from the global white background.

## Typography
This design system utilizes **Inter** for its systematic, utilitarian, and professional qualities. The type scale is modular, favoring legibility and structural hierarchy.

- **Headings:** Bold weights with slightly tightened letter spacing for a compact, "architectural" feel.
- **Caps/Labels:** Important metadata or small labels should use the `label-md` style with increased letter spacing (tracked out) and uppercase styling to denote authority.
- **Body:** Generous line-height (1.6) is mandatory to ensure readability in data-heavy or long-form workforce reporting.

## Layout & Spacing
The layout follows a strict **8-pixel grid system**. All dimensions, padding, and margins must be increments of 8 (with 4px used only for micro-adjustments in tight components like tags).

- **Grid:** A 12-column fixed grid is used for desktop (max-width 1280px), centered in the viewport. 
- **Margins:** Desktop margins are set to 48px; Tablet to 32px; Mobile to 16px.
- **Section Spacing:** Use `section` (80px) spacing between major vertical blocks to maintain the minimalist, airy feel.
- **Alignment:** Content should predominantly be left-aligned to mirror professional documentation and report structures.

## Elevation & Depth
Elevation in this design system is subtle and intentional, moving away from heavy drop shadows toward **Tonal Layers** and **Soft Ambient Shadows**.

- **Level 0 (Flat):** The default state for the main background.
- **Level 1 (Subtle):** Used for cards and containers. Defined by a 1px border in `#E2E8F0` and a very soft, diffused shadow (0px 4px 20px rgba(15, 23, 42, 0.05)).
- **Level 2 (Hover/Active):** When a user interacts with a card, the shadow should deepen slightly (0px 8px 30px rgba(15, 23, 42, 0.08)) and the element may lift 2px.
- **Interactive Depth:** Buttons do not use shadows; they use solid color fills to maintain a clean, flat, professional look.

## Shapes
The shape language is **Soft (0.25rem)**. This provides a subtle modern touch that breaks the harshness of a purely corporate grid without becoming too "bubbly" or consumer-grade.

- **Buttons & Inputs:** 4px (0.25rem) corner radius.
- **Cards:** 8px (0.5rem) corner radius to create a distinct container feel.
- **Avatars:** Circular (pill) to provide a organic contrast against the geometric UI.

## Components
Consistent component styling ensures the design system remains cohesive across the Stafex platform.

- **Buttons:** 
  - *Primary:* Navy Blue background, white text. No shadow. 
  - *Secondary:* Clear background, Navy Blue border (1px). 
  - *CTA:* Orange background, white text. Reserved for "Post a Job" or "Apply Now."
- **Cards:** White background, 1px `#E2E8F0` border, 8px rounded corners. Content should have at least 24px internal padding.
- **Input Fields:** 1px border in `#E2E8F0`. Focus state uses a 1px Navy Blue border and a 3px soft blue outer glow.
- **Chips/Badges:** Small, 4px rounded corners, using the `label-md` type style. Use light grey backgrounds with dark grey text for neutral states.
- **Imagery:** Use high-resolution industrial and corporate photography with a cool temperature bias (slight blue tint) to align with the brand color.
- **Iconography:** Use 24px stroke-based icons (2px weight). Avoid filled icons unless indicating an active toggle state.