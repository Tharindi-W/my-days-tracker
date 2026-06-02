# My Days — Daily Tracker PWA

A lightweight, offline-first Progressive Web App for daily habit and routine tracking. Built as a personal project to replace paper to-do lists with something installable, persistent, and fully private.

**Live demo:** `https://your-netlify-url.netlify.app`

---

## Features

- Three day modes: Weekday, Hiking day, Cook day
- Circular progress ring per day
- Mood logging and daily notes
- Full history with streak counter and completion stats
- Monthly calendar heatmap
- Goal progress tracking across four life goals
- Export data as JSON (backup/restore) or CSV (spreadsheet)
- Works fully offline after first load
- No backend, no account, no tracking — data stays on your device

## Tech stack

- Vanilla HTML, CSS, JavaScript — no frameworks, no dependencies
- Progressive Web App (PWA) with service worker for offline support
- Web App Manifest for home screen installation
- localStorage for persistent data

## Installation

**On iPhone (Safari):**
1. Open the live demo URL in Safari
2. Tap the Share button
3. Tap "Add to Home Screen"

**On Android (Chrome):**
1. Open the live demo URL in Chrome
2. Tap the 3-dot menu
3. Tap "Add to Home Screen" or "Install app"

## Run locally

No build step needed. Clone the repo and open `index.html` in a browser:

```bash
git clone https://github.com/yourusername/my-days-tracker.git
cd my-days-tracker
open index.html
```

For service worker support, serve over HTTP:

```bash
npx serve .
```

Then open `http://localhost:3000`

## Data and privacy

All data is stored in your browser's `localStorage`. Nothing is sent to any server. Use the Data tab in the app to export a JSON backup at any time and restore it on any device.

## Screenshots

<img width="1706" height="963" alt="image" src="https://github.com/user-attachments/assets/eaf8f1f1-77da-44e6-bf89-6fd9a7d8b064" />


## License

MIT — free to use, modify, and distribute.
