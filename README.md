# plus-packaging-dashboards
# Plus Packaging — Sales Dashboards

Internal sales performance dashboards built as standalone HTML files. No server or internet connection required — open directly in any browser.

---

## Files

### `ppj_personal_dashboard.html`
Jay's personal sales dashboard (salesperson code: PPJ).

- 36 customer accounts tracked across all months
- Monthly revenue targets and UK working days hardcoded for 2026
- Bar chart view and sortable customer breakdown table
- January and February 2026 actuals loaded
- Data persists via browser localStorage

### `team_dashboard.html`
Sales team overview dashboard covering all six salespeople (PP1–PP5, PPA/D).

- Editable revenue figures and sales targets per person
- Activity metrics: Calls, Visits, Deals, Fixed Appointments, New Customers
- Progress bars per metric (suppressed where target is zero)
- Data persists via browser localStorage

### `monthly_summary_dashboard.html`
High-level monthly summary for tracking overall sales performance.

- Month selector with working days progress bar
- Tracks: Target, Invoiced, Tracking, Difference, Needed Per Day
- Tracking vs target progress bar with binary green/red colouring
- Data persists via browser localStorage

---

## Usage

1. Download the relevant HTML file
2. Open it directly in Chrome or Edge (double-click the file)
3. Data is saved automatically in your browser's localStorage

> **Important:** localStorage only works when the file is opened locally in a browser — not via a preview window or online viewer.

---

## Data & Targets

- All targets are set for the 2026 calendar year
- Customer C001287 (Tudor Environmental) carries zero targets across all months
- Metrics with a zero target display no progress bar

---

*Plus Packaging — Internal use only*
