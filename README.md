# BankMap Canada

An interactive dashboard of Canadian banks, credit unions, foreign bank subsidiaries, banknote printers, and mutual fund platforms across Canada. The project maps institutions by head office and presents ownership, classification, scale, and selected market context in a clean editorial-style interface. [page:13][page:1]

**Authors:** Derrick Mirindi, David Sinkhonde, and Frederic Mirindi. [page:13]

![BankMap Canada preview](https://github.com/user-attachments/assets/3d191f5a-ee97-4c7c-a270-5fce772e417a)

## Overview

BankMap Canada is a front-end data visualization project focused on the Canadian financial landscape. It combines a geographic map, searchable institution directory, legend system, tab-based navigation, and mutual fund platform listings into a single browsing experience. [page:1]

The project is designed as an interactive reference tool for users who want to explore the structure of Canadian banking and adjacent financial infrastructure, including the Big Six banks, digital banks, cooperatives, foreign-owned institutions, crown financial entities, and note-printing firms. [page:1]

## Features

- Interactive map of Canadian financial institutions by head-office location. [page:1]
- Search bar for filtering institutions by name or ownership. [page:1]
- Category filters for institution types such as Big Six banks, co-ops, digital banks, foreign-owned banks, crown institutions, note printers, and other entities. [page:1]
- Editorial grid-based layout inspired by Müller-Brockmann design principles. [page:1]
- Mutual fund tab for separating investment-platform content from the main institutional map view. [page:1]
- Live CAD exchange-rate panel integrated into the interface. [page:1]
- Grid toggle for inspecting the underlying 12-column visual system. [page:1]

## Repository structure

| File | Purpose |
|------|---------|
| `README.md` | Project documentation and usage guide. [page:13] |
| `index.html` | Main project entry file in the repository. [page:13] |
| `map.html` | Interactive dashboard page containing layout, styles, map logic, and institution data. [page:13][page:1] |

## Data coverage

The dashboard currently includes institutions such as major Canadian banks, regional banks, digital banks, credit unions, foreign subsidiaries, and specialized entities such as banknote printers. The `map.html` page also includes category definitions and a structured institution array used to render the interface. [page:1]

Examples visible in the current code include Royal Bank of Canada, TD Canada Trust, Scotiabank, BMO, CIBC, National Bank of Canada, HSBC Bank Canada, Laurentian Bank of Canada, Canadian Western Bank, Neo Financial, Desjardins Group, Vancity, Meridian Credit Union, EQ Bank, Tangerine, and Canadian Bank Note Company. [page:1]

## Design approach

The interface uses a structured 12-column grid, strong typographic hierarchy, mono-label metadata, and an editorial visual language consistent with Swiss modernist layout principles. The code also includes a grid overlay toggle and baseline-driven spacing system, reinforcing the project’s design discipline as well as its data-navigation goals. [page:1]

This makes the dashboard useful not only as a finance reference interface but also as a demonstration of data storytelling, information architecture, and front-end design practice. [page:1]

## Getting started

1. Clone the repository.
2. Open `map.html` in a browser, or serve the repository locally with a simple static server.
3. Explore the map, use the search and filters, and switch between the directory and mutual-fund views. [page:1]

Example:

```bash
git clone https://github.com/Derrickmirindi/canadian-banking-dashboard.git
cd canadian-banking-dashboard
```

Then open `map.html` in your browser. [page:13][page:1]

## Usage

Use the **Map directory** tab to explore institutions geographically and browse categorized entries. Use the **Mutual funds** tab to view the investment-platform section separately from the institutional map. [page:1]

The search input allows quick filtering, while the category buttons help isolate segments of the financial system. The legend and live CAD rate panel provide additional context within the same interface. [page:1]

## Current status

The repository and page labels indicate that the project is still under development. The visible interface text in `map.html` explicitly identifies the dashboard as “Under Development,” which suggests ongoing refinement of data coverage, layout, and documentation. [page:1]

## Roadmap

- Expand the institution dataset and validate all entries.
- Add clearer source notes for institutional attributes.
- Improve mobile responsiveness and accessibility.
- Separate data from presentation for easier maintenance.
- Add deeper coverage of mutual fund platforms and related financial tools.

## Contribution

Suggestions, corrections, and contributions that improve the accuracy, usability, and presentation of the dashboard are valuable. Proposed changes may include data updates, UI improvements, accessibility fixes, or documentation enhancements.

## License

No license text is currently visible in the repository pages provided here, so usage rights should be clarified by adding a license file if public reuse is intended. [page:13]

