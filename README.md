# Lanka Fresh Mart - Sales Dashboard

## Student Information
- **Name:**N.M.S.Chethana
- **Reegistration Number**-MGT/2025/064

## Layout Structure: Grid & Flexbox Usage

* **CSS Grid:**
  * **Layouts:** Used for structuring the KPI metrics grid (`.kpi-grid`) and the asymmetrical charts section (`.charts-grid`)[cite: 3].
  * **Centering:** Used to place elements precisely using `place-items: center` for icons and avatars (`.brand-mark`, `.avatar`, `.kpi-icon`)[cite: 3].

* **Flexbox:**
  * **Containers:** Used for structuring the main app shell, sidebar layout, and top navigation bar (`.topbar`)[cite: 3].
  * **Alignment:** Used for headers, footers, chart legends (`.branch-legend`), and mobile navigation dropdown menus (`.primary-nav`)[cite: 3].

---

## Known Issues

* **Missing DOM Elements:** JavaScript attempts to update non-existent HTML element IDs like `bestMonthValue`, `insightText`, `monthlyPeak`, `q2Total`, and `growthRate`[cite: 2, 3].
* **Duplicate IDs:** The ID `reports` is assigned to multiple elements (both a navigation link and a chart card) in the HTML file[cite: 1, 3].
* **Low Contrast Risk:** KPI cards combine dark gradient backgrounds with dark text colors, which can reduce readability[cite: 3].
* **Disabled Animations:** Chart animations are explicitly turned off (`animation: false`), making charts pop in instantly instead of rendering smoothly[cite: 2].