# Changelog — BRACU CGPA Calculator

All notable changes to this project are documented here.

---

## v4.0 — Current (`index.html`)

### Added
- Collapsible semester cards — chevron toggle on each semester header collapses/expands the course list
- Collapse state persists via localStorage — stays collapsed across page refreshes

---

## v3.0 — (`index_v3.html`)

### Added
- Mobile responsive layout — course rows reformat as stacked cards on small screens
- Semester name and header wrap correctly on mobile
- Graph toggles stack vertically on mobile

---

## v2.0 — (`index_v2.html`)

### Added
- Credits attempted badge in each semester header (next to GPA badge), updates live
- Semester GPA bar chart — toggle independently from the CGPA trend line chart
- Two separate graph toggles with active state indicator

---

## v1.0 — (`index_v1.html`)

### Initial release
- Semester cards with inline-editable course tables
- GPA dropdown (12 discrete values per BRACU grading scale) with auto letter grade
- Per-semester GPA and cumulative CGPA calculations
- CGPA after each semester displayed in semester footer
- Cumulative CGPA trend line chart (toggleable)
- Confirmation popup for all deletions (course and semester)
- Persistent storage via localStorage
- Favicon (CG/PA split colour, dark background)
- Footer with copyright — Ahnaf Tahmid Patwary
