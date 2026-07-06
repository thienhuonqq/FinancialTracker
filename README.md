# Sophie · Finance Tracker

A single-file personal finance tracker built with HTML, CSS, and JavaScript. No backend, no dependencies to install — just open `FinanceTracker.html` in your browser.

## Features

- **Dashboard** — KPI summary cards (income, expenses, net savings, savings rate, daily average) with charts for spending trends, category breakdowns, and monthly comparisons
- **Transactions** — Add, edit, delete, and search transactions with category tagging
- **Insights** — Advanced analytics including top spending categories, recurring charges, and month-over-month changes
- **Upload** — Import transactions from Westpac and other bank CSV/TXT exports
- **Export** — Export your data to Excel (.xlsx)
- **Google Sheets sync** — Sign in to save your tracker data to a Google Sheet and keep manual edits backed up
- **localStorage persistence** — Data is saved in your browser first, then synced to Google Sheets when connected
- **Filtering** — Filter by time period (week, month, quarter, year, or custom date range) and by category

## Usage

1. Download or clone this repo
2. Open `FinanceTracker.html` in any modern browser
3. Sign in with Google Sheets if you want cloud backup
4. Upload a Westpac/bank CSV file, review the preview, then import
5. Edit categories, notes, or amounts manually whenever needed

No server is required. Internet is needed for first loading CDN libraries and for Google Sheets sync.

## Data

All data is stored in your browser's `localStorage`. If Google Sheets is connected, changes are also written to your linked spreadsheet. To back up manually, use the Export button to save an Excel file.

## Tech Stack

- [Chart.js](https://www.chartjs.org/) — charts and graphs
- [PapaParse](https://www.papaparse.com/) — CSV parsing
- [SheetJS (xlsx)](https://sheetjs.com/) — Excel file parsing
