# MY WEEK — Weekly Planner

A standalone, mobile-first weekly planner built with HTML, CSS and vanilla JavaScript.

## Run locally

1. Download and extract `MY_WEEK_Project.zip`.
2. Open `index.html` in a modern browser (Chrome recommended).
3. Your planner data is saved in that browser using `localStorage`.

## Current features

- Seven-day planner with previous / this week / next week navigation.
- Custom checklist categories with independently scheduled sub-checkboxes.
- Generic counter trackers with independent checkboxes.
- Optional Steps tracker with a configurable daily target and ten independent checkboxes.
- Activity-based daily and weekly completion calculations.
- Drag-handle activity reordering and editing.
- Local browser persistence.

## Counter layout update

- Generic counters and the Steps tracker display checkbox-only tiles (no 1, 2, 3 labels).
- Counter tiles are arranged in exactly two rows with no internal horizontal scrolling.
- Generic counters support 1–20 checks so the tiles remain usable on narrow mobile screens.
- Each activity card has its own × remove control. Removal asks for confirmation; historical completion records are retained in local storage.
- Steps remain calculated internally as `daily target / 10`; the per-checkbox value is not printed on the tiles.

## Data and privacy

This version stores data in the current browser/device only. It does not provide cloud backup or cross-device synchronisation. Clearing browser site data can remove the saved planner.

## Hosting on GitHub Pages

Create a separate repository (for example, `my-week-weekly-planner`), upload `index.html` and this README, then enable GitHub Pages from the repository's Settings → Pages.
