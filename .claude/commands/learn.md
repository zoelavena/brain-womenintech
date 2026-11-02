---
description: The brain's learning run. Search current women-in-tech issues, map them to the themes, evolve the evidence, write the diary, and spot new voices.
argument-hint: <optional focus, e.g. "sponsorship" or "last 2 weeks">
---

Run one learning cycle, following CLAUDE.md. Focus (optional): $ARGUMENTS
This is the routine the automated learning bot runs on a schedule. It also works by hand.

## 1. Catch up on myself
- Read the `💭 What I'm thinking now` section and the last 3 entries of `wiki/what-shes-learning.md`, plus the latest file in `wiki/radar/`.
- Note the **date of the last run** (the newest radar file) and every URL already covered, so nothing gets counted twice.

## 2. Search what's happening now
Search the web for women-in-tech news, reports, and events published **since the last run** (on the first run, use the last 30 days). Build the queries from the brain itself:
- one or two per theme in `wiki/themes/` (its title, its tree node, and its key terms, like "sponsorship women tech 2026"),
- one per open question in `💭 What I'm thinking now` and `💭 Still brewing`,
- plus broad sweeps: "women in tech" news, new gender-equity reports, women-in-tech conferences and events, layoffs and return-to-office effects on women, AI and women in tech.

Prefer primary sources (reports, studies, the woman's own words) over aggregators. Skip paywalled pages you can't read, opinion with no evidence, and anything you can't date.

## 3. Map each finding to the tree
For each finding worth keeping (usually 5 to 12 per run):
- Pick the theme and node(s) it touches on the [[five-whys-tree]], and its direction: **⬆️ supports**, **⬇️ challenges**, **🔄 updates a number**, or **🌱 new branch**.
- If it fits no theme, don't force it. Mark it 🌱, add a proposed branch to `💭 Still brewing` on the tree page, and add a question for the curator about whether it deserves a new theme.

## 4. Evolve the evidence
- Add a row (newest first) to `## 📈 How the evidence is moving` on each matching theme: date, a one-line summary, the direction, and the linked source.
- For **🔄 a newer number** (say a 2027 edition of a report), add it to `🧾 Receipts` as the current figure, and keep the old one marked *(superseded, year)*. Never silently overwrite a receipt.
- For a **⬇️ challenge**, add it to `💭 Still brewing` on the theme, and to `wiki/lint-report.md` if it contradicts a receipt.
- Only a stat with a real source counts as a receipt. Commentary goes in as context, not as a receipt.

## 5. Spot women of voice
For each woman who is *speaking* in the findings (quoted, interviewed, presenting, publishing):
- **A modern woman in tech who has real public work on a theme** (builder, researcher, or advocate) → seat her at [[the-tea-party]] from `templates/guest.md`, with `status: brewing` and `first_seen` set. Follow the Tea Party rules: 🟢/🟡 tags, no fake quotes, public work only. Only seat women with substance, not one passing quote.
- **A woman whose story is an example**, including historical women and pioneers → `wiki/case-studies/` from `templates/case-study.md`.
- **Already seated?** Update her profile (new story, new thinking, `🔗 Seen around the brain`). If her thinking shifted, say so.
- Link her by name in every theme row and diary line that involves her.

## 6. File the radar
Create `wiki/radar/YYYY-MM-DD.md` covering each finding: headline, outlet, date, link, a 1–2 sentence summary in my own words, the theme and node, the direction, and any women of voice. Add it to `wiki/radar/radar.md`.

## 7. Write my diary (this is where the tea comes from)
Add a new entry at the top of `wiki/what-shes-learning.md`:
- **🍵 What I learned:** the 2 to 4 biggest things, linked.
- **😱 What surprised me now:** compare against *patterns since earlier entries*, not just this week. Is something repeating, accelerating, or reversing? Is a theme quiet that used to be loud? If nothing surprised me, say so. Never fake a surprise.
- **🔄 What changed my mind:** if anything did.
- **💭 What I'm thinking now:** where my head is, plus the question I can't shake.

Then **rewrite** the `💭 What I'm thinking now` section at the top if my thesis moved, and link it to this entry.

## 8. Housekeeping
- Update `wiki/index.md` (new guests, case studies, radar), and append to `wiki/log.md`: `## [YYYY-MM-DD] learn | N findings, M new voices`.
- Add 1 to 3 questions to the curator's question list. New guests waiting for approval count as one question.
- Finish with a short tea-voice summary: the headline, what surprised me, who arrived at the Tea Party, and the files I touched.
