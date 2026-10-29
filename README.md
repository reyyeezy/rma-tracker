# RMA Tracker

A small, single-page tool for tracking returned hardware (RMAs) through bench inspection.

- Add a unit with serial, model and the reported issue
- Run a configurable inspection checklist (Pass / Fail / N/A per item)
- Move each unit through Received → Inspecting → Awaiting action → Closed
- Search and filter, see open / passed / failed counts
- Export everything to CSV

No server, no build step, no dependencies. Open `index.html` in a browser.
Data is stored in your browser's local storage and never leaves your machine.

The demo data uses made-up devices and serial numbers.

## Run it

```
open index.html
```

## Ideas for later

- Photo attachments per unit
- JSON import/export to move data between machines
- Per-model checklists
