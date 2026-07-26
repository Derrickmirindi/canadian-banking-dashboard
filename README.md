# BankMap Canada

<p align="center">
  <strong>An interactive dashboard of Canadian banks, credit unions, foreign subsidiaries, note printers, and mutual fund platforms.</strong>
</p>

<p align="center">
  <a href="./map.html">Open Dashboard</a> ·
  <a href="#overview">Overview</a> ·
  <a href="#features">Features</a> ·
  <a href="#getting-started">Getting Started</a> ·
  <a href="#roadmap">Roadmap</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/status-under%20development-e4002b?style=for-the-badge" alt="Status badge" />
  <img src="https://img.shields.io/badge/interface-editorial%20dashboard-111315?style=for-the-badge" alt="Interface badge" />
  <img src="https://img.shields.io/badge/design-12--column%20grid-f5f5f5?style=for-the-badge&logo=github&logoColor=111315" alt="Grid badge" />
</p>

---

## Overview

**BankMap Canada** is an interactive front-end dashboard that maps Canadian financial institutions by head office and organizes them through searchable, filterable, and category-based navigation. The repository currently contains `README.md`, `index.html`, and `map.html`, with `index.html` now redirecting users directly to the main dashboard page in `map.html`. [page:14]

The project is structured as a visual reference interface for exploring the Canadian financial system, including major banks, credit unions, digital-first institutions, foreign-owned subsidiaries, note printers, and mutual fund platforms. The interface uses a strong editorial layout language with a 12-column grid and tab-based navigation. [page:14]

---

## Project snapshot

| Item | Description |
|------|-------------|
| Project name | **BankMap Canada** |
| Type | Interactive financial dashboard |
| Main interface | `map.html` |
| Entry point | `index.html` redirects to `map.html` [page:14] |
| Focus | Canadian banks, financial institutions, and mutual fund platforms |
| Current stage | Under development |

---

## Features

- Interactive institutional map organized by head-office geography.
- Search bar for institution and ownership lookup.
- Category filters for major institution classes.
- Editorial Swiss-inspired layout with visible grid logic.
- Mutual fund tab separated from the map directory.
- Live CAD exchange-rate panel in the interface.
- Lightweight entry page that redirects directly to the dashboard. [page:14]

### Category coverage

- Big Six banks
- Credit unions and cooperatives
- Digital and online banks
- Foreign-owned banks
- Crown and public institutions
- Banknote printers
- Other financial institutions

---

## Interface design

The current dashboard design reflects an editorial information-design approach rather than a generic admin panel. Its typography, spacing rhythm, grid structure, and tab organization make it suitable both as a financial reference interface and as a portfolio-grade front-end project. [page:14]

### Design widgets included in this README

- Centered hero title
- Navigation links
- Status badges
- Snapshot table
- Feature matrix
- Quick-start code block

These README elements improve scannability and make the repository look more complete and professional on GitHub.

---

## Repository structure

```text
canadian-banking-dashboard/
├── README.md
├── index.html
└── map.html
```

| File | Role |
|------|------|
| `README.md` | Project documentation |
| `index.html` | Redirect entry page that sends visitors to `map.html` [page:14] |
| `map.html` | Main dashboard containing layout, styles, scripts, and institution data |

---

## Getting started

### Open locally

1. Clone the repository.
2. Open the project folder.
3. Launch `map.html` in a browser, or use a simple static server.

```bash
git clone https://github.com/Derrickmirindi/canadian-banking-dashboard.git
cd canadian-banking-dashboard
```

Because `index.html` redirects to `map.html`, either file can serve as the entry point for visitors, but the actual dashboard experience lives in `map.html`. [page:14]

### Suggested local server

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

---

## Usage

Use the **Map directory** view to browse institutions geographically and filter them by type. Use the **Mutual funds** tab to separate platform-related content from the institutional map view.

The search field supports quick lookup, while the legend and exchange-rate area add context to the dashboard experience. This makes the project useful for exploration, demonstration, and presentation.

---

## Why this project stands out

| Strength | Value |
|----------|-------|
| Financial focus | Turns institutional finance data into an accessible visual interface |
| Editorial design | Moves beyond generic dashboards into structured information design |
| Front-end clarity | Keeps the project lightweight and easy to inspect |
| Portfolio quality | Suitable for showcasing mapping, UI layout, and data presentation work |
| Expansion potential | Can grow into a richer public financial intelligence tool |

---

## Roadmap

- Expand the institution dataset.
- Add more validation and source transparency.
- Improve mobile responsiveness.
- Separate data from presentation logic.
- Add richer mutual fund and platform coverage.
- Introduce accessibility and performance refinements.

---

## Contribution

Contributions that improve data quality, interface design, documentation, accessibility, or usability are welcome. Good contribution areas include financial data cleanup, map enhancements, visual refinements, and README polishing.

---

## License

No explicit license is visible from the current repository context, so a license file should be added if reuse or public contribution is intended. [page:14]
