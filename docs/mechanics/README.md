# Mechanics Documentation

Modular design documents for Venture Ville systems.

---

## 📚 How to Use These Docs

Each mechanic is **standalone** with:
- Problem statement
- Solution design
- Strategic intent
- Open questions
- Dependencies
- Alternatives considered
- Risks & concerns

**Status indicators:**
- ✅ **Locked** — Design finalized, ready for implementation
- ⚠️ **Needs Development** — Requires design work
- 🧪 **Experimental** — Testing needed before locking

---

## ✅ Locked Systems (Ready for Implementation)

### [Resource System](./resource-system.md)
5-resource economy (Engineering, Design, Product, Marketing, Hiring)

### [Talent System](./talent-system.md)
Partner → Pod → Team progression + variant pieces

### [Roadmap Trees](./roadmap-trees.md)
Company-specific upgrade paths with shared archetypes

### [Progress Cards](./progress-cards.md)
5 discipline decks (tactical, swingy, one-shot effects)

### [Advancement Tracks](./advancement-tracks.md)
Product & Engineering hierarchies (Design TBD)

### [Funding Timeline](./funding-timeline.md)
Seed → Series A → Series B → Series C → IPO progression

### [Market Events](./market-events.md)
7-roll replacement with Time advancement

### [Organizational Capacity](./organizational-capacity.md)
Reorg mechanic (growth vs stability tension)

---

## ⚠️ Systems Needing Development

### [Turn Structure](./turn-structure.md) ⭐ **TOP PRIORITY**
**Critical blocker:** Defines full turn loop, resource production, build timing

**Why it matters:**
- Unlocks balance testing
- Enables playtesting
- Integrates all other systems
- Validates game pacing

**Start here for next session.**

---

### [Victory Conditions](./victory-conditions.md)
**Status:** Philosophy locked (Users + Money), mechanics TBD

**Open questions:**
- Threshold vs points vs hybrid?
- Exact victory thresholds?
- Endgame trigger?
- Scoring formula?

---

### [Upgrade Archetypes](./upgrade-archetypes.md)
**Status:** Philosophy locked (shared archetypes), pool TBD

**Open questions:**
- How many archetypes total? (15-20 target)
- What does each archetype do?
- Power curve tuning?
- Node cost formulas?

---

## 🔗 System Dependencies

```
Resource System → Talent System → Roadmap Trees → Victory Conditions
                      ↓                ↓
              Organizational     Upgrade Archetypes
                  Capacity             

Turn Structure ← ALL SYSTEMS

Advancement Tracks → Progress Cards
                           ↓
                    Market Events → Funding Timeline
```

**Critical path:**
1. **Turn Structure** (unlocks everything)
2. **Upgrade Archetypes** (enables tree design)
3. **Victory Conditions** (sets balance targets)

---

## 📋 Reading Order

### For First-Time Review
1. Resource System (foundation)
2. Talent System (physical presence)
3. Roadmap Trees (progression)
4. Victory Conditions (goals)
5. Turn Structure (integration)

### For Development Work
1. **Turn Structure** (do this first)
2. Upgrade Archetypes (enables company design)
3. Victory Conditions (sets targets)

### For Playtesting
1. Turn Structure (rules)
2. Resource System (economy)
3. Talent System (builds)
4. Progress Cards (tactics)

---

## 🎯 Next Milestone

**Design the full turn loop + engine timing + funding cadence together**

This will unlock:
- Real balance testing
- Strategic clarity
- Emotional payoff
- System cohesion

**Start with:** [turn-structure.md](./turn-structure.md)

---

## 📝 Document Template

When creating new mechanics docs, use this structure:

```markdown
# [Mechanic Name]

**Status:** [Locked / Needs Development / Experimental]
**Last Updated:** YYYY-MM-DD
**Dependencies:** [List]

---

## Problem Statement
[What need does this solve?]

## Solution: [Name]
[Your design]

## Strategic Intent
[Why this design? What experience?)

## Open Questions
- [ ] Question 1
- [ ] Question 2

## Alternatives Considered
### Rejected: [Option]
**Why not:** [Reasoning]

## Risks & Concerns
⚠️ [Warning]

## Dependencies
**Requires:** [Systems]
**Required by:** [Systems]

## Related Documents
[Links]
```

---

**Last Updated:** 2026-03-22  
**Total Mechanics:** 11 documents
