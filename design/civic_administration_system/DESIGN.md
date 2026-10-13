---
name: Civic Administration System
colors:
  surface: '#f3fbff'
  surface-dim: '#cfdce2'
  surface-bright: '#f3fbff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#e9f6fc'
  surface-container: '#e3f0f6'
  surface-container-high: '#ddeaf1'
  surface-container-highest: '#d8e5eb'
  on-surface: '#111d22'
  on-surface-variant: '#414945'
  inverse-surface: '#263237'
  inverse-on-surface: '#e6f3f9'
  outline: '#717974'
  outline-variant: '#c0c8c3'
  surface-tint: '#3b6757'
  primary: '#114032'
  on-primary: '#ffffff'
  primary-container: '#2b5748'
  on-primary-container: '#9ccbb8'
  inverse-primary: '#a2d0bd'
  secondary: '#426746'
  on-secondary: '#ffffff'
  secondary-container: '#c1eac1'
  on-secondary-container: '#466b4a'
  tertiary: '#2c3d18'
  on-tertiary: '#ffffff'
  tertiary-container: '#43542d'
  on-tertiary-container: '#b3c896'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#bdedd9'
  primary-fixed-dim: '#a2d0bd'
  on-primary-fixed: '#002117'
  on-primary-fixed-variant: '#224f40'
  secondary-fixed: '#c3edc4'
  secondary-fixed-dim: '#a8d1a9'
  on-secondary-fixed: '#002109'
  on-secondary-fixed-variant: '#2b4e30'
  tertiary-fixed: '#d5eab6'
  tertiary-fixed-dim: '#b9ce9b'
  on-tertiary-fixed: '#111f01'
  on-tertiary-fixed-variant: '#3b4c25'
  background: '#f3fbff'
  on-background: '#111d22'
  surface-variant: '#d8e5eb'
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
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
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
    letterSpacing: 0em
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
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0em
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.03em
  tabular-number:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.02em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.25rem
  gutter-mobile: 0.75rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.25rem
---

## Brand & Style

This design system establishes a trustworthy, highly organized, and accessible digital administration environment tailored for neighborhood-level community governance (Rukun Tetangga / RT). It blends modern civic professionalism with warmth, steering clear of cold bureaucratic software while avoiding frivolous consumer-app tropes.

### Design Movement
**Modern Civic Institutional:** Clean, authoritative, and data-dense. The interface combines precise tabular alignment, structured information groupings, and restrained organic accents. It emphasizes structured civic clarity, legible documentation pathways, and fast operational execution for local officials and residents alike.

### Key Visual Tenets
- **Civic Trust:** Forest and sage green anchors communicate stability, community welfare, and institutional integrity without feeling punitive.
- **Dense Legibility:** Information displays prioritize structured forms, family card (Kartu Keluarga) hierarchies, and real-time census metrics.
- **Calm Utility:** Generous padding around dense tabular cells, crisp divider borders, and muted surfaces minimize fatigue during record entry and verification.

## Colors

The palette balances institutional gravitas with organic calmness, ensuring sustained readability across document checks, population rosters, and financial audit logs.

### Palette Hierarchy & Intent
- **Primary (`#2B5748` - Deep Pine Green):** Key administrative drivers, primary action buttons, main sidebar surface, and verified institutional markers.
- **Secondary (`#618764` - Sage Green):** Sub-actions, interactive highlights, active tab states, and active filtering chips.
- **Tertiary (`#9CB080` - Light Moss Green):** Soft contextual backgrounds, success indicators, verified status badges, and gentle boundary fills.
- **Base Typography & Dark Surfaces (`#273338` - Dark Slate Charcoal):** Primary text, table headers, high-contrast structural borders, and modal headings.

### Surface System
- `surface-base`: `#F7F9F7` (Global canvas backdrop for all dashboard pages)
- `surface-elevated`: `#FFFFFF` (Primary containers, data grid sheets, and input fields)
- `surface-subtle`: `#EEF2EE` (Table alternating row zebra, card headers, disabled states)
- `border-neutral`: `rgba(39, 51, 56, 0.12)` (Crisp hairline borders defining data partitions)
- `border-subtle`: `rgba(39, 51, 56, 0.06)` (Table row separators)

### Semantic Colors
- **Status Valid / Aktif:** Text `#1D4A3A` on background `#E4EFE7`
- **Status Pending / Dalam Proses:** Text `#825B00` on background `#FFF8E1`
- **Status Alert / Pindah / Wafat:** Text `#7D201A` on background `#FCEBEA`
- **Status Information / PBB / Iuran:** Text `#1B4357` on background `#E3F0F7`

## Typography

The type system blends the institutional clarity of **Plus Jakarta Sans** for structural headers with the neutral, hyper-legible characteristics of **Inter** for dense tabular citizen data, National Identification Numbers (NIK), and administrative forms.

### Usage Standards
- **Tabular Numerics:** All citizen IDs (NIK, Nomor KK), phone numbers, RT/RW numbers, and monetary contributions must enforce `font-feature-settings: "tnum" 1, "cv05" 1` to guarantee vertical digit alignment across tables.
- **Administrative Phrasing:** Header labels and metadata use formal Indonesian terminology (e.g., *Nomor Induk Kependudukan*, *Kepala Keluarga*, *Surat Pengantar*, *Mutasi Warga*).
- **Uppercase Restraint:** Reserve uppercase styling strictly for micro-labels (`label-sm`), table field headers, and status pill badges with positive letter-spacing (`+0.04em`).

## Layout & Spacing

A structured 12-column grid system designed for dense data management and administrative dashboards.

### Breakpoints & Layout Adapters
- **Desktop (>= 1280px):** 12 columns, fixed collateral side navigation (260px), `margin: 2rem`, `gutter: 1.25rem`. Complex split views (list on the left, citizen profile verification sheet on the right).
- **Tablet (768px – 1279px):** 8 columns, collapsible slim navigation (64px icon rail), `margin: 1.5rem`, `gutter: 1rem`. Multi-column filters stack into collapsible drawer panels.
- **Mobile (< 768px):** 4 columns, full-width fluid layout, `margin-mobile: 1rem`, `gutter-mobile: 0.75rem`. Tables adapt to stacked structured identity cards.

### Grid Rhythm & Data Layouts
- Form layouts enforce two-column or four-column alignment with a strict `1rem` vertical and horizontal field gap (`space-md`).
- Table cell padding is maintained at `0.75rem 1rem` for desktop density and `1rem` uniform for card-based mobile summaries.

## Elevation & Depth

Visual hierarchy is conveyed primarily through **tonal separation** and **crisp hairline borders**, supported by subtle, low-blur ambient shadows for overlay components. Heavy drop shadows are omitted to maintain an institutional, paper-like record clarity.

### Elevation Hierarchy
- **Level 0 (Base Surface):** `#F7F9F7` background. Flat, no border.
- **Level 1 (Card & Content Blocks):** `#FFFFFF` fill with a `1px` solid outline of `rgba(39, 51, 56, 0.08)`. No shadow, relying on pure surface contrast against the base canvas.
- **Level 2 (Hover & Active Table Rows):** Soft fill transition to `#EEF2EE` with outline accentuation.
- **Level 3 (Dropdowns & Popovers):** `#FFFFFF` surface, `1px` solid border `rgba(39, 51, 56, 0.12)`, shadow: `0 4px 16px -2px rgba(39, 51, 56, 0.08)`.
- **Level 4 (Modal Dialogs & Slide-out Citizen Drawers):** `#FFFFFF` surface accompanied by a neutral backdrop overlay `rgba(39, 51, 56, 0.45)` with `backdrop-filter: blur(2px)`. Ambient shadow: `0 12px 32px -4px rgba(39, 51, 56, 0.16)`.

## Shapes

The design system implements a **Soft (`1`)** shape language to reflect formal administrative stability without sharp severity.

### Corner Radius Standards
- **Base Components (`rounded` = 0.25rem / 4px):** Form input fields, search bars, action buttons, table row selections, and status badges.
- **Medium Enclosures (`rounded-lg` = 0.5rem / 8px):** Data tables, profile summary cards, statistic indicator blocks, and navigation bar surfaces.
- **Large Overlays (`rounded-xl` = 0.75rem / 12px):** Verification modals, export confirmation dialogs, and slide-in citizen documentation panels.
- **Pill Shape (`rounded-full`):** Numeric badge indicators, notification counts, and citizen state indicator dots.

## Components

### Buttons
- **Primary:** Solid `#2B5748` background, `#FFFFFF` text, `border-radius: 4px`, medium weight. On hover: darken to `#204236`. On active: `#183329`.
- **Secondary:** Transparent background, `1px` border in `#618764`, `#2B5748` text. On hover: background `#EEF2EE`.
- **Ghost / Neutral:** Transparent background, `#273338` text. On hover: background `rgba(39, 51, 56, 0.05)`.
- **Destructive:** Solid `#DC2626` background or outline `#DC2626` with red text for actions like *Hapus Data Warga*.

### Badges & Status Chips
- Height of 22px, padding `2px 8px`, `border-radius: 4px`, typography `label-sm`.
- **Warga Tetap:** Background `#E4EFE7`, text `#1D4A3A`, border `1px solid rgba(43, 87, 72, 0.2)`.
- **Warga Kontrak / Domisili:** Background `#E8F0F5`, text `#1B4357`, border `1px solid rgba(27, 67, 87, 0.2)`.
- **Kepala Keluarga:** Background `#2B5748`, text `#FFFFFF`.

### Data Tables (Daftar Warga & Iuran)
- Table header row uses surface `#EEF2EE`, text `#273338`, uppercase `label-sm`, letter spacing `0.04em`.
- Hairline horizontal dividers `1px solid rgba(39, 51, 56, 0.08)`.
- Rows include subtle zebra striping (`#FFFFFF` alternating with `#FAFBF9`) and highlight with `#F0F4F1` on pointer hover.
- NIK and phone columns apply monospace tabular numeric formatting.

### Input Fields & Select Controls
- Surface `#FFFFFF`, border `1px solid rgba(39, 51, 56, 0.20)`, border-radius `4px`, padding `8px 12px`.
- Placeholder text in `rgba(39, 51, 56, 0.40)`.
- Focus ring: `2px solid #2B5748` with `offset: 1px`.
- Prefix/Suffix labels (such as "NIK", "KK", "+62", or "Rp") styled with surface `#EEF2EE` and border dividers.

### Family Tree & Household Cards (Kartu Keluarga View)
- Header displaying Nomor KK and Nama Kepala Keluarga with quick action badges (*Cetak Surat Pengantar*, *Edit Mutasi*).
- Nested tabular view for family members (*Istri*, *Anak*, *Famili Lain*) with clear parent-child visual hierarchy.

### Civic Specific Components
- **Surat Pengantar Generator:** A dedicated document preview container mimicking standard Indonesian RT/RW administrative stamps and signatures.
- **Statistic Metric Tiles:** Clean summary tiles with large tabular display numbers for total citizens (*Total Warga*), households (*Kepala Keluarga*), and pending requests (*Permohonan Baru*).