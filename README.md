# BankMap Canada

An interactive dashboard of Canadian banks, credit unions, foreign bank subsidiaries, banknote printers, and mutual fund platforms across Canada. The project maps institutions by head office and presents ownership, classification, scale, and selected market context in a clean editorial-style interface. 

**Authors:** Derrick Mirindi, David Sinkhonde, and Frederic Mirindi. 

![BankMap Canada preview](https://github.com/user-attachments/assets/3d191f5a-ee97-4c7c-a270-5fce772e417a)

## Overview

BankMap Canada is a front-end data visualization project focused on the Canadian financial landscape. It combines a geographic map, searchable institution directory, legend system, tab-based navigation, and mutual fund platform listings into a single browsing experience. 

The project is designed as an interactive reference tool for users who want to explore the structure of Canadian banking and adjacent financial infrastructure, including the Big Six banks, digital banks, cooperatives, foreign-owned institutions, crown financial entities, and note-printing firms. 

## Features

- Interactive map of Canadian financial institutions by head-office location. 
- Search bar for filtering institutions by name or ownership. 
- Category filters for institution types such as Big Six banks, co-ops, digital banks, foreign-owned banks, crown institutions, note printers, and other entities.
- Editorial grid-based layout inspired by Müller-Brockmann design principles. 
- Mutual fund tab for separating investment-platform content from the main institutional map view. 
- Live CAD exchange-rate panel integrated into the interface. 
- Grid toggle for inspecting the underlying 12-column visual system. 

## Repository structure

| File | Purpose |
|------|---------|
| `README.md` | Project documentation and usage guide.  |
| `index.html` | Main project entry file in the repository.  |
| `map.html` | Interactive dashboard page containing layout, styles, map logic, and institution data. |

## Data coverage

The dashboard currently includes institutions such as major Canadian banks, regional banks, digital banks, credit unions, foreign subsidiaries, and specialized entities such as banknote printers. The `map.html` page also includes category definitions and a structured institution array used to render the interface. 

Examples visible in the current code include Royal Bank of Canada, TD Canada Trust, Scotiabank, BMO, CIBC, National Bank of Canada, HSBC Bank Canada, Laurentian Bank of Canada, Canadian Western Bank, Neo Financial, Desjardins Group, Vancity, Meridian Credit Union, EQ Bank, Tangerine, and Canadian Bank Note Company. 

## Design approach

The interface uses a structured 12-column grid, strong typographic hierarchy, mono-label metadata, and an editorial visual language consistent with Swiss modernist layout principles. The code also includes a grid overlay toggle and baseline-driven spacing system, reinforcing the project’s design discipline as well as its data-navigation goals. [page:1]

This makes the dashboard useful not only as a finance reference interface but also as a demonstration of data storytelling, information architecture, and front-end design practice. 

## Getting started

1. Clone the repository.
2. Open `map.html` in a browser, or serve the repository locally with a simple static server.
3. Explore the map, use the search and filters, and switch between the directory and mutual-fund views. 

Then open `map.html` in your browser. 

## Usage

Use the **Map directory** tab to explore institutions geographically and browse categorized entries. Use the **Mutual funds** tab to view the investment-platform section separately from the institutional map.

The search input allows quick filtering, while the category buttons help isolate segments of the financial system. The legend and live CAD rate panel provide additional context within the same interface.

## Current status

The repository and page labels indicate that the project is still under development. The visible interface text in `map.html` explicitly identifies the dashboard as “Under Development,” which suggests ongoing refinement of data coverage, layout, and documentation. 

## Roadmap

- Expand the institution dataset and validate all entries.
- Add clearer source notes for institutional attributes.
- Improve mobile responsiveness and accessibility.
- Separate data from presentation for easier maintenance.
- Add deeper coverage of mutual fund platforms and related financial tools.
