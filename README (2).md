# OpsBoard — Executive Assistant Operations Dashboard

> Built by Carrie-Ann Bennett | Executive Assistant & Office Manager | 8 Years Experience

---

## A bit about this project

I built this dashboard myself — from a blank spreadsheet, step by step.

As an Executive Assistant with 8 years of experience working remotely, I've always believed that great support isn't just about managing diaries and booking travel. It's about building systems that help executives make better decisions, stay on top of priorities, and never miss what matters.

OpsBoard is my way of showing that. It's a real, working operations dashboard that I designed, built, and would use in my day-to-day role.

---

## What it does

OpsBoard is a two-part project — an Excel workbook and a live web dashboard — both tracking the same thing: the operational workload of an executive office.

### The Excel Version (OpsBoard.xlsx)

A professional multi-sheet workbook built entirely in Excel:

- **Executive Dashboard** — opens first, showing 4 live KPI cards: Total Open Tasks, In Progress, Completion Rate, and Overdue. Every number updates automatically when you change data in the Task Tracker.
- **Task Tracker** — the data engine. Log tasks with dropdown menus for Category, Priority (Critical / High / Medium / Low) and Status (Not Started / In Progress / Awaiting Approval / Delegated / Done). Colour-coding applies automatically.
- **Meeting Log** — track executive meetings, agenda status, minutes, and follow-up actions.
- **Key Contacts** — a stakeholder directory with priority ratings and category tags.

### The Web Version (index.html)

A live browser-based dashboard with the same features, built in HTML. No installation needed — just open it in any browser.

---

## Excel skills this project demonstrates

I want to be transparent about what I built and what each piece shows:

| Feature | Excel Skill |
|---|---|
| KPI cards updating live | COUNTIF, COUNTIFS, COUNTA formulas |
| Completion Rate percentage | IFERROR + division formula |
| Overdue detection | COUNTIFS with TODAY() and date logic |
| Live date in the header | TEXT(TODAY()) formula |
| Days Until Due column | Date subtraction with IF for blank handling |
| ⚠ Alert column | Nested IF + AND logic |
| Colour-coded Priority and Status | Conditional Formatting rules |
| Dropdown menus | Data Validation lists |
| Dashboard linked to Task Tracker | Cross-sheet formula referencing |

---

## How I built it

I didn't download a template. I didn't copy someone else's work.

I started with a completely blank Excel file and built every cell, every formula, every colour rule, and every dropdown one step at a time. That process taught me more than any course because I had to understand *why* each formula works, not just *that* it works.

The steps I followed:

1. Set up the workbook structure and title banner
2. Built the Task Tracker with headers, data, and dropdown menus
3. Added conditional formatting for automatic colour coding
4. Wrote the formulas — Days Until Due, overdue detection, completion alerts
5. Built the Executive Dashboard with live KPI cards linked to the Task Tracker
6. Final polish — removed gridlines, froze header rows, added borders

---

## About me

I'm Carrie-Ann, an Executive Assistant based in Cape Town, South Africa with 8 years of remote EA and Office Manager experience.

I built this project because I believe the best EAs don't just *use* systems — they *build* them. I'm actively growing my Excel and digital skills because I know that in this role, the ability to organise information clearly and present it professionally is just as important as any other skill.

If you're looking for an EA who takes initiative, thinks operationally, and brings structure to complexity — I'd love to connect.

📍 Cape Town, South Africa
💼 LinkedIn: *coming soon*

---

## Files in this repo

| File | What it is |
|---|---|
| `OpsBoard.xlsx` | The Excel dashboard — download and open in Excel |
| `index.html` | The web version — open in any browser |
| `README.md` | This file |

---

*Built with Excel — and a lot of determination.* 💪

