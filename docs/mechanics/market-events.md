# Market Event System (7-Roll Replacement)

**Status:** ✅ Core mechanic locked, ⚠️ Event design TBD  
**Last Updated:** 2026-03-22  
**Dependencies:** Funding Timeline (Time advancement)

---

## Problem Statement

Catan's robber (7-roll) creates:
- ❌ Punishment without strategy
- ❌ Kingmaking (who to rob?)
- ❌ Negative player experience

**Venture Ville needs:**
- ✅ Time pressure without punishment
- ✅ Strategic opportunities and setbacks
- ✅ Macro pacing engine
- ✅ Thematic market volatility

---

## Solution: Market Events + Time Advancement

### Core Mechanic

**When a 7 is rolled:**
1. **Advance Time** (move funding timeline marker)
2. **Trigger Market Event** (draw from event deck)

This replaces robber punishment with:
- Macro pacing (funding pressure)
- Tactical volatility (events)
- Thematic resonance (market dynamics)

---

## Event Distribution (Proposed)

| Event Type | % of Deck | Purpose |
|------------|-----------|---------|
| **Month End** | 50% | Baseline time pressure, funding checks |
| **Tailwinds** | 25% | Opportunity spikes, growth boosts |
| **Headwinds** | 25% | Strategic setbacks, market corrections |

### Event Examples

**Month End (Baseline):**
- "All players check funding requirements"
- "Advance Time marker 1 space"
- "Draw Progress Card of choice"

**Tailwinds (Opportunities):**
- "Market surge: +2 Users for everyone"
- "Hiring boom: Build Talent at -1 resource"
- "VC interest: Next funding stage costs less"

**Headwinds (Setbacks):**
- "Market correction: Lose 1 Money"
- "Hiring freeze: No Talent builds this round"
- "Tech crash: Engineering cards cost +1 resource"

---

## Strategic Intent

### Goals

1. **Replace punishment with pressure** — Time advances, deadlines loom
2. **Create opportunity windows** — Tailwinds reward timing
3. **Add strategic adaptation** — Headwinds require flexibility
4. **Maintain tension** — 7-rolls still matter, but differently

### Player Psychology

Market Events should feel like:
- 📈 **Tailwinds:** "Yes! Perfect timing!"
- 📉 **Headwinds:** "Ugh, I need to pivot"
- ⏰ **Month End:** "Can I make this deadline?"

---

## Time Advancement Model

### How Time Progresses

**Option 1: Fixed Intervals**
- Every 7-roll advances Time 1 space
- Predictable, but may feel mechanical

**Option 2: Event-Based**
- Some events advance Time, others don't
- Variable pacing, more dynamic

**Option 3: Accumulating**
- 7-rolls accumulate "pressure"
- Time advances when threshold hit

**Decision:** TBD during turn structure design

---

## Event Targeting

### Scope Options

**Global Effects:**
- Affect all players equally
- Simple, but less interactive

**Selective Effects:**
- Apply to specific players (leader, trailing, random)
- More strategic, but risks kingmaking

**Player Choice:**
- Active player chooses who is affected
- Maximizes agency, but slows game

**Proposed:** Mix of global (Month End) + selective (Tailwinds/Headwinds)

---

## Alternatives Considered

### Rejected: Keep the Robber
**Why not:** Thematically wrong, negative experience, kingmaking

### Rejected: No 7-Roll Replacement
**Why not:** Loses dramatic tension, 7-rolls become dead rolls

### Rejected: Pure Time Track (No Events)
**Why not:** Too mechanical, loses tactical surprise

---

## Open Questions

- [ ] **Event deck size** — 30 cards? 50 cards?
- [ ] **Event targeting rules** — Who is affected by Tailwinds/Headwinds?
- [ ] **Time advancement rate** — How fast does the timeline move?
- [ ] **Discard/reshuffle** — Do events cycle or stay gone?
- [ ] **Player interaction** — Can players trigger events outside 7-rolls?

---

## Design Constraints

1. **Must be faster than robber** — Resolve in <30 seconds
2. **Must feel thematic** — Events should match startup reality
3. **Must balance positive/negative** — Not all punishment, not all rewards
4. **Must advance Time consistently** — Pacing needs predictability

---

## Risks & Concerns

⚠️ **Event overload** — Too many different effects confuse players  
⚠️ **Swingy randomness** — Tailwinds may create lucky winners  
⚠️ **Kingmaking** — Selective events may unfairly decide games  
⚠️ **Runaway pacing** — If 7-rolls cluster, Time may advance too fast

---

## Dependencies

**Requires:**
- Funding Timeline (Time advancement triggers funding checks)
- Turn Structure (when events resolve)

**Required by:**
- Funding Timeline (relies on Time advancing)

---

## Related Documents

- [funding-timeline.md](./funding-timeline.md) — Time advancement drives funding pressure
- [progress-cards.md](./progress-cards.md) — Some events may grant Progress Cards
- [turn-structure.md](./turn-structure.md) — When Market Events trigger (TBD)
- `../../design/cards/market-events/` — Individual event designs (TBD)
