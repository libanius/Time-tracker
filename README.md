# TimeTrack — crew hours and payroll from the phone

**An offline-first app for contractors to log hours by project and rate, and pay helpers and crews correctly — without spreadsheets.**

Part of the [BrightScale](https://github.com/libanius) family of construction tools. Its sibling, [BrightScale Tracker](https://github.com/libanius/BrightScale-Tracker), runs the project; TimeTrack runs the hours.

## The problem

On a remodeling job, labor is the cost that leaks the most. Hours live in text messages, notebooks and memory, and payday turns into a negotiation. TimeTrack makes the record at the moment the work happens.

## What it does

- **Check-in / check-out** in two taps — now, or a time you type, today, yesterday or another day
- **Projects with an hourly rate** — each client or service is its own project
- **Reports by period and week**, with **payroll** totals and **PDF export**
- **Ledger** of what was earned and what was paid
- **Works offline** — data lives on the device (IndexedDB) and the app installs on iPhone like a native app
- **Backup and restore through GitHub** — versioned, so a lost phone is not lost hours

## Built with

Vanilla JavaScript · Progressive Web App · IndexedDB · GitHub API for backup · GitHub Pages hosting. Iterated through more than seven major versions on real jobs (current: v7.12).

## Status

In use by its author to track his own hours on South Florida remodeling jobs. Interface currently in Portuguese.

## Roadmap

- Multiple workers per company, with the owner's approval of hours
- Hours flowing directly into BrightScale Tracker's project financials
- English and Spanish interface

---

Built by **Paulo Libânio Neto**, construction project manager and founder of BrightScale Contractor · contact@brightscalegroup.com
