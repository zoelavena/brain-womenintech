---
type: why-node
status: spilled
scope: in-scope
why_id: "1"
sources: ["[[wef-global-gender-gap-2026]]", "[[toast-gender-equity-2026]]", "[[zoe-wwc-board-2026]]"]
updated: 2026-11-02
---

# 🌳 Why are there so few women leading in tech?

## ☕ The tea

Girl, it's not a skills problem. Zoe asked "why?" five times and kept landing in the same place: **no one is advocating for women in the room** (4.5). Three separate paths lead there: the work women do doesn't get counted, they get handed relationship work instead of resource work, and even with the same experience they aren't picked.

## The tree

Solid lines are on the path to the root cause. Dotted lines are branches Zoe ruled **out of scope** for this talk. They're kept here on purpose, because they're still real.

```mermaid
flowchart TD
    N1["1 · Why so few women leading in tech?<br/>38.9% entry-level → 17.6% C-suite"]
    N21["2.1 · Fewer women start in tech"]:::oos
    N31["3.1 · New tech roles: women land in lower-paid ones"]:::oos
    TP["Pipeline & education issue"]:::term
    N22["2.2 · Women step away or leave mid-career"]
    N33["3.3 · Caregiving pulls them out, and costs them more"]:::oos
    N41["4.1 · Care work still falls mostly on women"]:::oos
    N42["4.2 · Men step away to grow, women to care"]:::oos
    TC["Caregiving & social norms issue"]:::term
    TPol["Workplace policy issue"]:::term
    N32["3.2 · Women don't see a path to advance here"]
    N43["4.3 · Companies don't make the path visible"]:::oos
    TM["Org measurement issue"]:::term
    N44["4.4 · Extra work doesn't pay off for them"]
    N51["5.1 · The work isn't counted as leadership"]
    N23["2.3 · Women aren't chosen at the jump to leadership"]
    N34["3.4 · Relationship work, not resource work"]
    N46["4.6 · Steered to people roles; men to budget & influence"]
    N54["5.4 · Budget & headcount at stake → default goes to men"]
    N35["3.5 · Same experience, less likely to be picked"]
    N47["4.7 · Bias in the decision process"]:::oos
    TB["Hiring & promotion bias issue"]:::term
    N45(["4.5 · ROOT CAUSE<br/>No one is advocating for them in the room"]):::root
    N52["5.2 · Mentorship gets mistaken for sponsorship"]
    N53["5.3 · Sponsorship is informal; leaders aren't trained"]:::company

    N1 -.-> N21 -.-> N31 -.-> TP
    N1 --> N22
    N1 --> N23
    N22 -.-> N33
    N33 -.-> N41 -.-> TC
    N33 -.-> N42 -.-> TPol
    N22 --> N32
    N32 -.-> N43 -.-> TM
    N32 --> N44 --> N51 --> N45
    N32 --> N45
    N23 --> N34 --> N46 --> N54 --> N45
    N23 --> N35
    N35 -.-> N47 -.-> TB
    N35 --> N45
    N45 --> N52
    N45 -.-> N53

    classDef oos fill:#eee,stroke:#999,color:#555,stroke-dasharray: 4 3
    classDef term fill:#fff,stroke:#bbb,color:#777
    classDef root fill:#e0457b,stroke:#a3164c,color:#fff
    classDef company fill:#fde7ef,stroke:#e0457b,color:#7a1239
```

## 🧭 Where each branch lives in the brain

| Node | Branch | Page |
|---|---|---|
| 4.5, 5.2, 5.3 | Root cause: sponsorship | [[sponsorship-gap]] |
| 3.2 → 4.4 → 5.1 | Evidence gap | [[evidence-gap]] |
| 2.3 → 3.4 → 4.6 → 5.4 | Exposure gap | [[exposure-gap]] |
| 3.5, 4.7 | Hiring & promotion bias | [[hiring-and-promotion-bias]] |
| 2.1, 3.1 | Pipeline & education *(out of scope)* | [[pipeline-and-education]] |
| 3.3, 4.1 | Caregiving & social norms *(out of scope)* | [[caregiving-and-social-norms]] |
| 4.2 | Workplace policy *(out of scope)* | [[workplace-policy]] |
| 4.3 | Organizational measurement *(out of scope)* | [[organizational-measurement]] |

## 🧾 Receipts

See the node pages above. Every number on the tree comes from [[wef-global-gender-gap-2026]] or [[toast-gender-equity-2026]], as recorded on [[zoe-wwc-board-2026]].
⚠️ The numbers were copied from Zoe's board and haven't yet been checked against the original reports. See [[lint-report]].

## 🎨 From the original research

> "Skill gap that leadership thinks it's seeing is actually an exposure gap."
> "A small change we can do is to become sponsors for our kind."
> ([[zoe-wwc-board-2026]])

## 💭 Still brewing

- The **solution side** of the tree is thin. 5.3 ("Formalize sponsorship. Train it like a skill.") is the only node about the company's role. What else belongs there?
- The why chain still doesn't explain why fewer women study STEM in the first place (Zoe flagged this herself on 2.1).
- Proposed branches will appear here as new sources get ingested.

## ☕ Who's at the table

| Node | Guests |
|---|---|
| 2.1 pipeline | [[reshma-saujani\|Reshma Saujani]] |
| 4.4 → 5.1 evidence gap | [[tanya-reilly\|Tanya Reilly]] |
| 4.5 root cause | [[herminia-ibarra\|Herminia Ibarra]], [[lara-hogan\|Lara Hogan]] · case study: [[anita-borg\|Anita Borg]] |
| 5.2 mentorship ≠ sponsorship | [[herminia-ibarra\|Herminia Ibarra]], [[lara-hogan\|Lara Hogan]] |
| 5.3 sponsorship is informal | [[lara-hogan\|Lara Hogan]] |

The full library is at [[the-tea-party]]. Women used as examples (pioneers and others) are in [[case-studies]].

## 🔗 Connected tea

[[triple-threat-framework]] · [[three-kinds-of-gaps]] · [[wwc-nyc-2026-talk]] · [[mentor-coach-sponsor]]
