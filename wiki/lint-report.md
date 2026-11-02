---
type: lint
updated: 2026-11-02
---

# 🧹 Lint report

## [2026-11-02] First pass

### 🚩 Receipts that don't match
1. **Node 4.2 on shestriplethreat.com:** the site shows *Women 15.1% / Men 19.8%* with the caption "Took a break for professional development". The board only gives men's figure for this (19.8%), and 15.1% is the **US unpaid care** stat from 4.1. It looks like a copy-paste slip on the live site. **Action:** check WEF 2026 Section 2.1 for women's real professional development break rate, then fix `assets/five-whys-data.js` on the site. → [[workplace-policy]]

### ⚠️ Unverified receipts
- Every WEF and Toast number in the wiki was transcribed from the board, **not from the original reports**. Add the reports to `raw-sources/reports/` and run `/ingest`.

### 💔 Voice check
- 🗣️ Real talk is empty everywhere, because no women have been met yet. Each theme page now says what kinds of stories to look for. → `/meet`
- 4.6 uses a government stat to stand in for tech. It's labeled, but a tech-specific source would be better.
