# Funding Progression System

**Status:** ✅ Philosophy locked, ⚠️ Mechanics TBD  
**Last Updated:** 2026-03-22  
**Dependencies:** Market Events (Time advancement)

---

## Problem Statement

The game needs:
- **Macro pacing pressure** — Long-term strategic deadlines
- **Persistent power growth** — Structural scaling over time
- **Individualized risk** — Each player faces unique challenges
- **Thematic runway tension** — "Are we going to make payroll?"

---

## Solution: Individual Funding Timelines

Each company follows a **Funding Timeline** that acts as persistent structural power growth.

### Funding Stages

```
Seed → Series A → Series B → Series C → IPO
```

**Each stage unlocks:**
- Increased build capacity
- Asset protection
- Resource throughput bonuses
- Upgrade tier access
- Endgame scoring leverage

---

## Advancement Triggers

### How Funding Advances

**Option 1: Automatic Time-Based**
- Advance one stage every X Market Events
- All players progress together (global pressure)

**Option 2: Achievement-Based**
- Unlock next stage by hitting milestones (Users, Money, Nodes)
- Players progress independently (individualized)

**Option 3: Player Choice**
- Spend resources/users to "raise funding"
- Creates strategic timing decisions

**Decision:** TBD based on turn structure

---

## Funding Pressure Mechanic

### When Time Advances (Market Events)

Players must **meet funding requirements** or choose consequences:

**Penalty Options:**
- 📉 Downgrade a build (Team → Pod)
- 🔒 Freeze an upgrade slot
- 👤 Layoffs (lose Talent pieces)
- 💰 Money penalty
- 👥 User loss

**Strategic Tension:**
- Failing to hit funding = setback
- But rushing funding = wasted resources
- Optimal timing = game mastery

---

## Funding Benefits (Proposed)

| Stage | Benefit Example |
|-------|-----------------|
| **Seed** | Starting capacity, minimal protection |
| **Series A** | +1 build action per turn |
| **Series B** | Protected assets (can't lose certain builds) |
| **Series C** | Resource throughput +50% |
| **IPO** | Endgame scoring multiplier |

**Note:** Exact benefits TBD during turn structure design.

---

## Strategic Intent

### Macro Pacing Goals

Funding creates **three game phases:**

1. **Early (Seed → Series A):** Capability building, divergence
2. **Mid (Series A → Series C):** Convergence, competitive friction
3. **Late (Series C → IPO):** Platform dominance, final push

### Runway Realism

Players should feel:
- ⏰ **Time pressure** — "I need to hit milestones or suffer"
- 📈 **Growth trajectory** — "I'm scaling up structurally"
- ⚖️ **Risk/reward** — "Do I push for next stage or build engine?"

---

## Visual Representation (Proposed)

### Funding Track Board

```
[Seed] → [A] → [B] → [C] → [IPO]
  ↑       ↑     ↑     ↑      ↑
Month 3  Mo 6  Mo 9  Mo 12  Mo 18
```

**Time markers** show when funding pressure hits.  
**Player tokens** move along track as they advance.

---

## Alternatives Considered

### Rejected: Shared Global Funding
**Why not:** Loses individualized pressure, everyone advances together

### Rejected: No Funding System
**Why not:** No macro pacing, game drags without structural pressure

### Rejected: Funding as Victory Condition
**Why not:** Reduces strategic variety, creates single optimal path

---

## Open Questions

- [ ] **Advancement trigger** — Time-based, achievement-based, or player choice?
- [ ] **Exact benefits** per funding stage?
- [ ] **Penalty severity** — How punishing should funding failure be?
- [ ] **Time intervals** — How many turns between stages?
- [ ] **Catch-up mechanics** — Can trailing players skip stages?
- [ ] **IPO endgame** — What happens after reaching IPO?

---

## Design Constraints

1. **Must create urgency** — Players should care about hitting deadlines
2. **Must be survivable** — Falling behind shouldn't be instant loss
3. **Must scale consistently** — All companies reach similar stages at similar times (engine timing parity)
4. **Must reward efficiency** — Hitting funding early should provide advantage

---

## Risks & Concerns

⚠️ **Runaway snowball** — Early funding advantages compound too hard  
⚠️ **Deterministic outcomes** — If one player hits Series C first, game may be over  
⚠️ **Punishment harshness** — Too severe penalties create feel-bad moments  
⚠️ **Complexity tracking** — Players must remember individual funding states

---

## Dependencies

**Requires:**
- Market Events (Time advancement trigger)
- Turn Structure (when funding checks happen)

**Required by:**
- Victory Conditions (IPO may affect scoring)
- Roadmap Trees (funding stages may gate node access)

---

## Related Documents

- [market-events.md](./market-events.md) — Time advancement triggers funding checks
- [organizational-capacity.md](./organizational-capacity.md) — Reorg helps survive funding pressure
- [victory-conditions.md](./victory-conditions.md) — Funding stage affects endgame scoring (TBD)
