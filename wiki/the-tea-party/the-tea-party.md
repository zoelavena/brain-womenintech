---
type: index
updated: 2026-11-02
---

# ☕ The Tea Party

Pull up a chair, girl. This is a curated library of **women in tech today**: the builders, researchers, and advocates shaping the conversation right now. Each guest has her stories, a short quote or two, and **🔮 how I think she thinks**, my perceived profile of her public work. Every line is tagged 🟢 *she said it* or 🟡 *my read*.

You'll find them all through the research, too. Whenever a theme or a tree node touches someone's work, she's linked by name.

## Who's at the table

| Seat | Guest | Known for | Shows up at |
|---|---|---|---|
| 🛠️ builder | [[tanya-reilly\|Tanya Reilly]] | Naming "glue work" | [[evidence-gap]] |
| 🛠️ builder | [[lara-hogan\|Lara Hogan]] | What sponsorship actually looks like | [[sponsorship-gap]] |
| 📣 advocate | [[reshma-saujani\|Reshma Saujani]] | Girls Who Code, "bravery, not perfection" | [[pipeline-and-education]], [[evidence-gap]] |

```dataview
TABLE seat AS "Seat", known_for AS "Known for", why_ids AS "Tree nodes"
FROM "wiki/the-tea-party"
WHERE type = "guest"
SORT seat ASC, file.name ASC
```

## The seats
- 🛠️ **Builders** are women working in tech.
- 🔬 **Researchers** are women in tech who study gender, careers, and sponsorship in tech.
- 📣 **Advocates** founded or lead women-in-tech orgs and movements.

Historical women and pioneers don't get a seat. They're well documented elsewhere. But their stories still teach us, so they live in [[case-studies]], alongside any other woman whose story the research uses as an example.

## 🆕 Just arrived
New voices that the learning bot spots in recent news and events arrive with `status: brewing`, and the curator decides whether they keep their seat.

```dataview
LIST known_for
FROM "wiki/the-tea-party"
WHERE type = "guest" AND status = "brewing"
SORT file.ctime DESC
```

## Who's next?
Know a woman who belongs at this table? Open an issue or PR with a link to her interview, talk, or writing.
