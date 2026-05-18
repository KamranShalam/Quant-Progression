# Quant Career Plan — Kamran Shalam

A single-file, self-contained dashboard for tracking a 12-month quantitative finance career pivot. No build step, no dependencies, no server — just open `quant_plan.html` in a browser.

## Features

- **4-phase roadmap** — Apply & Foundations → Build Skills → Portfolio & Competition → Formal Credentials
- **Kanban board** — drag-and-drop task management across To Do / In Progress / Done
- **Progress tracking** — per-phase progress bars and a master progress indicator
- **Activity history** — full log of every status change with revert support
- **Timeline view** — month-by-month 12-month plan
- **Projects & Resources** — curated reference cards for portfolio projects and learning materials
- **Cross-device sync** — optional GitHub Gist sync via Personal Access Token
- **Search** — keyboard-accessible global search across all tasks and sections
- **Local persistence** — all state saved to `localStorage`, survives page refresh

## Usage

Open `quant_plan.html` directly in any modern browser. No installation required.

To enable cross-device sync, click the sync banner and enter a GitHub Personal Access Token with `gist` scope.

## Design

- **Font**: [Inter](https://rsms.me/inter/) for UI text; [JetBrains Mono](https://www.jetbrains.com/lp/mono/) for data values (numbers, dates, percentages)
- **Theme**: dark, with softened backgrounds and layered card shadows
- **Responsive**: single-column layout on screens under 900px

## Stack

Pure HTML, CSS, and vanilla JavaScript — everything in one file.
