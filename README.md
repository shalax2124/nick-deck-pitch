# HelloNancy × Nick Kyrgios — Campaign Clone

Editable working copy of the Nick Kyrgios x HelloNancy campaign proposal. Forked from the original Canva deck (DAHHvMvBp4M) and the Notion working docs in the carenbloom workspace.

## Why this exists

The Canva deck is the polished pitch. This repo is the **working canvas** — every asset, script, and tagline broken out so we can iterate on copy, swap visuals, and resolve open questions before production.

## Structure

```
.
├── README.md                  ← you are here
├── narrative/                 ← the campaign architecture, written down
│   ├── 00-architecture.md     ← phase 1 → phase 2 spine
│   ├── 01-phase-one.md        ← "The Lemon That Broke The Zen" — full script
│   ├── 02-phase-two.md        ← "The Kyrious Ball Launch" — full script
│   ├── 03-interview.md        ← Nick interview Q's (3 parts, 15 questions)
│   └── 04-rollout.md          ← day-by-day seeding plan (DRAFT — to align)
├── assets/
│   ├── storyboard/            ← AI key frames for Phase 1 + Phase 2 hero films
│   ├── products/              ← Lem product shots + UGC
│   ├── videos/                ← existing HelloNancy spots for tone reference
│   └── brand/                 ← logo, palette, typography (TODO)
├── slides/                    ← reserved for slide renders (TODO)
└── index.html                 ← single-page viewer
```

## Open questions (round 2 punch list)

- [ ] Day-1 seeding: which creator breaks the news? Anonymous tennis-insider account vs. named creator vs. Nick's friend on tour
- [ ] Phase 2 product reality: is "Kyrious Ball" a real SKU we ship, or film-only prop?
- [ ] Shoot window: Mallorca (Jun 18–21) primary, Stuttgart (Jun 5–7) hedge — confirm crew
- [ ] OOH locations: NYC + London approved? Australia (Melbourne) for home-court resonance?
- [ ] Doctor scene tone: rewrite to remove women-as-target subtext while keeping the joke
- [ ] Paid vs. organic budget split

## Sources

- **Canva pitch deck**: [DAHHvMvBp4M](https://canva.link/kryw2fsqh5hyqt7) (Crystal Lo, round 2 — May 2)
- **Notion narrative docs** (carenbloom workspace):
  - [PT1 — Phase 1 hero film script](https://www.notion.so/carenbloom/PT1-HELLO-NANCY-x-NICK-KYRGIOS-350af6a34372801fa8c1c5e55e8709b1)
  - [PT2 — Phase 2 hero film script](https://www.notion.so/carenbloom/PT2-HELLO-NANCY-x-NICK-KYRGIOS-350af6a343728053928ffef474c8d691)
  - [Interview Questions for Nick Kyrgios](https://www.notion.so/carenbloom/Interview-Questions-for-Nick-Kyrgios-350af6a343728000be67fcb6971ba2dc)
- **Reference**: CeraVe × Michael Cera (Super Bowl 2024) — 32B earned impressions, the campaign architecture this clones

## Editing flow

1. Edit a `narrative/*.md` → re-render `index.html`
2. Swap an image in `assets/` → it appears anywhere it's referenced
3. PR a new variant → discuss before pushing to Crystal
