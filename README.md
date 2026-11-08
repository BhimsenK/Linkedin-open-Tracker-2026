# MY WEEK — Weekly Planner

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
