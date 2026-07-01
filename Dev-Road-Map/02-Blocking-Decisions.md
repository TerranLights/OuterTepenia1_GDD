# Blocking Decisions

Decisions and dependencies that need to resolve before substantive GDD work can proceed in the areas they affect.

---

## Decision 1: Faction Design — Blocked on Upstream Projects

**Status: OPEN, not blocking near-term work, but blocking all Phase 2+ faction content**

Outer Tepenia 1's factions are deliberately not being designed independently. The user's process is sequential across the whole universe: a faction roster is being built for Inner Tepenia first, which then evolves/expands into The Cryptograph Helix's factions, and whatever state that lands in becomes the foundation for Outer Tepenia 1's factions.

**This is not a decision to make here — it's a dependency to track.** Check Inner Tepenia and Cryptograph Helix faction docs for current state before ever proposing a finished Outer Tepenia faction.

---

## Decision 2: Opening Sequence Is Not Yet Written Into the GDD

**~~RESOLVED — June 2026~~**

**Decision:** Written up as `Storyline/Opening_Sequence.md`. The Space Janitor opening (partner death, MacGuffin theft, compactor process, mechanic's garage revival) now exists as an actual GDD document. Details beyond the confirmed sequence (antagonist identity, partner's name, MacGuffin's final nature) remain open — see Decision 5.

---

## Decision 3: Mechanics Framework — Adapt, Don't Adopt

**Status: RESOLVED (reference-level) — June 2026. Detailed design still pending, but no longer a blocking decision.**

The copied Inner Tepenia `Game-Mechanics/` folder is split into three tiers, not one blanket "reference-only" bucket:
- **MACHINE stats: RESOLVED — direct, identical carryover.** Not adapted, not reinterpreted. Binding and canonical across the entire series (Inner Tepenia, Outer Tepenia 1, Outer Tepenia 2, Outer Tepenia: New Centauri). See `Game_Design_Principles.md` — Series-Wide Systems.
- **Perks/skills: RESOLVED — mostly carry over, subject to contextual adjustment.** Strong default, not frozen; individual perks/skills may be added, cut, or adjusted per what each game's context needs.
- **AP combat system: RESOLVED — Fallout: New Vegas's AP/VATS model is the fundamental basis** (real-time combat with an AP-gated targeted-action system), not Fallout 1/2's turn-based grid-AP model. This is a direct application of Absolute Law 3. Adjustments for the outer-space/zero-g context are expected. See `Game_Design_Principles.md` — Reference Principles, "Confirmed application — AP Combat System."
- **Camera system: RESOLVED — Fallout 4's free 360° 3rd-person camera is the base reference**, with No Man's Sky and Horizon: Zero Dawn as secondary references; 1st-person is standard. See `Game_Design_Principles.md` — Camera Reference Standard.

None of these are blocking anymore — the reference points are set. What remains is normal Phase 1 design work (fleshing out the actual AP costs, action list, camera feel details, etc.), not an open decision.

---

## Decision 4: Multiple Truths Principle — Adopt or Drop

**Status: OPEN — not blocking, can be revisited any time**

Inner Tepenia's "Subnets Are Six Different Truths" device has no confirmed Outer Tepenia equivalent. DNA-as-tech has been floated as a plausible mechanism if the user wants an equivalent, but this is explicitly undecided. Low urgency — doesn't block other phases, but should be resolved before Phase 5 (Quests and Story) locks in the main narrative structure, since it would shape how the story is told.

---

## Decision 5: MacGuffin and Antagonist Details

**Status: OPEN — not blocking Phase 1, will block Phase 3 and Phase 5**

The MacGuffin is tentatively an energy drive of rare/unique composition (open to alternatives). The antagonist who steals it ("not-Benny") exists only as a role/parallel, with no character design. Both need to be locked in before companion/antagonist character work (Phase 3) or main quest structure (Phase 5) can proceed.
