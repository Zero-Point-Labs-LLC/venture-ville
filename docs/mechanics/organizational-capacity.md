# Organizational Capacity (Reorg Mechanic)

**Status:** ✅ Concept locked, ⚠️ Mechanics TBD  
**Last Updated:** 2026-03-22  
**Dependencies:** Talent System, Funding Timeline

---

## Problem Statement

Players need:
- **Scaling safety buffer** — Protection against funding pressure
- **Growth vs stability tension** — Meaningful strategic trade-off
- **Non-productive builds** — Defensive options beyond engines
- **Late-game relevance** — Mechanism that matters more over time

**Analog:** Cities & Knights city walls (defensive, non-productive)

---

## Solution: Reorg (Reorganization)

A **non-productive build** that increases organizational capacity.

### What Reorg Does

✅ **Increases headcount / team capacity**  
✅ **Acts as scaling safety buffer**  
❌ **Does NOT generate resources**  
❌ **Does NOT accelerate upgrades**

**Strategic role:**
- **Early game:** Optional (better to build engines)
- **Mid game:** Situational (depends on funding pressure)
- **Late game:** Critical (survival requirement)

---

## Failure Consequences

**If organizational capacity is insufficient:**
- 🔻 Inefficiency penalties
- 👤 Forced layoffs / attrition
- 🔒 Capacity penalties (can't build)
- 💸 Funding failure consequences worsen

**Example scenario:**
> You have 5 Teams but only 3 Reorg capacity.  
> Next funding check, you must downgrade 2 Teams or pay penalty.

---

## Strategic Intent

### Growth vs Stability Tension

**Build engines:**
- ✅ Immediate power increase
- ✅ Faster User/Money generation
- ❌ Increases organizational overhead

**Build Reorg:**
- ✅ Protects against funding failure
- ✅ Enables safe expansion
- ❌ No immediate return on investment

Players must balance **offense (growth) vs defense (stability)**.

---

## Mechanical Options (TBD)

### Option 1: Capacity Slots
- Each Reorg unlocks capacity for X Teams
- Exceed capacity → penalties at funding check
- Clean, but abstract

### Option 2: Efficiency Modifier
- Low Reorg → resource generation penalty
- High Reorg → efficiency bonus
- More complex, but more dynamic

### Option 3: Layoff Protection
- Reorg acts as "insurance" against funding penalties
- Spend Reorg to avoid downgrading builds
- One-time use, then rebuild

**Decision:** TBD based on funding mechanic design

---

## Costs & Limits

### Resource Cost (Placeholder)
- **Build Reorg:** 2-3 Hiring resources?
- **Upgrade Reorg:** Additional resources for higher tiers?

### Supply Limits
- **Per player:** 3-5 Reorg pieces?
- **Global pool:** Shared or individual supply?

**Decision:** TBD during balance testing

---

## Visual Representation

### Player Mat Option
```
[Teams: ○ ○ ○ ○ ○]
[Reorg:  □ □ □]
```

If Teams > Reorg slots → risk penalties

### Board Option
Reorg pieces placed on board like settlements/cities (thematic presence)

---

## Alternatives Considered

### Rejected: Automatic Scaling
**Why not:** Removes strategic decision, no tension

### Rejected: Pure Punishment System
**Why not:** No counterplay, feels arbitrary

### Rejected: Resource-Based Buffer
**Why not:** Too abstract, lacks physicality

---

## Open Questions

- [ ] **Exact mechanic** — Capacity slots, efficiency, or insurance?
- [ ] **Cost formula** — What does Reorg cost to build?
- [ ] **Timing** — When is Reorg checked (every funding? every turn?)
- [ ] **Limits** — How many Reorg can you build?
- [ ] **Upgrades** — Can Reorg be upgraded for more capacity?

---

## Design Constraints

1. **Must feel optional early** — Don't force builds in first few turns
2. **Must become critical late** — Ignore at your peril by endgame
3. **Must create visible risk** — Players should see danger coming
4. **Must reward foresight** — Building Reorg proactively should pay off

---

## Risks & Concerns

⚠️ **Boring builds** — "I guess I have to build Reorg again..."  
⚠️ **Runaway leaders** — If ahead, Reorg becomes easy; if behind, impossible  
⚠️ **Complexity creep** — Another system to track  
⚠️ **Unclear timing** — When is the "right" time to build Reorg?

---

## Dependencies

**Requires:**
- Talent System (scales with Team count)
- Funding Timeline (triggers capacity checks)
- Turn Structure (when Reorg is built)

**Required by:**
- Funding penalty severity (Reorg mitigates consequences)

---

## Related Documents

- [talent-system.md](./talent-system.md) — What Reorg protects
- [funding-timeline.md](./funding-timeline.md) — When Reorg matters most
- [turn-structure.md](./turn-structure.md) — When Reorg builds happen (TBD)
