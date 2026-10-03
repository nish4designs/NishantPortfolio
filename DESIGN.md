---
name: Logistics Control Tower
colors:
  surface: '#f8f9ff'
  surface-dim: '#cbdbf5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d3e4fe'
  on-surface: '#0b1c30'
  on-surface-variant: '#45464d'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#76777d'
  outline-variant: '#c6c6cd'
  surface-tint: '#565e74'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#131b2e'
  on-primary-container: '#7c839b'
  inverse-primary: '#bec6e0'
  secondary: '#9d4300'
  on-secondary: '#ffffff'
  secondary-container: '#fd761a'
  on-secondary-container: '#5c2400'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#002113'
  on-tertiary-container: '#009668'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dae2fd'
  primary-fixed-dim: '#bec6e0'
  on-primary-fixed: '#131b2e'
  on-primary-fixed-variant: '#3f465c'
  secondary-fixed: '#ffdbca'
  secondary-fixed-dim: '#ffb690'
  on-secondary-fixed: '#341100'
  on-secondary-fixed-variant: '#783200'
  tertiary-fixed: '#6ffbbe'
  tertiary-fixed-dim: '#4edea3'
  on-tertiary-fixed: '#002113'
  on-tertiary-fixed-variant: '#005236'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  headline-xl:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 30px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
    letterSpacing: -0.01em
  stat-metric:
    fontFamily: Inter
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.02em
  body-lg:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '500'
    lineHeight: 22px
  body-md:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  label-caps:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.06em
  label-status:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.04em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  margin: 1.5rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 0.75rem
  space-lg: 1.25rem
  space-xl: 1.75rem
---

## Brand & Style

This design system embodies modern enterprise clarity, high operational precision, and mission-critical ergonomics. Designed for end-to-end supply chain monitoring, automated logistics visibility, and rapid incident resolution, the aesthetic merges functional corporate utility with refined modern SaaS clarity.

The visual language follows a disciplined minimalist and low-contrast bordered structure. It rejects heavy drop shadows, flashy ornamentation, and distracting high-saturation backgrounds in favor of pristine crisp lines, structured white telemetry cards, high-contrast data metrics, and semantically tinted warning indicators. Micro-accents in warm coral, amber alert tones, and stable emeralds guide operator attention instantly toward throughput anomalies, bottlenecks, and gatehouse queues without visual fatigue during high-tempo monitoring sessions.

## Colors

The palette is engineered for high data legibility, low visual friction, and actionable status hierarchies:

- **Primary (`#0f172a`):** Deep slate-black used for prominent metric figures, major headings, bold structural titles, and high-emphasis active navigation icons.
- **Secondary (`#f97316` / `#ea580c` / `#ef4444`):** Warm amber, orange, and coral spectrum reserved for variances, bottleneck risks, critical lead times, and urgency indicators.
- **Tertiary (`#10b981` / `#059669`):** Emerald green indicating positive health, fulfilled target ratios, normal throughput states, and cleared queues.
- **Neutral (`#64748b` / `#94a3b8`):** Balanced cool slate tones used for secondary metrics, descriptive labels, baseline targets, and subheadings.
- **Background & Canvas (`#f8fafc` / `#ffffff`):** Soft, cool off-white app canvas hosting pure white container cards.
- **Structural Outlines (`#e2e8f0` / `#eaecf0`):** Ultra-crisp 1px hair-line borders providing definition for metric cards, table grids, buttons, and control panels.

## Typography

Typography relies entirely on the precise, neutral mechanics of **Inter**. 

- **Key Performance Figures (`stat-metric`):** Bold, dense, high-contrast numeric values configured with tabular lining numbers to ensure instant scanning across dashboard cards.
- **Section & Column Titles (`label-caps`):** Rendered in compact all-caps with generous tracking (`0.06em`) and medium/semibold weight for domain groupings, table headers, and metric titles.
- **Data & Tables (`body-md` / `body-sm`):** Optimized for high-density information layouts. High letter-contrast maintains crisp rendering even on high-DPI monitoring displays.

## Layout & Spacing

The layout model is built on an asymmetric telemetry grid designed for high operational control:
- **Navigation Rail:** A fixed 220px vertical sidebar housing top-level workflow views and contextual navigation items.
- **Main Canvas:** A responsive fluid workspace segmented into a standardized 12-column subgrid. 
  - Top tier: 5 uniform single-metric KPI cards spanning the full width.
  - Middle tier: Mixed 4-column modules showcasing trend lines, gatehouse capacity, and distribution bars.
  - Bottom tier: 8-column primary process worklist paired with a dedicated 4-column critical action sidebar panel.
- **Spacing Rhythm:** Standard 8px increment baseline scale. Compact inner-padding within cards (`1.25rem`) maximizes visible data density while preserving breathing room between distinct analytical clusters.

## Elevation & Depth

Visual hierarchy in this system relies on low-contrast outlines and flat tonal nesting rather than heavy physical drop shadows:

- **Border Definition:** Primary containers use a uniform, hairline 1px border (`#e2e8f0` or `#eaecf0`) set against `#ffffff` surfaces.
- **Elevation Layers:**
  - **Base Canvas:** Flat, pale matte background (`#f8fafc`).
  - **Surface Tier 1 (Cards, Worksheets):** White background (`#ffffff`), 1px outline (`#eaecf0`), no elevation blur.
  - **Surface Tier 2 (Action Panels & Callouts):** Tinted light fills (e.g. `#f8fafc` or pale amber `#fffbeb`) bordered with subtle accent lines.
  - **Overlays & Menus:** Crisp white surface with an ambient, diffused shadow: `0 4px 16px -2px rgba(15, 23, 42, 0.06)`, framed by a crisp `#e2e8f0` border.

## Shapes

The design system incorporates geometric balance through refined intermediate curvature:

- **Metric & Content Cards:** Constructed with smooth outer radii (`1rem` / 16px to `1.25rem` / 20px) to soften dense data screens while retaining precise grid alignment.
- **Controls & Interactive Elements:** Filter buttons, interactive chips, and dropdown triggers use pill profiles or soft radii (8px–10px) to differentiate actionable triggers from static analytical cards.
- **Status Dots & Indicators:** True circles (50% border-radius) paired with uppercase alphanumeric tags.

## Components

### Buttons & Interactive Controls
- **Secondary / Action Buttons:** Clean white background, 1px border (`#cbd5e1`), subtle dark text (`#0f172a`), 8px border-radius, horizontal padding `12px 16px`. Active state transitions smoothly to `#f1f5f9`.
- **Action Highlight Buttons:** Soft blue/neutral fill (`#f0f9ff` or `#eff6ff`) with matching borders (`#bae6fd`) and rich primary text for high-priority operational workflows.
- **Filter Pills & Dropdowns:** Pill-shaped capsules with left-aligned icons, light borders, subtle chevrons, and active dropdown indicator states.

### Data Tables & Worklists
- **Header Row:** Crisp 11px uppercase labels (`#64748b`), minimal height, no background tint, bordered bottom with a continuous 1px divider.
- **Data Rows:** Alternating hover highlight (`#f8fafc`), generous vertical padding (`12px`), with prominent domain badges in warm amber/brown (`#b45309`) and monospaced or semibold node titles.
- **Table Action Buttons:** Compact ghost-outline buttons (`Open Gate B`) aligned flush right on each data row.

### Status Indicators & Badges
- **Live Status Dots:** Inline 6px circular indicators:
  - *Critical:* `#ef4444` dot with uppercase red text.
  - *Warning:* `#f97316` dot with uppercase amber text.
  - *Stable:* `#10b981` dot with uppercase emerald text.
- **Metric Variance Tags:** Pill badges with soft pastel fills and saturated text (e.g., `#ffedd5` background with `#c2410c` text for `+1.2d Variance`).

### Navigation Tabs
- **Underline Style Tabs:** Minimalist text buttons without backgrounds. Active tab features bold primary font (`#0f172a`) paired with a sharp 2px solid bottom bar, while inactive tabs remain muted neutral (`#64748b`).

### Action & Escalation Panels
- **Incident Cards:** Light-bordered container featuring contextual alert icons, clear incident root-cause documentation, and grouped secondary CTA buttons (`Expedite Freight`, `Re-route Shipment`).