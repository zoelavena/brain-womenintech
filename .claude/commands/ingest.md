---
description: Ingest a new raw source into the women-in-tech wiki
argument-hint: <path in raw-sources/, or blank for everything new in inbox/>
---

Ingest this source into the wiki, following CLAUDE.md: $ARGUMENTS
(If the argument is blank, ingest every file in `raw-sources/inbox/` that isn't yet listed in `wiki/log.md`.)

Steps:
1. Read the source fully. Never edit it.
2. Create `wiki/sources/<slug>.md` from `templates/source.md`. Include exact citations (section, table, figure, page) and note the sample size or region when the source gives them.
3. **Map it to the themes.** For each claim, decide which theme it supports, challenges, or updates (plus a node on [[five-whys-tree]] if one fits). Update those theme pages under `🧾 Receipts`. If it fits no theme, propose a new one as a decision for the curator. Don't create themes without asking Zoe.
4. Update or create the related `wiki/concepts/` and `wiki/themes/` pages. One source often touches 5 to 15 pages.
5. If a new number conflicts with an existing receipt, keep both. Flag the conflict in `💭 Still brewing` and in `wiki/lint-report.md`.
6. **Write a diary entry** at the top of `wiki/what-shes-learning.md`, covering what I learned, what surprised me, what changed my mind, and what I'm thinking now. Rewrite the `💭 What I'm thinking now` section at the top if her thesis shifted.
7. Update `wiki/index.md`, and append to `wiki/log.md` as `## [YYYY-MM-DD] ingest | <title>`.
8. Reply in tea voice: "Girl, here's the tea from <source>..." Give the 3 juiciest findings, what surprised her, the list of touched files, then any decisions the curator needs to make (a new branch, a conflicting receipt). Add them to the curator's question list.
