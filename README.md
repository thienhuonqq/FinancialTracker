# Sophie · Finance Tracker

A single-file personal finance tracker built with HTML, CSS, and JavaScript. No backend, no dependencies to install — just open `FinanceTracker.html` in your browser.

## Features

- **Dashboard** — KPI summary cards (income, expenses, net savings, savings rate, daily average) with charts for spending trends, category breakdowns, and monthly comparisons
- **Transactions** — Add, edit, delete, and search transactions with category tagging
- **Insights** — Advanced analytics including top spending categories, recurring charges, and month-over-month changes
- **Upload** — Import transactions from CSV or Excel (.xlsx) files
- **Export** — Export your data to CSV
- **localStorage persistence** — All data is saved automatically in your browser; nothing leaves your device
- **Filtering** — Filter by time period (week, month, quarter, year, or custom date range) and by category

## Usage

1. Download or clone this repo
2. Open `FinanceTracker.html` in any modern browser
3. Start adding transactions manually or upload a CSV/Excel file

No server, no sign-up, no internet connection required after the initial page load.

## Data

All data is stored in your browser's `localStorage`. Clearing your browser data will erase your transactions. To back up, use the Export button to save a CSV.

## Tech Stack

- [Chart.js](https://www.chartjs.org/) — charts and graphs
- [PapaParse](https://www.papaparse.com/) — CSV parsing
- [SheetJS (xlsx)](https://sheetjs.com/) — Excel file parsing
