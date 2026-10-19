---
name: Sovereign Auth
colors:
  surface: '#faf8ff'
  surface-dim: '#d2d9f4'
  surface-bright: '#faf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f3ff'
  surface-container: '#eaedff'
  surface-container-high: '#e2e7ff'
  surface-container-highest: '#dae2fd'
  on-surface: '#131b2e'
  on-surface-variant: '#464555'
  inverse-surface: '#283044'
  inverse-on-surface: '#eef0ff'
  outline: '#777587'
  outline-variant: '#c7c4d8'
  surface-tint: '#4d44e3'
  primary: '#3525cd'
  on-primary: '#ffffff'
  primary-container: '#4f46e5'
  on-primary-container: '#dad7ff'
  inverse-primary: '#c3c0ff'
  secondary: '#712ae2'
  on-secondary: '#ffffff'
  secondary-container: '#8a4cfc'
  on-secondary-container: '#fffbff'
  tertiary: '#00505f'
  on-tertiary: '#ffffff'
  tertiary-container: '#006a7c'
  on-tertiary-container: '#93e8ff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e2dfff'
  primary-fixed-dim: '#c3c0ff'
  on-primary-fixed: '#0f0069'
  on-primary-fixed-variant: '#3323cc'
  secondary-fixed: '#eaddff'
  secondary-fixed-dim: '#d2bbff'
  on-secondary-fixed: '#25005a'
  on-secondary-fixed-variant: '#5a00c6'
  tertiary-fixed: '#acedff'
  tertiary-fixed-dim: '#4cd7f6'
  on-tertiary-fixed: '#001f26'
  on-tertiary-fixed-variant: '#004e5c'
  background: '#faf8ff'
  on-background: '#131b2e'
  surface-variant: '#dae2fd'
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.025em
  headline-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 38px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 26px
    fontWeight: '600'
    lineHeight: 34px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
    letterSpacing: -0.005em
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0.005em
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.04em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system expresses quiet authority, high-performance capability, and architectural precision. It bridges the trust required for enterprise cloud security with the refined ergonomics of executive-tier creative tools. The user experience is frictionless, deliberate, and immersive.

The aesthetic fuses **Corporate / Modern** discipline with **Glassmorphism** and subtle ambient atmospheric depth:
- **Showcase Canvas:** Rich, deep, immersive slate and midnight indigo balanced with disciplined violet luminescence. It conveys intelligence, infrastructure stability, and technical prestige without resorting to playful or juvenile tropes.
- **Form Ergonomics:** Pristine, distraction-free clarity. The authentication side utilizes hyper-readable typography, crisp micro-borders, tactile interactive elements, and multi-layered diffused ambient shadows to deliver instant cognitive ease.

## Colors

The palette balances clinical precision on the operational canvas with atmospheric resonance on the showcase panel.

- **Primary (`#4F46E5` - Electric Indigo):** The primary driver of visual action, focused state rings, brand identifiers, and primary conversion buttons.
- **Secondary (`#7C3AED` - Deep Violet):** Utilized for directional accents, premium indicators, ambient gradient mesh undertones, and interactive highlights on dark surfaces.
- **Tertiary (`#06B6D4` - Cyber Cyan):** An acute functional accent used sparingly for telemetry badges, active session pins, and security encryption check indicators.
- **Neutral (`#0F172A` - Deep Obsidian Slate):** Grounds the typography, high-contrast borders, and deep structural surfaces across the platform.

### Functional Roles & Surface Tone Architecture
- **Interactive Background (Form Side):** Crisp base `#FFFFFF` paired with subtle canvas tint `#F8FAFC`.
- **Showcase Background:** Deep multi-stop gradient spanning from `#0B0F19` through `#0F172A` down into `#1E1B4B`, overlaid with 12% violet-indigo radial light sources.
- **Text Hierarchies:**
  - High Emphasis: `#0F172A` (Light mode) / `#F8FAFC` (Dark showcase)
  - Medium Emphasis: `#475569` (Light mode) / `#94A3B8` (Dark showcase)
  - Subtle / Muted: `#94A3B8` (Light mode) / `#64748B` (Dark showcase)
- **Validation Signals:** Error `#E11D48` (Crimson Rose), Success `#10B981` (Emerald), Alert `#F59E0B` (Amber).

## Typography

The type system pairs **Plus Jakarta Sans** for expressive, geometric, modern display headings with **Inter** for dense, neutral, highly legible system body copy and authentication controls.

- **Headlines:** Set in Plus Jakarta Sans with deliberate negative tracking (`-0.01em` to `-0.025em`) to impart a tailored editorial presence that counters generic software aesthetics.
- **Data & Interaction:** Set in Inter with optical kerning enabled. Form labels, assistive captions, input values, and button actions maintain balanced line-heights to eliminate layout shifting during state mutations (e.g., error string appearance).
- **Tabular Numerals:** For authentication countdowns, verification passcodes, and security keys, enable `font-feature-settings: "tnum"` to maintain strict vertical alignment.

## Layout & Spacing

The layout model is anchored on an asymmetric 2-column split configuration:
- **Desktop (>= 1024px):** A 50/50 or 45/55 fixed split screen.
  - **Left / Showcase Column:** Anchored, full viewport height (`100vh`), housing branding, dynamic environmental graphics, feature telemetry, and client proof badges.
  - **Right / Form Column:** Centered flex-column container with a constrained max content width of `440px`, ensuring high focus and scanning speed.
- **Tablet (768px - 1023px):** Compact 40/60 split, where the showcase column reduces visual flourishes to prioritize form ergonomics while retaining brand stature.
- **Mobile (< 768px):** Collapses into a single stacked column. The showcase panel collapses into a compact navigation brand header (displaying logo and secure SSL indicator), yielding primary viewport real estate to the authentication form.

Layout rhythms follow a strict 4px/8px modular scale. Component stacks strictly preserve vertical rhythm using `space-md` between form inputs and `space-xl` between logical semantic clusters (e.g., header, credential fields, alternate SSO flows, legal disclaimers).

## Elevation & Depth

Visual hierarchy uses diffused, tinted light attenuation rather than heavy muddy drop-shadows. Depth signals status and interactivity without breaking layout structure.

- **Level 0 (Flat Canvas):** Neutral background `#FFFFFF` or `#F8FAFC` for high optical contrast.
- **Level 1 (Form Inputs & Idle States):**
  - Shadow: `0px 1px 2px rgba(15, 23, 42, 0.05)`
  - Border: Subtle 1px solid `#E2E8F0`
- **Level 2 (Hovered Inputs & Active Cards):**
  - Shadow: `0px 4px 12px -2px rgba(79, 70, 229, 0.08), 0px 2px 4px -1px rgba(15, 23, 42, 0.04)`
  - Border: 1px solid `#CBD5E1`
- **Level 3 (Focused Interactive Controls & Primary Buttons):**
  - Shadow: `0px 10px 24px -4px rgba(79, 70, 229, 0.25), 0px 4px 8px -2px rgba(79, 70, 229, 0.15)`
  - Focus Ring: `0 0 0 4px rgba(79, 70, 229, 0.15)` with a 1px inner boundary of `#4F46E5`.
- **Level 4 (Showcase Glass Overlay Cards & Floats):**
  - Background: `rgba(15, 23, 42, 0.65)`
  - Backdrop Filter: `blur(16px) saturate(180%)`
  - Border: 1px solid `rgba(255, 255, 255, 0.1)`
  - Shadow: `0px 20px 40px -8px rgba(0, 0, 0, 0.5)`

## Shapes

The geometric framework is categorized as **Rounded** (`roundedness: 2`), yielding controlled precision and warm accessibility:

- **Base Radius (Inputs, Standard Buttons, Alert Banners):** `0.5rem` (8px). This creates balanced corners that match the stroke weight and visual density of standard typography.
- **Large Radius (Cards, Dropdowns, Modal Dialogs, Floating Showcase Panels):** `1rem` (16px).
- **Extra Large Radius (Outer Shells, Contextual Callouts):** `1.5rem` (24px).
- **Pill Radius (`9999px`):** Reserved exclusively for status indicators, MFA badges, and environmental category chips.

## Components

### Buttons
- **Primary CTA:** Solid `#4F46E5` fill with pure white typography (`label-lg`). Height `48px`. Padding: `0 1.5rem`. Smooth hover transition to `#4338CA` with Level 3 elevation glow. Disabled state: `#F1F5F9` background with `#94A3B8` text, no pointer events.
- **Secondary / Social SSO (e.g., Google, GitHub, Okta, SAML):** Background `#FFFFFF`, 1px solid `#E2E8F0`, text color `#0F172A` (`label-lg`). Height `48px`. Hover adds Level 1 elevation and border color `#CBD5E1`.
- **Tertiary / Text Link:** Transparent background, text `#4F46E5` with semi-bold weight. Focus visible via outline. Underline appears solely on hover.

### Input Fields
- **Container:** Height `48px`, shape radius `8px`, base border 1px solid `#E2E8F0`, background `#FFFFFF`. Padding: `0 1rem`.
- **Typography:** `body-md` in `#0F172A`. Placeholder text in `#94A3B8`.
- **Labeling:** Floating or top-aligned `label-md` in `#334155`, tracking `0.02em`, 6px above the field.
- **Focus State:** Border shifts to `#4F46E5` with an outer ring: `0 0 0 3px rgba(79, 70, 229, 0.12)`.
- **Error State:** Border shifts to `#E11D48`, accompanied by an error text string in `body-sm` with a 16px alert icon below the container.
- **Addornments:** Password eye toggle, security status check, and single-click clear icons use a 20px dimension, styled in `#64748B` with hover state shifting to `#0F172A`.

### Checkboxes & Radios
- **Checkbox:** `18px x 18px` box, `4px` radius. Border 1.5px solid `#CBD5E1`. On checked: `#4F46E5` fill with a crisp white centered check mark.
- **Radio:** `18px x 18px` circular shell. On checked: concentric 6px solid `#4F46E5` circle.
- **Alignment:** Aligned with top line of associated body text.

### Chips & Badges
- **Security / SSO Status Chip:** Height `24px`, pill-shaped (`roundedness: 9999px`), padding `0 0.625rem`. Background: `rgba(79, 70, 229, 0.08)`, text `#4F46E5` in `label-sm`.
- **Showcase Feature Badge:** On dark glass, background: `rgba(255, 255, 255, 0.1)`, text: `#F8FAFC`, backdrop blur `8px`.

### Cards & Showcase Panels
- **Testimonial / Trust Metric Card (Showcase Side):** Floating glass layer with `rounded-lg` (16px), background `rgba(15, 23, 42, 0.65)`, border `1px solid rgba(255, 255, 255, 0.12)`. Internal padding `space-lg`.
- **MFA / Dual-Factor Passcode Card:** Inset nested grouping with `#F8FAFC` background, `rounded-md` (8px), and 1px border `#E2E8F0`.

### Dividers & Separators
- **Horizontal Splitter (e.g., "or continue with"):** 1px solid `#E2E8F0` with a centered `body-sm` text block anchored over `#FFFFFF`, color `#64748B`, uppercase tracking `0.05em`.