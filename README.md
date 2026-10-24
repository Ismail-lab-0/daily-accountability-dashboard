# Daily Accountability Dashboard

An offline personal dashboard: one-tap daily done/not-done tracking under your own categories, projects, learning, finance, journal and goals.

**Full version (buyers):** https://ismail-lab-0.github.io/daily-accountability-dashboard/

## Features

- Input tracker with colour-coded categories and per-task streaks
- Dashboard with time filter, done %, progress chart and Off track list
- Plans, Projects (kanban), Learning, Finance, Journal, Goals
- Export/import JSON backup and printable report; works offline once installed

## Setup

This is a static, self-contained HTML app — no build step required to run it.
Open `index.html` directly, or serve the repo's `docs/` folder (this is what
GitHub Pages does automatically for this repo).

## Limitations

- Data is stored locally in the browser only — export a backup periodically.

## Deployment

Published via GitHub Pages from the `docs/` folder on `main`. The demo build (if any) and the full build are generated from the same source by `tools/app_bundle.js` — see that script for the `--demo` flag.