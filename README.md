# Task Manager

A calm, **project-first** task board in a single self-contained HTML file — no build, no server, no dependencies. Your data lives in your browser (`localStorage`).

**Live demo → https://septemberfd.github.io/task-manager/**

## Idea

Track work by the *big things* (projects), not scattered atoms. Each project holds its tasks, a deadline, and a free-form notes area for context (paste links, messages, thoughts). A few lenses sit on top:

- **Overview** — KPIs and per-project progress at a glance
- **Focus** — everything you starred as important, regardless of date
- **This Week** — what's due this week (and anything overdue), grouped by project
- **Projects** — collapse, archive, drag to reorder; an *Uncategorized* inbox for loose tasks
- **Tasks** — one spreadsheet: filter by status or time period, group by project, edit inline
- **Trash** — deleted tasks and projects wait here; restore anytime

## Notes on the model

- **Star = important** (shows in Focus). **Deadlines** drive This Week. No fussy priority labels.
- A project's deadline **auto-extends** to its latest task.
- New tasks default to a deadline a week out; new projects a month out — so nothing is dateless.
- Light / dark theme. Optional: sync your data to a local `tasks.json` (cross-device via any file-sync).

## Use it

Open `index.html` in any modern browser, or visit the live demo. The sample projects are just there to show the layout — clear them and add your own. Everything you enter stays in *your* browser.

---

Created by [septemberfd](https://github.com/septemberfd) · MIT licensed.
