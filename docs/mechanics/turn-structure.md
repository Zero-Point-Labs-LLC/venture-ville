# Turn Structure

**Status:** ⚠️ NEEDS DEVELOPMENT (Critical Priority)  
**Last Updated:** 2026-03-22  
**Dependencies:** ALL systems

---

## Problem Statement

The game currently lacks a defined **turn loop**.

**Required:**
- Full action sequence (what happens each turn?)
- Resource production timing (when do players collect?)
- Build timing (when can you build Talent/Nodes?)
- Card timing (when are Progress Cards drawn/played?)
- Market Event timing (when do 7-rolls trigger?)

**This is the critical blocker for:**
- Balance testing
- Playtesting
- System cohesion
- Game pacing validation

---

## Design Requirements

### Must Include

1. **Resource Production Phase** — How/when players generate resources
2. **Build Phase** — When Talent pieces and Roadmap nodes are built
3. **Card Phase** — When Progress Cards are drawn and played
4. **Event Phase** — When Market Events trigger (7-rolls)
5. **Funding Phase** — When funding checks happen (if per-turn)

### Pacing Constraints

From master design:
- **Target length:** 20-30 turns per player
- **Early game:** Capability divergence
- **Mid game:** Convergence + friction
- **Late game:** Platform dominance

**Turn structure must support this arc.**

---

## Open Questions

### Critical (Answer First)

- [ ] **Resource production topology** — How are resources generated?
  - Roll dice for resource hexes (Catan-style)?
  - Fixed production (worker placement)?
  - Card-based (deck draws)?

- [ ] **Action economy** — How many actions per turn?
  - Free build + special action?
  - Action points to spend?
  - Phase-based (everyone does X, then Y)?

- [ ] **Turn order** — Simultaneous or sequential?
  - Clockwise rotation?
  - First player token?
  - Bidding for turn order?

### High Priority

- [ ] **Progress Card timing** — When drawn?
  - After resource production?
  - Separate card phase?
  - Discipline dice rolled when?

- [ ] **Market Event timing** — When resolved?
  - Immediate on 7-roll?
  - End of turn?
  - Start of next turn?

- [ ] **Funding check frequency** — How often?
  - Every turn?
  - Only on Market Events?
  - Fixed turn intervals?

---

## Proposed Turn Sequence v0.1 (Rough Draft)

**For discussion:**

1. **Roll Dice** — Resource production + discipline check
2. **Produce Resources** — Collect based on roll
3. **Draw Progress Card** (if applicable)
4. **Build Phase** — Spend resources to build Talent/Nodes
5. **Play Cards** (optional) — Use Progress Cards
6. **Market Event** (if 7 rolled) — Time + Event trigger
7. **End Turn** — Pass to next player

**This is highly tentative and needs refinement.**

---

## Design Principles to Follow

1. **Clarity over cleverness** — Simple is better
2. **Consistent pacing** — Each turn should feel similar in duration
3. **Minimize downtime** — Keep non-active players engaged
4. **Thematic coherence** — Actions should make narrative sense

---

## Alternatives to Consider

### Resource Production

**Option A: Dice + Hexes (Catan)**
- Roll 2d6, collect from hexes matching numbers
- Familiar, proven mechanic
- May feel derivative

**Option B: Fixed Production Tracks**
- Each turn, advance production marker
- Predictable, strategic
- Less exciting

**Option C: Card-Based**
- Draw resource cards each turn
- Controlled randomness
- Slower, more fiddly

### Action Economy

**Option A: Free Build + Special**
- One build action per turn + one special ability
- Simple, fast
- May limit strategic depth

**Option B: Action Points**
- 3 action points, spend as desired
- Flexible, deep
- Slower analysis paralysis risk

**Option C: Phase-Based**
- Everyone produces, everyone builds, etc.
- Simultaneous, fast
- Less interactive

---

## Dependencies

**This system integrates:**
- Resource System (production timing)
- Talent System (build timing)
- Roadmap Trees (node unlock timing)
- Progress Cards (draw/play timing)
- Market Events (trigger timing)
- Funding Timeline (check timing)
- Advancement Tracks (progress timing)

**Critical:** Turn structure design unlocks all other systems.

---

## Next Steps

1. **Prototype Turn Sequence** — Create v1.0 draft
2. **Paper Playtest** — Test with simple resource/build rules
3. **Iterate** — Refine based on pacing feel
4. **Lock Structure** — Finalize and document

---

## Related Documents

- **ALL mechanics docs** depend on turn structure
- [MASTER-DESIGN.md](../../MASTER-DESIGN.md) — Overall pacing goals
- [DESIGN-TRACKER.md](../../DESIGN-TRACKER.md) — Track turn structure as critical milestone
