---
name: Academic Enterprise Interface
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
  on-surface-variant: '#444653'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#757684'
  outline-variant: '#c4c5d5'
  surface-tint: '#3755c3'
  primary: '#00288e'
  on-primary: '#ffffff'
  primary-container: '#1e40af'
  on-primary-container: '#a8b8ff'
  inverse-primary: '#b8c4ff'
  secondary: '#565e74'
  on-secondary: '#ffffff'
  secondary-container: '#dae2fd'
  on-secondary-container: '#5c647a'
  tertiary: '#002e81'
  on-tertiary: '#ffffff'
  tertiary-container: '#0042b2'
  on-tertiary-container: '#a4b9ff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dde1ff'
  primary-fixed-dim: '#b8c4ff'
  on-primary-fixed: '#001453'
  on-primary-fixed-variant: '#173bab'
  secondary-fixed: '#dae2fd'
  secondary-fixed-dim: '#bec6e0'
  on-secondary-fixed: '#131b2e'
  on-secondary-fixed-variant: '#3f465c'
  tertiary-fixed: '#dbe1ff'
  tertiary-fixed-dim: '#b4c5ff'
  on-tertiary-fixed: '#00174b'
  on-tertiary-fixed-variant: '#003ea8'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 34px
    letterSpacing: -0.015em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: -0.005em
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
    letterSpacing: 0em
  label-md:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.03em
  metric-stat:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 34px
    letterSpacing: -0.02em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 0.75rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style

This design system delivers an authoritative, high-density operational environment engineered for enterprise school administration, academic boards, and executive leadership. It pairs the functional clarity of modern cloud SaaS with the institutional gravitas required for educational governance. 

### Design Philosophy
- **Modern Institutionalism:** An atmosphere of discipline, precision, and trust. The visual tone eliminates decorative noise in favor of data legibility, structured hierarchies, and immediate status recognition.
- **Cognitive Ergonomics:** Designed for high-frequency, all-day operation by registrars, academic coordinators, and treasurers. High visual contrast between structural chrome and interactive controls reduces mental fatigue during intensive record processing.
- **Contextual Integrity:** Tailored natively to Indonesian academic frameworks (e.g., Kurikulum Merdeka, semester evaluations, Dapodik compliance, Tuisi/SPP billing, and complex multi-status attendance tracking).

### Aesthetic Style
A tailored hybrid of **Corporate / Modern** and **Minimalist Utility**. The UI relies on crisp 1px hairpins, subtle slate surface layering, micro-level depth transitions, and deliberate color zoning. Structural panels recede through muted neutral slate backdrops, allowing critical academic KPIs, student rosters, and fiscal status badges to command immediate focus.

## Colors

The color system enforces rigorous functional segregation. Tonal values are split systematically between institutional anchors, administrative surfaces, interactive targets, and institutional status tokens.

### Palette Architecture
- **Primary Navy (`#1E40AF`):** The core institutional identity marker. Used for primary interactive triggers, active navigation items, prominent branding nodes, and focused structural accents.
- **Secondary Deep Slate (`#0F172A` / `#1E293B`):** Structural authority. Applied to global navigational bars, primary data headers, heavy metric numerals, and high-emphasis body text.
- **Tertiary & Interactive Accent (`#2563EB` / `#3B82F6`):** Signals active engagement, interactive text links, selection indicators, and primary data visualization curves.
- **Neutral Canvas & Foundations (`#F8FAFC`, `#F1F5F9`, `#E2E8F0`, `#64748B`):** 
  - Canvas base: `#F8FAFC`
  - Sub-surface/card fills: `#FFFFFF`
  - Structural separators and table grid borders: `#E2E8F0`
  - Inactive/placeholder text and secondary metadata: `#64748B`

### Semantic Academic Status Tokens
Colors must strictly convey regulatory and operational states:
- **Emerald (`#10B981` / Soft Fill `#ECFDF5` / Border `#A7F3D0`):** Success, active status (*Aktif*), completed tuition (*Lunas*), present (*Hadir*).
- **Amber (`#F59E0B` / Soft Fill `#FFFBEB` / Border `#FDE68A`):** In progress, pending approval (*Menunggu Verifikasi*), excused absence (*Izin* / *Sakit*), partial settlement (*Cicilan*).
- **Rose (`#EF4444` / Soft Fill `#FEF2F2` / Border `#FECACA`):** Critical alerts, delinquent payment (*Menunggak*), unexcused absence (*Alpa*), disciplinary actions, system failure.
- **Indigo / Violet (`#6366F1` / Soft Fill `#EEF2FF`):** Extracurricular (*Ekstrakurikuler*), special assignments, secondary taxonomy labels.

## Typography

The type system balances structure and legibility across high-density administrative views.

### Font Pairing Logic
- **Headings & Key Metrics (Plus Jakarta Sans):** Provides contemporary geometric authority with open counters. It keeps executive dashboards crisp, professional, and accessible even when scanning dense KPI metrics or cohort reports.
- **Body, Inputs & Micro-Data (Inter):** The standard for enterprise UI legibility. Inter delivers unambiguous distinction between identical glyphs (such as `1`, `l`, and `I`), which is vital when verifying National Student Identification Numbers (NISN), National Identity Numbers (NIK), and ledger codes.

### Typographic Rules
- Numeric figures within financial ledgers, grades, and attendance summaries must render using tabular figures (`font-variant-numeric: tabular-nums`) to preserve optical column alignment.
- Uppercase text is strictly reserved for micro-labels (`label-sm`), system indicators, table header labels, and badge tags. These elements must always include positive letter spacing (`0.03em`) to maintain legibility at smaller sizes.

## Layout & Spacing

The layout is built on a responsive 12-column fluid grid system pinned to an operational enterprise viewport standard.

### Viewport Structures
- **Desktop (>= 1280px):** Fixed navigation rail (260px expanded, 72px collapsed icon-only) combined with a 12-column fluid content area. Section gutters are locked at `1.5rem` (`24px`), with outer horizontal margins at `2rem` (`32px`).
- **Tablet / Small Laptop (768px - 1279px):** Auto-collapsing sidebar to icon-rail (72px) or overlay sheet. Grid shifts to 8 fluid columns with `1rem` (`16px`) gutters.
- **Mobile Handheld (< 768px):** Single-column layout flow with off-canvas bottom navigation or drawer menu. Section margin drops to `1rem` (`16px`), gutters scale down to `0.75rem` (`12px`).

### Vertical Rhythm & Rationale
All visual margins, internal card paddings, and data row heights adhere to a strict 4px/8px incremental scale:
- `space-xs` (4px): Micro gaps between paired inline metadata, tags, and icons.
- `space-sm` (8px): Form input inner vertical padding, compact badge spacing, cell-level horizontal gaps.
- `space-md` (16px): Card internal padding, form row spacing, header-to-toolbar gaps.
- `space-lg` (24px): Primary dashboard widget gaps, split panel gutters.
- `space-xl` (32px): Distinct administrative module separation and view boundaries.

## Elevation & Depth

This design system avoids heavy shadows, skew, and exaggerated blur filters. Depth is communicated through structured **tonal layering**, surface-contrast stepping, and crisp **hairline borders**.

### Surface Hierarchy
1. **Canvas Layer (`#F8FAFC`):** The lowest layer. Houses page backgrounds, dashboard gutters, and administrative workspace foundations.
2. **Surface Container (`#FFFFFF`):** High-priority structural panels, metric cards, table containers, and filter modules. Elevated above the canvas solely using a razor-thin border (`1px solid #E2E8F0`) and an ambient, low-luminance contact blur.
3. **Elevated Overlays & Popovers:** Dropdowns, contextual menus, date pickers, and flyouts utilize `#FFFFFF` backed by a structured dual shadow: `0 4px 6px -1px rgba(15, 23, 42, 0.06), 0 2px 4px -2px rgba(15, 23, 42, 0.04)` with a perimeter line of `1px solid #CBD5E1`.
4. **Modal Dialogs & Drawers:** High z-index focal surfaces with dark tinted scrims (`rgba(15, 23, 42, 0.5)` backdrop blur of `2px`). Modal surface depth: `0 20px 25px -5px rgba(15, 23, 42, 0.1), 0 8px 10px -6px rgba(15, 23, 42, 0.04)`.

### Border Discipline
All panels, input fields, and tab groups feature crisp geometric boundaries. Outlines rely on slate color gradations:
- Default state: `#E2E8F0`
- Interactive/hover state: `#CBD5E1`
- Focus/selected state: `#1E40AF` with a concentric 2px offset ring (`rgba(37, 99, 235, 0.15)`).

## Shapes

The design system maintains a **Soft** shape language (`roundedness: 1`), balancing humanistic touchpoints with the structured precision of high-density institutional software.

### Geometric Values
- **Base Shape (`rounded`: 0.25rem / 4px):** Applied to compact controls, inline tags, data grid checkboxes, code blocks, and micro-badges.
- **Medium Shape (`rounded-md`: 0.375rem / 6px):** Form controls, inputs, standard buttons, dropdown selectors, and small notification toasts.
- **Large Shape (`rounded-lg`: 0.5rem / 8px):** KPI summary cards, table master containers, complex card components, and modal interfaces.
- **Maximum Shape (`rounded-xl`: 0.75rem / 12px):** Primary dashboard hero containers and executive summary charts.

Pill shapes are strictly restricted to contextual status tags (e.g., student attendance pills) to visually contrast them against functional input boxes and rectangular data cells.

## Components

### Buttons
- **Primary:** Background `#1E40AF`, foreground `#FFFFFF`, border `transparent`. Hover: `#1E3A8A`. Active: `#172554`. Height: 38px (Desktop), 42px (Touch). Padding: `0 16px`. Text style: `label-md`.
- **Secondary / Outline:** Background `#FFFFFF`, foreground `#0F172A`, border `1px solid #E2E8F0`. Hover: `#F8FAFC` and border `#CBD5E1`.
- **Ghost:** Background `transparent`, foreground `#64748B`. Hover: `#F1F5F9` and foreground `#0F172A`.
- **Destructive:** Background `#FEF2F2`, foreground `#EF4444`, border `1px solid #FECACA`. Hover: `#FEE2E2`.

### Badges & Chips (Status Indicators)
Rendered with `font-size: 11px`, `font-weight: 600`, padding `2px 8px`, border radius `9999px` (pill):
- **Lunas / Aktif / Hadir:** Background `#ECFDF5`, text `#065F46`, border `1px solid #A7F3D0`.
- **Menunggu / Izin / Sakit:** Background `#FFFBEB`, text `#92400E`, border `1px solid #FDE68A`.
- **Menunggak / Alpa / Bahaya:** Background `#FEF2F2`, text `#991B1B`, border `1px solid #FECACA`.
- **Tingkat Kelas / Identitas:** Background `#F1F5F9`, text `#334155`, border `1px solid #E2E8F0`.

### Data Tables (Roster & Gradebooks)
- **Container:** Wrapped in a card with `1px solid #E2E8F0`, corner radius `8px`.
- **Header Row:** Background `#F8FAFC`, bottom border `1px solid #E2E8F0`. Typography: `label-sm`, color `#64748B`, text-transform `uppercase`. Height: 40px.
- **Data Rows:** Background `#FFFFFF`, alternating zebra striping is forbidden; depth is maintained via subtle hover state (`#F8FAFC`). Height: 48px (dense) or 56px (standard). Border bottom `1px solid #F1F5F9`.
- **Cell Content:** NISN and monetary amounts use tabular figures aligned right. Text fields align left. Action columns are pinned right.

### Metric KPI Cards
- Background `#FFFFFF`, border `1px solid #E2E8F0`, padding `space-md` (16px), corner radius `8px`.
- Comprises an overline title (`label-sm`, `#64748B`), large stat value (`metric-stat`, `#0F172A`), and an indicator pill indicating trend or cohort percentage (e.g., `+2.4% vs Bulan Lalu`).

### Form Inputs & Filter Toolbars
- Inputs have a height of 38px, background `#FFFFFF`, border `1px solid #E2E8F0`, corner radius `6px`, padding `0 12px`.
- Hover: border `#CBD5E1`. Focus: border `#1E40AF`, ring `3px rgba(37, 99, 235, 0.12)`.
- Integrated Filter Bars: Combines deep search inputs, multi-select dropdowns (Tahun Ajaran, Semester, Kelas/Rombel), and an export action group aligned horizontally with an 8px element gap.

### Breadcrumbs & Context Headers
- Breadcrumbs use `body-sm`, text `#64748B`, with `/` dividers. Active terminal node is `#0F172A`, font-weight `500`.
- Context headers pair the page title (`headline-md`) with quick academic cycle chips (e.g., "TA 2024/2025 - Ganjil") positioned adjacent to the heading.