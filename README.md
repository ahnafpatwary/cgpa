# BRACU CGPA Calculator

A lightweight, privacy-first web application for tracking cumulative GPA across semesters at BRAC University. No account, no backend, no data collection — all data is stored locally on the device.

**Live → [ahnafpatwary.github.io/cgpa](https://ahnafpatwary.github.io/cgpa)**

---

## Features

- Semester management with custom naming and auto-numbering
- Inline editing across all fields with instant recalculation
- Per-course entry — course code, credit hours, GPA selection, automatic letter grade
- Real-time computation of semester GPA, cumulative CGPA, and CGPA after each semester
- Credits attempted displayed per semester
- Cumulative CGPA trend (line chart) and semester GPA comparison (bar chart) with independent toggles
- Data persistence via browser localStorage
- Deletion confirmation to prevent accidental data loss

---

## BRACU Grading Scale

| Marks | Grade | GPA |
|-------|-------|-----|
| 97 – 100 | A+ | 4.00 |
| 90 – <97 | A | 4.00 |
| 85 – <90 | A- | 3.70 |
| 80 – <85 | B+ | 3.30 |
| 75 – <80 | B | 3.00 |
| 70 – <75 | B- | 2.70 |
| 65 – <70 | C+ | 2.30 |
| 60 – <65 | C | 2.00 |
| 57 – <60 | C- | 1.70 |
| 55 – <57 | D+ | 1.30 |
| 52 – <55 | D | 1.00 |
| 50 – <52 | D- | 0.70 |
| < 50 | F | 0.00 |

---

## Tech Stack

- HTML, CSS, JavaScript — no frameworks or build tools
- [Chart.js](https://www.chartjs.org/) for data visualisation
- [DM Sans](https://fonts.google.com/specimen/DM+Sans) via Google Fonts
- localStorage for client-side persistence
- Deployed via GitHub Pages

---

## Versions

| Version | File | Notes |
|---------|------|-------|
| v2.0 | `index.html` | Credits badge, semester GPA bar chart, dual graph toggles |
| v1.0 | `index_v1.html` | Initial release |

See [CHANGELOG.md](./CHANGELOG.md) for full details.

---

## Author

**Ahnaf Tahmid Patwary** — [github.com/ahnafpatwary](https://github.com/ahnafpatwary)

---

*© 2026 Ahnaf Tahmid Patwary. All rights reserved.*
