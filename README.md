Parse Source Tracker

A tiny local tool for keeping track of the sources you scrape: which ones are done, which are in progress, which failed, and when each run is planned to start and finish.

No installation, no dependencies, no server. It is a single HTML file.

Features

- Add sources (URL or name) with a planned start and end time
- Four statuses: not parsed, in progress, parsed, error
- Overdue highlight when the planned end time has passed and the source is not parsed
- Filter by status and see summary counters
- Export to JSON (backup) and CSV (spreadsheets), import from JSON
- Light and dark theme follow the system setting

Usage

1. Clone the repository or download `index.html`.
2. Open `index.html` in any modern browser.

```bash
git clone https://github.com/egorfm/parse-source-tracker.git
cd parse-source-tracker
open index.html
```

Data storage

Data lives in the browser's `localStorage`, so it stays on your machine and is tied to the browser you use. Clearing site data removes it. Use **Export JSON** regularly to keep a backup.
