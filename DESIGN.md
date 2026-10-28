---
name: Modern Freight & Trade Orchestration
colors:
  surface: '#f5faff'
  surface-dim: '#cedce6'
  surface-bright: '#f5faff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#e9f5ff'
  surface-container: '#e2f0fa'
  surface-container-high: '#dceaf4'
  surface-container-highest: '#d7e4ef'
  on-surface: '#101d24'
  on-surface-variant: '#3e484d'
  inverse-surface: '#25323a'
  inverse-on-surface: '#e5f3fd'
  outline: '#6e797e'
  outline-variant: '#bdc8ce'
  surface-tint: '#006780'
  primary: '#00647c'
  on-primary: '#ffffff'
  primary-container: '#007f9d'
  on-primary-container: '#fafdff'
  inverse-primary: '#6cd3f7'
  secondary: '#006b5f'
  on-secondary: '#ffffff'
  secondary-container: '#6df5e1'
  on-secondary-container: '#006f64'
  tertiary: '#006577'
  on-tertiary: '#ffffff'
  tertiary-container: '#008096'
  on-tertiary-container: '#f9fdff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#b7eaff'
  primary-fixed-dim: '#6cd3f7'
  on-primary-fixed: '#001f28'
  on-primary-fixed-variant: '#004e61'
  secondary-fixed: '#71f8e4'
  secondary-fixed-dim: '#4fdbc8'
  on-secondary-fixed: '#00201c'
  on-secondary-fixed-variant: '#005048'
  tertiary-fixed: '#acedff'
  tertiary-fixed-dim: '#4cd7f6'
  on-tertiary-fixed: '#001f26'
  on-tertiary-fixed-variant: '#004e5c'
  background: '#f5faff'
  on-background: '#101d24'
  surface-variant: '#d7e4ef'
  surface-canvas: '#F8FAFC'
  surface-card: '#FFFFFF'
  petroleum-deep: '#06131A'
  petroleum-card: '#0A1F2B'
  petroleum-border: '#163345'
  status-active: '#00E59B'
  status-alert: '#F43F5E'
  border-subtle: '#E2E8F0'
typography:
  display-hero:
    fontFamily: Plus Jakarta Sans
    fontSize: 3.5rem
    fontWeight: '800'
    lineHeight: 4.25rem
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 2.25rem
    fontWeight: '800'
    lineHeight: 2.75rem
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 2.5rem
    fontWeight: '700'
    lineHeight: 3rem
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.75rem
    fontWeight: '700'
    lineHeight: 2.25rem
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.75rem
    fontWeight: '600'
    lineHeight: 2.25rem
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.25rem
    fontWeight: '600'
    lineHeight: 1.75rem
  stat-display:
    fontFamily: Plus Jakarta Sans
    fontSize: 3rem
    fontWeight: '800'
    lineHeight: 3.25rem
    letterSpacing: -0.03em
  body-lg:
    fontFamily: Inter
    fontSize: 1.125rem
    fontWeight: '400'
    lineHeight: 1.875rem
  body-md:
    fontFamily: Inter
    fontSize: 1rem
    fontWeight: '400'
    lineHeight: 1.625rem
  body-sm:
    fontFamily: Inter
    fontSize: 0.875rem
    fontWeight: '400'
    lineHeight: 1.375rem
  label-md:
    fontFamily: Inter
    fontSize: 0.875rem
    fontWeight: '600'
    lineHeight: 1.25rem
    letterSpacing: 0.01em
  label-code:
    fontFamily: JetBrains Mono
    fontSize: 0.75rem
    fontWeight: '500'
    lineHeight: 1rem
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
  space-xs: 0.375rem
  space-sm: 0.75rem
  space-md: 1.25rem
  space-lg: 2rem
  space-xl: 3rem
---

## Brand & Style

This design system establishes a high-precision, digital-first aesthetic tailored for next-generation global logistics, freight management, and international customs clearance. Rooted in structural clarity, technological velocity, and enterprise trust, the visual language balances the calculated rigor of industrial enterprise software with the fluidity and polish of modern SaaS.

The visual style synthesizes **high-tech enterprise minimalism** with **subtle glassmorphism** and structured **Bento-grid modularity**:
- **Structured Precision:** High-density data displays, crisp metric callouts, and clean micro-borders provide clear operational visibility across complex multimodal supply chains.
- **Atmospheric Depth:** Deep maritime petroleum tones anchor the primary operational canvas, accented by refractive, frosted translucent surfaces that introduce depth without visual noise.
- **RTL-Native Ergonomics:** Built specifically for Persian (Farsi) typography and bidirectional RTL/LTR data sets, prioritizing balanced horizontal rhythm, uncompromised baseline alignments, and smooth scanning patterns for enterprise logistics teams.

## Colors

The palette merges coastal marine authority with electric digital signals:
- **Primary (`#0891B2`) & Vibrant Cyan (`#06B6D4`):** The operational core. Used for interactive states, key track-and-trace progress indicators, vessel status badges, and critical action triggers.
- **Secondary Teal (`#14B8A6`):** Supporting technical accents, secondary graphs, micro-metrics, and contextual confirmations.
- **Deep Navy Petroleum (`#06131A`):** The primary neutral baseline. Functions as both the deep contrast anchor for dark-mode command modules, complex Bento dashboards, and the deep foreground color for ultra-crisp typography in light mode.
- **Clean Light Surface (`#F8FAFC` & `#FFFFFF`):** High-efficiency neutral background canvas providing maximum readability for tabular data, bill-of-lading documents, and shipment analytics.
- **Functional Semantics:** `#00E59B` (In-Transit / Cleared Customs), `#F43F5E` (Port Delay / Exception), `#F59E0B` (Awaiting Documentation).

In dark-theme components and Bento cards, surfaces step up into `#0A1F2B` layered with 1px structural borders tinted with cyan-white translucence (`rgba(255, 255, 255, 0.08)`).

## Typography

This system implements a strict bidirectional typographic architecture:
- **Persian Text Rendering:** In Persian RTL mode, the primary typography stack maps headlines, titles, and body copy directly to **Yekan Bakh** (with weights ExtraBold for hero displays, Bold for section headers, Medium for UI labels, and Regular for descriptions/tables). Letter-spacing is set to `0` or slightly positive for Persian text to preserve glyph continuity.
- **Latin & Numerical Rendering:** In LTR context, **Plus Jakarta Sans** provides geometric modernism and authoritative punch for corporate headlines and metrics, while **Inter** delivers neutral, highly legible reading comfort for documentation, customs forms, and manifests.
- **Telemetry & Manifest Identifiers:** **JetBrains Mono** is reserved strictly for tracking numbers (BL, AWB, Container IDs, HS Codes, IMO numbers), coordinates, and timestamp logs, ensuring monospaced visual structure across tables.
- **Persian Numerals:** In financial and quantitative displays, tabular Persian numerals are enforced to maintain alignment inside Bento grid metric cards.

## Layout & Spacing

The structural layout utilizes a balanced **12-column Bento Grid framework** capable of housing diverse operational widgets, route-map views, and metric hubs:
- **Grid Architecture:** Desktop views span a 12-column grid with `1.5rem` gutters and a maximum canvas width of `1440px`. Mobile viewports compress to a fluid 4-column stack with `1rem` gutters and `1.25rem` outer margins.
- **Bento Hierarchy:** Bento containers follow a 1:1, 2:1, 2:2, or 3:1 column-span hierarchy. Spacing inside Bento modules relies strictly on `space-md` (`1.25rem`) and `space-lg` (`2rem`) to give high-density charts and operational counters room to breathe.
- **RTL Fluidity:** Padding, inset directions, and flex arrangements invert automatically in RTL mode (`direction: rtl`). Start/End logical properties (`padding-inline-start`, `margin-inline-end`) ensure smooth directional symmetry between Persian and English interfaces.

## Elevation & Depth

Visual hierarchy does not rely on heavy drop shadows; instead, it uses **tonal layering**, **1px crisp borders**, and **frosted glassmorphism**:
- **Surface Level 0 (Base Canvas):** Light Mode `#F8FAFC` / Dark Navy Petroleum `#06131A`.
- **Surface Level 1 (Bento Cards & Panels):** Light Mode `#FFFFFF` with a 1px border of `#E2E8F0` / Dark Mode `#0A1F2B` with a 1px border of `rgba(255, 255, 255, 0.08)`.
- **Surface Level 2 (Glassmorphism Accents & Floating Panels):** Background set to `rgba(255, 255, 255, 0.75)` in light mode, or `rgba(10, 31, 43, 0.65)` in dark petroleum sections, reinforced with `backdrop-filter: blur(16px)` and an inner highlight rim of `inset 0 1px 0 rgba(255, 255, 255, 0.2)`.
- **Shadow Signature:** Ambient and dispersed. Cards use `0 4px 24px -2px rgba(6, 19, 26, 0.04), 0 1px 2px -1px rgba(6, 19, 26, 0.02)`. Floating overlays and modal drawers introduce focused elevation with `0 20px 48px -8px rgba(6, 19, 26, 0.16)`.

## Shapes

The geometric identity is defined by large, confident curves balancing technical precision:
- **Cards and Bento Modules:** Use `1rem` to `1.5rem` (`rounded-2xl` equivalent) for an inviting, modern structural frame.
- **Interactive Controls:** Buttons, input shells, dropdowns, and segmented filters adopt `0.75rem` (`12px`) corner radius, ensuring distinct separation from outer container shapes.
- **Pills and Indicators:** Status chips, tracking state pills, and category tags utilize full capsule radius (`9999px`).
- **Dividers & Strokes:** Structural separation lines use crisp 1px strokes with 0px radius, anchoring the soft outer rounded corners with rigid internal discipline.

## Components

### Buttons
- **Primary Action:** Solid `#0891B2` with white text. Hover transitions to `#06B6D4` with a subtle cyan glow (`0 0 20px rgba(6, 182, 212, 0.35)`). Active state scales slightly to `0.98`.
- **Secondary (Petroleum Glass):** In dark modules, `rgba(255, 255, 255, 0.06)` background, white text, 1px border of `rgba(255, 255, 255, 0.15)`. In light modules, `#F1F5F9` background, `#06131A` text.
- **Ghost:** Transparent background with `#0891B2` label and icon; hover injects `rgba(8, 145, 178, 0.08)`.

### Bento Cards & Stat Displays
- **Stat Modules:** Bold vertical rhythm featuring a small `label-code` category header, followed by an oversized `stat-display` numerical value, and anchored by a trending delta badge (`+14.2%` with a subtle green pill container).
- **Glass Highlight Tiles:** Accent tiles that sit over dark petroleum canvas use subtle linear gradients from `rgba(8, 145, 178, 0.15)` to `transparent`, framed by high-precision semi-transparent borders.

### Input Fields & Search Bars
- **Tracking & Freight Input:** Elevated search shell with `space-sm` internal padding, `0.75rem` corner radius, and integrated prefix icon (container, vessel, or airway bill icon).
- **Focus State:** 1px border transition from `#E2E8F0` to `#0891B2`, backed by a 3px ring of `rgba(8, 145, 178, 0.15)`.

### Chips & Badges
- **Status Indicators:** Pill-shaped with a live pulsing beacon dot (e.g., green dot for `In Transit - On Schedule`).
- **HS Code & Customs Tags:** Compact monospace labels surrounded by low-saturation petroleum borders.

### Lists & Tracking Timelines
- **Logistics Milestones:** Vertical RTL/LTR connecting nodes. Completed legs show filled cyan lines and check icons; pending legs display dashed muted strokes.
- **Table Rows:** Hover state transitions to soft cyan tint (`rgba(8, 145, 178, 0.02)`), with clear divider lines and monospaced alignment for timestamps, weights, and TEU volumes.