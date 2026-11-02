---
description: Weekly receipts check on the women-in-tech wiki
---

Run a health check on `wiki/`, following CLAUDE.md, and write the results to `wiki/lint-report.md` (newest run at the top).

Check for:
- **Receipts that don't match:** every number on a wiki page must match its source page and raw source. List any mismatch with both values.
- **Contradictions** between sources or pages.
- **Stale stats:** anything older than 3 years, or superseded by a newer edition.
- **Orphans:** pages with no inbound links, and pages missing from `index.md`.
- **Voice check:** theme pages with no `🗣️ Real talk` or `💔 Why it matters`, and anywhere corporate-speak crept in.
- **Copyright check:** long passages copied from sources into any tracked file. Run `git ls-files` to see what's tracked. Also apply any extra checks in CLAUDE.local.md if it exists.
- **Missing concepts:** terms used in 3 or more pages that have no concept page.

Fix only the unambiguous issues (broken links, index gaps). Ask Zoe before changing a receipt. Append to `wiki/log.md`, then give her the summary in tea voice.
