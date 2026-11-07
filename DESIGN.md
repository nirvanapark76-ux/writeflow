---
name: WriteFlow Administrative Suite
colors:
  surface: '#f9f9ff'
  surface-dim: '#d3daef'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f1f3ff'
  surface-container: '#e9edff'
  surface-container-high: '#e1e8fd'
  surface-container-highest: '#dce2f7'
  on-surface: '#141b2b'
  on-surface-variant: '#444651'
  inverse-surface: '#293040'
  inverse-on-surface: '#edf0ff'
  outline: '#757682'
  outline-variant: '#c5c5d3'
  surface-tint: '#4059aa'
  primary: '#00236f'
  on-primary: '#ffffff'
  primary-container: '#1e3a8a'
  on-primary-container: '#90a8ff'
  inverse-primary: '#b6c4ff'
  secondary: '#006a61'
  on-secondary: '#ffffff'
  secondary-container: '#86f2e4'
  on-secondary-container: '#006f66'
  tertiary: '#4b1c00'
  on-tertiary: '#ffffff'
  tertiary-container: '#6e2c00'
  on-tertiary-container: '#f39461'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dce1ff'
  primary-fixed-dim: '#b6c4ff'
  on-primary-fixed: '#00164e'
  on-primary-fixed-variant: '#264191'
  secondary-fixed: '#89f5e7'
  secondary-fixed-dim: '#6bd8cb'
  on-secondary-fixed: '#00201d'
  on-secondary-fixed-variant: '#005049'
  tertiary-fixed: '#ffdbcb'
  tertiary-fixed-dim: '#ffb691'
  on-tertiary-fixed: '#341100'
  on-tertiary-fixed-variant: '#773205'
  background: '#f9f9ff'
  on-background: '#141b2b'
  surface-variant: '#dce2f7'
typography:
  display-metric:
    fontFamily: Noto Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  display-metric-mobile:
    fontFamily: Noto Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Noto Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Noto Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Noto Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Noto Sans
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Noto Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Noto Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Noto Sans
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
  label-md:
    fontFamily: Noto Sans
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
  label-sm:
    fontFamily: Noto Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
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
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.25rem
  space-xl: 1.5rem
---

## Brand & Style

This design system targets language institute directors, academic administrators, and instructors aged 30 to 50 who handle high-volume grading, curriculum monitoring, and institutional metrics. The primary objective is cognitive decompression: reducing operational friction while establishing an aura of institutional credibility, pedagogical precision, and technological discretion.

The aesthetic follows **Corporate / Modern** principles tempered by minimalist restraint:
- **Calm, High-Clarity Canvas:** Interfaces favor structured hierarchy over decorative visual effects.
- **Academic Authority:** Deep indigo delivers executive gravitas, balanced by measured teal accents that celebrate pedagogical milestones and successful AI-assisted workflows.
- **Utilitarian Balance:** Predictable information pathways, high-legibility contrasts, and distinct spatial zoning reduce errors during rapid administrative tasks.

## Colors

The palette establishes a deliberate institutional hierarchy designed for high data density without cognitive fatigue.

### Palette Implementation
- **Primary (`#1E3A8A` - Deep Indigo):** Anchor color for administrative hierarchy, selected navigation anchors, active state fills, key primary CTAs, and structural accents.
- **Secondary (`#0D9488` - Teal Green):** Applied selectively to indicate positive academic outcomes, completion rates, AI evaluation confirmations, and real-time operational status.
- **Canvas & Surface Tiers:**
  - Base Application Canvas: `#F3F4F6` (Cool Clean Gray) creates separation from interactive modules.
  - Card & Container Surfaces: `#FFFFFF` (Pure White) provides clean data planes with strict optical containment.
  - Subsurface / Table Header Tint: `#F8FAFC` maintains legibility across multi-column data spreads.
- **Typography & Text Contrast:**
  - High-Emphasis Heading & Metrics: `#111827` (Dark Charcoal).
  - Primary Body & Table Content: `#2D3748` (Slate).
  - Supporting Metadata & Captions: `#64748B` to `#6B7280`.
- **Structural Outlines:**
  - Borders and horizontal dividers rely on crisp, neutral borders (`#E2E8F0` and `#E5E7EB`) to define clear boundaries without visually cluttering tables and dashboards.

## Typography

The typography scale utilizes **Noto Sans**, ensuring cross-platform parity between East Asian (Korean) and Latin glyphs across diverse desktop browsers.

- **Numerics and Key Performance Indicators:** Large administrative statistics prioritize numeric clarity via tabular figure features (`tnum`), preventing horizontal shifting during live data refreshes.
- **Hierarchy Separation:** Section titles leverage bold weights (`700`) paired with reduced letter-spacing (`-0.02em`) to anchor dashboards. Body text relies on weight `400` with generous line-heights (`1.45` to `1.5`) to preserve readability across extended essay-grading viewports.
- **Labels & Status Pills:** Component labels favor medium and semibold weights (`500`-`600`) at `12px` to `14px`, keeping secondary operational signals crisp and legible.

## Layout & Spacing

The layout is built around a persistent, fixed-width navigational rail (`260px`) accompanied by a fluid main administrative canvas designed for standard 12-column layouts.

### Screen Adaptability
- **Desktop (1280px and above):** 12-column layout with fixed navigation rail. The metric card grid spans 3 or 4 uniform columns with `1.5rem` gutters (`24px`). Internal card padding maintains a spacious `1.25rem` to `1.5rem` (20–24px) for clear breathing room.
- **Tablet (768px – 1279px):** Sidebar condenses to an icon-led slim rail (`72px`) or auto-collapsing drawer. Grid shifts to 6 columns; metric cards reflow into 2x2 modular blocks.
- **Mobile (< 768px):** Navigation transitions to a top navigation bar with a slide-out drawer. Dashboard metrics stack into single or dual columns with `1rem` outer canvas padding and `1rem` horizontal gutters.

## Elevation & Depth

This system avoids heavy drop shadows and exaggerated glassmorphism, instead using **low-contrast outlines combined with shallow ambient shadows** to establish physical structure.

### Elevation Hierarchy
- **Canvas Base (Level 0):** `#F3F4F6` background. Flat, non-elevated.
- **Resting Panels & Cards (Level 1):** Solid `#FFFFFF` fill bounded by a continuous `1px` solid border (`#E2E8F0`), supported by an ambient shadow: `0 1px 3px 0 rgba(0, 0, 0, 0.05), 0 1px 2px -1px rgba(0, 0, 0, 0.04)`.
- **Dropdowns & Popovers (Level 2):** Layered above resting cards with a defined boundary border (`#E2E8F0`) and focused ambient elevation: `0 4px 6px -1px rgba(0, 0, 0, 0.07), 0 2px 4px -2px rgba(0, 0, 0, 0.05)`.
- **Modals & Overlays (Level 3):** Modal containers use an intensified ambient boundary: `0 20px 25px -5px rgba(0, 0, 0, 0.08), 0 8px 10px -6px rgba(0, 0, 0, 0.04)`, underpinned by an overlay scrim (`rgba(17, 24, 39, 0.4)`).

## Shapes

The interface embraces a balanced curvature profile (**Level 2 - Rounded**), blending clean lines with inviting, accessible softness.

- **Standard Cards & Containers:** Radii remain consistent between `10px` and `12px`, eliminating blunt industrial edges while keeping data boundaries crisp.
- **Interactive Controls (Inputs, Standard Buttons):** Form elements and actions maintain an `8px` (`0.5rem`) radius.
- **Status Badges, Filter Pills, and Avatars:** Fully rounded pill forms (`9999px`) to differentiate interactive chips and state indicators from rectangular content cards.

## Components

### Buttons
- **Primary:** Background `#1E3A8A`, text `#FFFFFF`, radius `8px`, vertical padding `10px`, horizontal padding `16px`. Active/Hover: `#172554`. Focus state displays an outer ring (`2px` solid `#93C5FD`, `2px` offset).
- **Secondary / Success Action:** Background `#0D9488`, text `#FFFFFF`, radius `8px`. Active/Hover: `#0F766E`.
- **Outline / Ghost:** Background `transparent`, border `1px solid #E2E8F0`, text `#2D3748`. Hover: `#F8FAFC`.

### Metric & Stats Cards
- **Structure:** `#FFFFFF` background, `1px solid #E2E8F0`, corner radius `12px`, padding `20px` to `24px`.
- **Internal Stack:** Card title and icon in muted slate (`#64748B`, `13px Regular`) positioned at the top; large metric readout (`#111827`, `36px-40px Bold`) centered; contextual growth badge or trend text anchored at the base.

### Navigation Sidebar
- **Background:** `#FFFFFF` with a trailing `1px solid #E2E8F0` right border.
- **Active Navigation Item:** Solid Deep Indigo background accent (`#1E3A8A`) or soft tint background (`#EFF6FF`) with deep indigo text (`#1E3A8A`, `600` weight) paired with a bold left-edge border indicator (`3px solid #1E3A8A`).
- **Inactive Items:** Neutral text (`#64748B`), hover shifts to background `#F1F5F9` and text `#1E3A8A`.

### Status Badges & Chips
- **Success / Completed:** Pill shape (`9999px`), background `#CCFBF1`, text `#0F766E`, font size `12px`, weight `600`, padding `4px 10px`.
- **In Review / AI Processing:** Background `#FEF3C7`, text `#92400E`.
- **Pending / Inactive:** Background `#F1F5F9`, text `#475569`.

### Data Tables
- **Header:** Background `#F8FAFC`, uppercase label style (`12px`, weight `600`, text `#64748B`), padding `12px 16px`, subtle bottom divider `1px solid #E2E8F0`.
- **Body Rows:** Background `#FFFFFF`, padding `16px`, bottom divider `1px solid #F1F5F9`. Hover state shifts cleanly to `#F8FAFC`.
- **Numeric & Metric Alignment:** Essay scores, completion rates, and timestamps remain strictly right-aligned with tabular numerals enabled.

### Form Inputs & Select Controls
- **Field Wrapper:** Height `40px`, border `1px solid #CBD5E1`, background `#FFFFFF`, radius `8px`, typography `14px Regular` (`#111827`), placeholder text `#94A3B8`.
- **Focus State:** Border changes to `#1E3A8A` with a subtle box-shadow ring: `0 0 0 3px rgba(30, 58, 138, 0.12)`.