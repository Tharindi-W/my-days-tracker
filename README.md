# My Days — Daily Tracker PWA

A lightweight, offline-first Progressive Web App for daily habit and routine tracking. Built as a personal project to replace paper to-do lists with something installable, persistent, and fully private.

**Live demo:** `https://your-netlify-url.netlify.app`

---

## Features

- Four day types that pick themselves by weekday (tap a chip to change):
  - **WFH** (Mon, Fri): PhD block before work, career hour after the gym
  - **Office** (Tue, Wed, Thu): read a paper on the commute in, save jobs on the way home
  - **Trip / party** (Sat): no-guilt day out, with an optional 15-minute tiny win
  - **Cook · clean · shop** (Sun): groceries + meal prep for the week, then a 2-hour PhD/career power block
- A timed plan for each day type, with the current block highlighted
- Six daily goals rated 1 to 5 stars, scored out of 100 (total stars x 100 / 30)
- Daily tallies for jobs applied, GitHub pushes, papers read and professors emailed, with weekly targets
- Countdown to the end of the contract (20 Jan 2027) and the December hiring slowdown
- Weekly milestones for the PhD, the next job and GitHub, with a weekly focus star
- History, a 14-day score trend, 6-goal averages and a calendar heatmap
- Edit a past day if you forgot to rate it the night before
- Export data as JSON (backup/restore) or CSV (spreadsheet)
- Works fully offline after first load
- No backend, no account, no tracking: data stays on your device

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
