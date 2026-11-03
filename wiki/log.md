---
type: log
---

# 📓 Log

Append-only. Newest at the bottom. Format: `## [YYYY-MM-DD] operation | title`

## [2026-11-02] setup | Brain scaffolded
- Created the vault structure, CLAUDE.md schema, slash commands (`/ingest`, `/ask`, `/brain-dump`, `/lint`), and templates.
- Raw-saved the FigJam board export (`raw-sources/figma/`) and the site's Five Whys data (`raw-sources/site/`).

## [2026-11-02] ingest | Zoe's research (shestriplethreat.com + working notes)
- Built [[five-whys-tree]], 8 theme pages, 4 concept pages, 4 source pages, and 4 "me" pages.
- The receipts come from Zoe's board. The original WEF and Toast reports haven't been ingested yet.
- Flagged 1 receipt mismatch in [[lint-report]].

## [2026-11-02] setup | Real talk = women's voices, not Zoe's
- 🗣️ Real talk now holds anecdotes from women in tech, taken from interviews and articles. It no longer holds Zoe's own experience.
- Added `/meet`, `templates/woman.md`, `wiki/women/`, and `raw-sources/voices/`. `/brain-dump` now captures Zoe's takes and reactions.
- Rewrote the curator's question list and the Real talk prompts on all 8 theme pages.

## [2026-11-02] setup | Public, curated brain
- The repo is public. Raw clippings and reports are git-ignored, and curator working files stay local.
- Retired `wiki/me/`.
- Added curator vs visitor modes, `/tour`, the brain's voice (🧠), and her diary [[what-shes-learning]].
- Origin framing: the brain started from Zoe's research on shestriplethreat.com, and this is its evolution.

## [2026-11-02] meet | The Tea Party opens
- Renamed `wiki/women/` to [[the-tea-party]] and added `templates/guest.md`, with seats and the 🔮 perceived profile (🟢/🟡 tagging).
- Seated [[tanya-reilly]], [[lara-hogan]], [[herminia-ibarra]], [[reshma-saujani]], and [[anita-borg]].
- Linked the guests into the tree, 4 themes, 2 concepts, and the diary.

## [2026-11-02] setup | Learning loop
- The Tea Party is now modern women in tech only. Pioneers moved to [[case-studies]] ([[anita-borg]]).
- Added `/learn`, the [[radar]] and its template, and a `📈 How the evidence is moving` table on every theme.

## [2026-11-02] setup | Parked "Zoe's take"
- Removed the `🫖 Zoe's take` sections, `/brain-dump`, and the journal (to revisit later). Lines quoted from the original research now sit under `🎨 From the original research`.

## [2026-11-02] setup | Curator decisions
- New emerging theme: [[ai-and-the-future-of-women-in-tech]], grown out of node 3.1 and added to the tree.
- [[herminia-ibarra]] moved from the Tea Party to [[case-studies]] because her research covers every industry.
- Dropped the node 4.2 site check. Curator decisions are now strictly about the women-in-tech research.
- The WEF 2026 and Toast 2026 reports still need to be added to `raw-sources/reports/` by hand.

## [2026-11-02] setup | A general women-in-tech brain
- Themes are now one flat, equal list. Removed the "in scope" and "out of scope" labels and the root-path framing.
- The Five Whys tree is now "Where it started", with every branch drawn equal. Renamed the original notes to [[zoe-research-notes]].

## [2026-11-02] learn | First learning run: 5 findings, 0 new voices
- Filed [[2026-11-02]] in the radar (30-day window, Oct 3 – Nov 2, 2026): Web Summit Gender in Tech 2026 (AI impact + pay fairness; mid-career squeeze), LinkedIn AI hiring research, Web Summit State of the Industry survey, GHC 2026 cancellation (filed as didn't-fit).
- Evolved the evidence on [[ai-and-the-future-of-women-in-tech]], [[caregiving-and-social-norms]], [[hiring-and-promotion-bias]], and [[workplace-policy]]; added Jayeeta Putatunda's story to Real talk on the AI theme.
- Wrote the diary entry in [[what-shes-learning]] and rewrote "What I'm thinking now".
- Voices heard but not seated: Sarah Steinberg, Jayeeta Putatunda, Brenda Darden Wilkerson — single-quote sources in this run; Wilkerson flagged for a future /meet. No Tea Party seats added.

## [2026-11-02] meet | Brenda Darden Wilkerson
- Seated [[brenda-darden-wilkerson]] at [[the-tea-party]] (advocate, status: brewing) from interviews (Fotis Georgiadis / Candice Georgiadis), the AnitaB.org GHC cancellation statement (via AfroTech), and TechTimes' LinkedIn AI hiring coverage. Clipping saved to `raw-sources/voices/` (git-ignored).
- Placed her story on [[pipeline-and-education]], [[exposure-gap]], and [[sponsorship-gap]] (Real talk), linked her on the [[five-whys-tree]] (2.1, 5.2), and wrote the diary entry in [[what-shes-learning]].
- Her two-mentor advice refines node 5.2 (mentors interpret/navigate; sponsors advocate). Promotion from brewing to steeped is a curator decision.

## [2026-11-02] learn | Evening run at Zoe's direction: 2 findings, 0 new voices
- Filed [[2026-11-02-evening]] in the radar: Artemis Canada 2026 salary survey (women in Canadian tech leadership earn ~78 cents on the dollar; median base $152,000 vs $194,500) and ISACA 2026 Tech Workplace and Culture survey (47% of women experienced gender discrimination, up from 42% in 2024). Both evolved the evidence on [[hiring-and-promotion-bias]].
- The third stat Zoe named (31% say AI improved gender equality) was already filed in the morning run and was not duplicated.
- Artemis is from April 2026, outside the usual 30-day window; included because the curator asked for it directly. Its medians are self-reported survey data with no stated sample size — filed as receipts with that caveat.
- Wrote the diary entry in [[what-shes-learning]]. No Tea Party seats added; Julia Hermann (ISACA/SheLeadsTech) was heard but not seated — single-quote source.

## [2026-11-02] learn | Night run at Zoe's direction: 1 finding, 0 new voices
- Filed [[2026-11-02-night]] in the radar: Van Koevering & Field (Johns Hopkins, COLM 2026) — women-associated prompt features drew shorter, less sophisticated, less formal outputs across 4 models; LLM judge picked male-associated output as more competent in 69.4% of decided comparisons (preliminary, mostly ties; verified in the paper, Table 7).
- Evolved the evidence on [[ai-and-the-future-of-women-in-tech]] and [[hiring-and-promotion-bias]]; wrote the diary entry in [[what-shes-learning]].
- Voices heard but not seated: Katherine Van Koevering, Anjalie Field — single-study sources in this run; Field flagged as a /meet candidate.

## [2026-11-02] learn | Scheduled nightly run (late): 3 findings, 0 new voices
- First scheduled run started clean, then stopped per the dirty-tree rule when the in-chat JHU learn wrote to the tree mid-run; it filed nothing. Completed in a follow-up pass once the tree was clean and pushed (HEAD bd27cd7).
- Filed [[2026-11-02-late]] in the radar: Philadelphia Fed automation-risk analysis (21% vs 10% high-risk; 9% vs 13% AI-growth; scenario analysis, not predictions), GOV.UK Women in Tech Taskforce voluntary standards (22% IT workforce; 2p/£1 VC), Prosperity Project (women of colour in leadership 19.7% → 14.6%; 4% of executive-officer seats).
- Evolved the evidence on [[ai-and-the-future-of-women-in-tech]], [[workplace-policy]], [[hiring-and-promotion-bias]], and [[sponsorship-gap]] (Real talk); wrote the diary entry in [[what-shes-learning]].
- Voices heard but not seated: Julie Savard-Shaw, Barnini Bhattacharyya, Vicky Foxcroft, Anne-Marie Imafidon — single-source quotes in this run; Imafidon and Savard-Shaw flagged as /meet candidates.

## [2026-11-02] meet | Anjalie Field
- Seated [[anjalie-field]] at [[the-tea-party]] (researcher, status: brewing) from the JHU Hub release (Sept 21, 2026), the JHU faculty Q&A, and the COLM 2026 paper. Clipping saved to `raw-sources/voices/` (git-ignored).
- Placed her story on [[ai-and-the-future-of-women-in-tech]] and [[hiring-and-promotion-bias]] (Real talk), linked her in both themes' evidence rows, and wrote the diary entry in [[what-shes-learning]].
- Promotion from brewing to steeped is a curator decision.
