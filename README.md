# Outer Tepenia 1

Game Design Docs for **Outer Tepenia 1** — a 1st-/3rd-person 3D open-world Sci-Fi RPG, set in orbit around Jupiter.

**Status:** early design (pre-Phase-1). See [`Dev-Road-Map/01-Completion-Matrix.md`](Dev-Road-Map/01-Completion-Matrix.md) for the authoritative status table, and [`TODO.md`](TODO.md) for a quick-glance list of what's next.

---

## What This Is

Outer Tepenia 1 is the third work in the shared **Tepenian universe** (named for Tepenia, the in-universe hybrid robot/human meta-civilization — not to be confused with Terran Lights, the real-world media production company producing all three works), chronologically downstream of two other properties:

- **[Inner Tepenia](https://github.com/TerranLights/InnerTepeniaGDD)** — a top-down, isometric, turn-based Sci-Fi RPG and spiritual successor to old-school Fallout, set in post-nuclear Antarctica (~2700s).
- **[The Cryptograph Helix](https://github.com/TerranLights/TheCryptographHelixDD)** — a 7-volume novel series (~3000s–3100s) about a DNA-based criminal resistance fighting a tech oligarchy, during which the outer solar system ("Outer Tepenia" — Jupiter and beyond) transitions from uncolonized frontier to settled territory.

Outer Tepenia 1 takes place roughly **1,000 years after the ending events of The Cryptograph Helix**, inheriting Inner Tepenia's robot-personhood/evacuee-diaspora history and Cryptograph Helix's DNA-tech/Jovian-frontier backdrop — but in a new format: real-time, open-world, 1st-/3rd-person, rather than turn-based prose-adjacent RPG or novel.

## Opening Premise

Modeled on the Fallout: New Vegas courier opening — a role and an inciting incident, not a scripted backstory. The player character is a **robot working as a Space Janitor in orbit around Jupiter**. Mid-shift, a third party steals the game's MacGuffin (tentatively a rare-composition energy drive) and triggers a "compactor process" that kills the player's partner and nearly kills the player. The player wakes up repaired in a mechanic's garage, goes through character creation, and the game begins. Full details: [`Storyline/Opening_Sequence.md`](Storyline/Opening_Sequence.md).

## Design Philosophy

Governed by three **Absolute Laws** — not allowed to be broken:

1. **Player Freedom & Agency Reigns Supreme** — nothing is obligatory.
2. **Old-School Fallout Is the Base Reference** — Fallout 1/2/New Vegas together are the central design reference; other games fill gaps Fallout doesn't cover.
3. **New Vegas Is the Gold Standard Within Fallout** — where Fallout 1/2 and New Vegas differ, New Vegas wins.

Everything else — narrative tone (no good endings, the player as witness), scope targets, world-design framework, and reference standards for flight/camera/combat — builds on top of these. Full doc: [`Game_Design_Principles.md`](Game_Design_Principles.md).

## Key Systems (in progress)

- **MACHINE stats** — the 7-attribute character system, carried over identically from Inner Tepenia and shared across the whole "[...] Tepenia" series.
- **NODE** — Tepenia's answer to VATS; body-part targeting integrated with MACHINE stats. Works like New Vegas's real-time VATS here, unlike Inner Tepenia's turn-based version.
- **Zero-g and verticality** — core traversal/combat mechanics, not incidental to an orbital setting.
- **Space flight** — referencing Everspace 2, CHORVS, and No Man's Sky (flight mechanics only).
- **DNA-as-tech** — carried forward from The Cryptograph Helix, intended as a real narrative thread rather than background flavor.
- **Item degradation and repair**, **full mod support**, and **romanceable companions** are also confirmed features.

## Repo Structure

| Path | Contents |
|------|----------|
| `Game_Design_Principles.md` | Binding design laws and principles — read this first |
| `Dev-Road-Map/` | Phased development roadmap, completion matrix, and open/blocking decisions |
| `TODO.md` | Lightweight, at-a-glance task tracker |
| `Storyline/` | Narrative content, starting with the opening sequence |
| `Game-Mechanics/` | Character creation, combat, perks, and core mechanics — much of this is still Inner Tepenia's copied content awaiting adaptation to real-time play; check each file for adaptation notes |
| `game comparisons.md`, `Steam_page_description.md` | Copied from Inner Tepenia as placeholders, not yet updated for this game |

## Reference Games

Fallout: New Vegas is the primary reference (see Absolute Laws above). Other confirmed references, scoped to specific systems: Fallout 4 (3rd-person camera), Everspace 2 / CHORVS / No Man's Sky (flight mechanics only), Horizon: Zero Dawn (camera, secondary).
