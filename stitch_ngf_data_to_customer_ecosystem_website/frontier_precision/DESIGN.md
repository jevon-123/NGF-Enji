---
name: Frontier Precision
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
  on-surface-variant: '#5b403d'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#8f6f6c'
  outline-variant: '#e4beba'
  surface-tint: '#ba1a20'
  primary: '#af101a'
  on-primary: '#ffffff'
  primary-container: '#d32f2f'
  on-primary-container: '#fff2f0'
  inverse-primary: '#ffb3ac'
  secondary: '#565e74'
  on-secondary: '#ffffff'
  secondary-container: '#dae2fd'
  on-secondary-container: '#5c647a'
  tertiary: '#005f7b'
  on-tertiary: '#ffffff'
  tertiary-container: '#00799c'
  on-tertiary-container: '#e9f7ff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad6'
  primary-fixed-dim: '#ffb3ac'
  on-primary-fixed: '#410003'
  on-primary-fixed-variant: '#930010'
  secondary-fixed: '#dae2fd'
  secondary-fixed-dim: '#bec6e0'
  on-secondary-fixed: '#131b2e'
  on-secondary-fixed-variant: '#3f465c'
  tertiary-fixed: '#bee9ff'
  tertiary-fixed-dim: '#7bd1f8'
  on-tertiary-fixed: '#001f2a'
  on-tertiary-fixed-variant: '#004d65'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
  deep-crimson: '#D32F2F'
  hera-blue: '#3B82F6'
  hema-purple: '#8B5CF6'
  netcore-orange: '#F97316'
  konvergence-teal: '#0D9488'
  border-subtle: '#E2E8F0'
  text-main: '#1E293B'
  text-muted: '#64748B'
typography:
  display-xl:
    fontFamily: Geist
    fontSize: 72px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.04em
  display-xl-mobile:
    fontFamily: Geist
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Geist
    fontSize: 48px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Geist
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-md:
    fontFamily: Geist
    fontSize: 30px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.7'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: Geist
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.0'
    letterSpacing: 0.1em
  stats-number:
    fontFamily: Geist
    fontSize: 56px
    fontWeight: '700'
    lineHeight: '1.0'
    letterSpacing: -0.02em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  container-max: 1280px
  gutter: 24px
  section-padding: 120px
  section-padding-mobile: 64px
  bento-gap: 16px
---

## Brand & Style

The design system embodies "Data-driven Authority." It is a premium corporate framework designed for an Indonesian AI ecosystem that bridges the gap between raw market data and tangible customer impact. The brand personality is intellectual, institutional, and cutting-edge, yet accessible enough to feel like a strategic partner rather than just a software provider.

The visual style is **Minimalist with Bento-Box influences**. It utilizes a sophisticated "Clean Light Mode" to project transparency and clarity. To differentiate from standard corporate SaaS, it incorporates **Ecosystem Accents**—subtle, high-fidelity ambient glows and gradients—that represent the diverse technical specializations (AI, Martech, Systems Integration) within the group.

**Key Stylistic Pillars:**
- **Bento Grid Layouts:** Systematic organization of business units and case studies to imply modularity and scale.
- **High-End Technicality:** Use of hairline dividers, monospaced numerical data, and generous white space.
- **Strategic Heat:** Deep Crimson is reserved strictly for high-value actions and primary brand signifiers, ensuring it never overwhelms the clean aesthetic.

## Colors

The palette is anchored by **Deep Crimson**, a color of action and leadership, derived from the core logo. This is supported by a foundation of "Pure White" and "Soft Slate" to maintain a high-end corporate feel.

### Color Application
- **Primary (Deep Crimson):** Used for primary CTAs, active states in navigation, and key statistical highlights.
- **Secondary (Midnight Navy):** Used for primary headings and heavy text to provide grounded authority.
- **Ecosystem Accents:** These are used as "Ambient Glows" (low-opacity background blurs) or small "Identity Dots" next to SBU names (HERA, HEMA, etc.) to visually categorize the ecosystem without breaking the minimalist theme.
- **Surface Strategy:** Use `#FFFFFF` for the main background and `#F8FAFC` (Soft Slate) for "Bento Box" containers to create subtle depth without relying on heavy shadows.

## Typography

The typography system relies on **Geist** for its precision and technical sharpness, paired with **Inter** for maximum readability in data-heavy sections.

- **Headlines:** Set in Geist with tight letter-spacing to evoke a modern, "engineered" feel. Large display type should be used sparingly for hero sections and major transitions.
- **Body:** Inter is used for all descriptive text. Maintain a generous line-height (1.6+) to ensure the "Data-to-Customer" narrative remains breathable and professional.
- **Numerical Data:** Statistics and timeline years should use the `stats-number` style to stand out as authoritative proof points.
- **Labels:** Small, uppercase labels in Geist should be used above section headers (e.g., "OUR JOURNEY") to establish a clear information hierarchy.

## Layout & Spacing

The layout follows a **Fixed-Width Grid** for desktop to maintain premium control over whitespace, transitioning to a fluid stack for mobile.

### Layout Principles
- **The Bento Grid:** Business units and case studies are arranged in a modular grid. Use varying column spans (e.g., 2/3 for primary content, 1/3 for supporting stats) to create visual interest.
- **Timeline Flow:** The corporate journey should be presented as a vertical or horizontal line with significant breathing room between phases, emphasizing the "25-year" heritage.
- **Whitespace:** Use `section-padding` (120px) generously between major content blocks to avoid the "cramped" feel often found in tech websites. 
- **Alignment:** All elements should adhere to a strict 12-column grid. Components within Bento boxes should be center-aligned or top-left aligned consistently.

## Elevation & Depth

This design system avoids heavy drop shadows in favor of **Tonal Layers** and **Low-Contrast Outlines**.

- **Surface Tiers:** The base background is Pure White. Secondary containers (Bento boxes, input fields) use a subtle light gray fill (`#F8FAFC`) with a 1px hairline border in `#E2E8F0`.
- **Ecosystem Glows:** Depth is added through "Ambient Glows." These are large, blurred radial gradients (15-20% opacity) of tech-blue, orange, or teal placed behind containers to signify different SBUs.
- **Interactive States:** On hover, containers should lift slightly using a very soft, high-diffusion shadow (e.g., `0 20px 40px rgba(0,0,0,0.04)`) and a primary-colored border-bottom or accent line.
- **Glassmorphism:** Use sparingly for sticky navigation bars (Backdrop blur: 12px, Opacity: 80% white) to keep the focus on content while scrolling.

## Shapes

The shape language is **Soft and Professional**. It avoids the playfulness of hyper-rounded corners, opting for a precise, "machined" look.

- **Standard Radius:** 0.25rem (4px) for small components like tags and input fields.
- **Container Radius:** 0.75rem (12px) for Bento boxes and cards to give them a distinct but disciplined presence.
- **Buttons:** Primary buttons use a slightly higher radius (8px) to feel more inviting to the touch, but never fully pill-shaped.
- **Separation Lines:** Use thin, 1px horizontal and vertical rules to delineate phases in the timeline, reinforcing the "grid" and "data" aesthetic.

## Components

### Buttons
- **Primary:** Deep Crimson background, white text. Bold Geist font. No icons, or a simple "Arrow Right" on hover.
- **Secondary:** Transparent background, Midnight Navy border (1px), Navy text.
- **Tertiary/Ghost:** Text only with a Deep Crimson underline that appears on hover.

### Bento Cards (SBUs & Use Cases)
- **Structure:** Soft gray background, subtle border, Geist headline, Inter body text. 
- **Categorization:** Each card features a 2px colored top-border corresponding to its ecosystem accent (e.g., Blue for HERA, Teal for konvergence).

### Statistics Banner
- A full-width band with a very light gray background. Large Geist numbers in Deep Crimson, with small Geist labels in Midnight Navy below.

### Timeline Milestones
- Vertical layout for mobile, horizontal for desktop.
- Points on the line are hollow circles that fill with Deep Crimson as the user scrolls to that phase.

### Inputs & Forms
- Minimalist style. No background (pure white), 1px border. On focus, the border changes to Deep Crimson with a 2px outer "halo" of low-opacity Red.

### Data Visualization
- Icons should be "Line Art" style with 1.5px stroke weight. Use Midnight Navy for the main icon body and Deep Crimson for one "accent" stroke within the icon.