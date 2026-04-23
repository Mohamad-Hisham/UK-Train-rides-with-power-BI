# Phase 1 — Stitch UI Structure Extraction (Initial)

Source requested by user:
- https://stitch.withgoogle.com/projects/16128246752799282953

## Access status
The Stitch project URL is reachable, but its design payload is not directly retrievable in this CLI environment (likely due authenticated, client-rendered content).

## Inferred UI structure (from request + LMS admin conventions)

### Global shell
- **Left Sidebar (fixed desktop / drawer mobile)**
  - Brand/logo area
  - Primary nav groups
  - Active route indicator
  - Collapsible behavior
- **Topbar**
  - Page title + breadcrumb
  - Global search
  - Notifications
  - User profile menu
- **Main content area**
  - Section headers
  - KPI card rows
  - Filter/toolbars
  - Data tables
  - Charts and detail cards

### Reusable visual patterns
- Rounded cards with soft border/shadow
- Dense but readable data tables with status chips
- Action buttons in neutral/primary emphasis
- Compact filters (select, date range, text search)
- Slide-over/drawer and dialog forms for CRUD
- Empty/loading/error states for all grids and charts

### Core layout composition
1. App shell (`Sidebar + Topbar + Content`)
2. Page header (`title + subtitle + primary actions`)
3. Analytics row (`KPI cards`)
4. Control row (`search/filter/sort/export`)
5. Main data surface (`table/grid`) with pagination
6. Secondary surface (`chart/activity/recent items`)

### Bilingual support considerations (EN/AR)
- RTL layout toggle
- Locale-aware typography spacing
- Dual-language display fields on content entities

## Design token baseline to implement
- **Color roles**: `background`, `foreground`, `muted`, `card`, `primary`, `secondary`, `destructive`, `success`, `warning`, `info`
- **Spacing scale**: `4/8/12/16/20/24/32`
- **Radius scale**: `sm/md/lg/xl`
- **Typography**:
  - Page title
  - Section title
  - Body
  - Caption
  - Label

> Note: Once Stitch export/screenshots are accessible, this file should be updated with exact token values, component proportions, and spacing deltas.
