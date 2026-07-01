# Outer Tepenia 1 — Development Roadmap

## What This Is

A structured development roadmap for the Outer Tepenia 1 GDD, mirroring the format used for Inner Tepenia's roadmap. Unlike Inner Tepenia's roadmap (written mid-development, ~50-55% complete), this one starts at the very beginning — most phases below are scope descriptions of work not yet started, not progress reports.

This roadmap covers GDD work only — it is not a production or implementation plan. It orders and prioritizes the design documents, decisions, and written content that need to exist before the GDD is complete enough to hand to an implementation team.

---

## How to Read This

**The roadmap is split into seven phases**, each in its own file:

| File | Phase | What It Covers |
|------|-------|----------------|
| `02-Blocking-Decisions.md` | Pre-Phase | Decisions/dependencies that must resolve before certain work can proceed |
| `03-Phase-1-Foundations.md` | Phase 1 | Adapt the copied Inner Tepenia mechanics reference into Outer Tepenia's own real-time framework; finalize opening sequence details |
| `04-Phase-2-Factions-and-World.md` | Phase 2 | Faction design (dependent on upstream Inner Tepenia/Cryptograph Helix work); settlement design |
| `05-Phase-3-Characters.md` | Phase 3 | Companions (including romanceable), the antagonist ("not-Benny"), other named NPCs |
| `06-Phase-4-Perks-and-Progression.md` | Phase 4 | Stat/skill/perk system adapted for real-time play |
| `07-Phase-5-Quests-and-Story.md` | Phase 5 | Main quest, side content, DNA-as-tech narrative integration |
| `08-Phase-6-World-Depth.md` | Phase 6 | Individual moon/station/settlement cultural depth |
| `09-Phase-7-Long-Term.md` | Phase 7 | DLC planning, sequel setup (feeds Outer Tepenia 2 / New Centauri) |

For old-school Fallout design analysis, consult Inner Tepenia's `10-Fallout-Design-Reference.md` directly rather than duplicating it here — the Absolute Laws in `Game_Design_Principles.md` govern how it applies to Outer Tepenia.

The **Completion Matrix** (`01-Completion-Matrix.md`) is the single-source status table. Update it as work is completed.

---

## Current State (June 2026)

**Overall completion: pre-Phase-1.** What exists so far is philosophy and premise, not systems or content:

What is solid:
- Absolute Laws and Game Design Principles (player freedom, Fallout/NV precedence, flight reference standard, scope standards, Environment/Control/Access framework)
- Universe timeline placement (~1,000 years after The Cryptograph Helix)
- Opening premise: Space Janitor in Jovian orbit, partner killed, MacGuffin (tentatively an energy drive) stolen by an unnamed antagonist ("not-Benny"), "not-Doc Mitchell" mechanic's garage revival into character creation
- Genre/format decisions: open-world, 1st-/3rd-person toggle, zero-g and space flight as mechanics (not thematic centerpieces), DNA-as-tech as a real narrative thread

What is incomplete, in priority order:
1. Blocking decisions and dependencies (see `02-Blocking-Decisions.md`)
2. Writing the opening premise into an actual Storyline doc (currently only established in discussion — not yet in the GDD)
3. Mechanics adaptation — none of the copied Inner Tepenia Game-Mechanics content has been converted to Outer Tepenia's real-time format
4. Faction design — blocked on upstream Inner Tepenia/Cryptograph Helix faction work
5. Everything else (characters, perks, quests, world depth, DLC) — not started

---

## Guiding Principles for This Roadmap

### Order follows dependency
Faction questlines cannot be written before factions exist. Perks cannot be written before the progression system is adapted. Settlement lore cannot be finalized before the Environment/Control/Access framework has real settlements to apply it to.

### The Absolute Laws are non-negotiable; everything else can move
Player freedom, the Fallout/NV reference hierarchy, and gap-filling from other games (Law 2/3) govern every decision in every phase. Everything else in `Game_Design_Principles.md` — scope numbers, the Environment/Control/Access framework, the undecided Multiple Truths principle — can still evolve.

### Systems before content
A quest that references a faction that isn't designed is a quest built on sand. This is doubly true here since Outer Tepenia's mechanics framework doesn't exist yet — it's only a copied, non-binding reference from a different genre of game (turn-based isometric vs. real-time open-world).

### Don't get ahead of upstream projects
Faction design specifically must wait on Inner Tepenia's faction roster and its evolution through The Cryptograph Helix. Don't invent Outer Tepenia factions independently of that chain.

---

## Dependencies Map

```
Blocking Decisions
    └── Phase 1 (Foundations: mechanics adaptation, opening sequence write-up)
            ├── Phase 2 (Factions + World) ← Factions sub-item blocked on upstream projects
            │       ├── Phase 3 (Characters) ← also depends on Phase 1
            │       ├── Phase 4 (Perks + Progression) ← also depends on Phase 1 + 3
            │       └── Phase 5 (Quests + Story) ← depends on Phase 2 + 3
            └── Phase 6 (World Depth) ← can run parallel to Phase 3-5, needs settlements from Phase 2
Phase 7 (Long-Term) ← depends on Phase 5 + 6
```
