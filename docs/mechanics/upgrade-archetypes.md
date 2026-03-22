# Upgrade Archetypes (Shared Building Blocks)

**Status:** ⚠️ NEEDS DEVELOPMENT (High Priority)  
**Last Updated:** 2026-03-22  
**Dependencies:** Resource System, Roadmap Trees, Turn Structure

---

## Problem Statement

**Design challenge:**
- Companies need **unique roadmap trees** for asymmetry
- But **fully custom nodes** create balance explosion + teach burden

**Solution:**
Create **shared upgrade archetypes** that companies remix into unique trees.

**Think:**
- Same card effects, different deck order (not unique card text per deck)
- Same building types, different tech tree arrangement (not custom buildings per faction)

---

## Design Philosophy (Locked)

### Companies Differ Via:
✅ **Ordering** — What unlocks when  
✅ **Triggers** — What enables what  
✅ **Branching** — Strategic emphasis  
✅ **Theme** — Narrative flavor  

### Companies Do NOT Differ Via:
❌ **Unique rule systems** per node  
❌ **Company-specific resource types**  
❌ **Completely custom mechanics**  

**Why:** Teach once, recognize everywhere. Balance testing stays manageable.

---

## Archetype Categories (Proposed)

### 1. Prototypes (Economy Shapers)

**Function:** Improve resource conversion efficiency

**Example Archetypes:**
- **Converter** — Trade 2 of X for 1 of Y
- **Discount** — Build next node at -1 resource
- **Probability Boost** — Reroll one die during production
- **Storage** — Hold +3 resource cards

---

### 2. Apps (Economic Engines)

**Function:** Generate recurring income or output multipliers

**Example Archetypes:**
- **Passive Generator** — +1 User per turn
- **Multiplier** — +50% Money from next node
- **Network Effect** — +1 User per adjacent Team
- **Subscription** — +$5M Money each Market Event

---

### 3. Flagships (Market Leaders)

**Function:** Large User spikes, platform foundation

**Example Archetypes:**
- **User Magnet** — +10 Users instantly
- **Platform Seed** — Unlocks Platform tier
- **Market Dominance** — Steal 3 Users from opponent
- **Viral Hit** — +1 User per Progress Card held

---

### 4. Platforms (Ecosystems)

**Function:** Endgame compound effects, network dominance

**Example Archetypes:**
- **Ecosystem Builder** — +2 Users per affiliated node
- **Monopoly Lock** — Opponents pay you for certain actions
- **Scale Advantage** — All outputs doubled
- **Winner-Take-All** — +50 Users if you have most Money

---

## Archetype Pool Size

**Target: 15-20 total archetypes**

**Breakdown (estimated):**
- Prototypes: 4-5
- Apps: 6-8
- Flagships: 3-4
- Platforms: 2-3

**Company tree size:** 12-18 nodes each  
**Archetypes used per company:** 8-12 unique  
**Remix factor:** High (same archetypes, different contexts)

---

## Example: Two Companies Using Same Archetype

### Company A: "Social Media Startup"
**Node:** "Viral Campaign" (Flagship - User Magnet archetype)
- **Cost:** 2 Marketing + 1 Design
- **Output:** +10 Users
- **Flavor:** "Your meme goes viral!"

### Company B: "SaaS Startup"
**Node:** "Enterprise Launch" (Flagship - User Magnet archetype)
- **Cost:** 2 Product + 1 Engineering
- **Output:** +10 Users
- **Flavor:** "Fortune 500 adoption!"

**Same mechanic, different theme and cost.**

---

## Open Questions

### Critical

- [ ] **Archetype count** — How many total archetypes?
- [ ] **Node effects** — What does each archetype do?
- [ ] **Power curve** — How strong should late-game archetypes be?
- [ ] **Remix rules** — Can companies use same archetype multiple times?

### High Priority

- [ ] **Prototype effects** — What economy shapers exist?
- [ ] **App effects** — What engines exist?
- [ ] **Flagship effects** — What big plays exist?
- [ ] **Platform effects** — What endgame powers exist?

### Medium Priority

- [ ] **Resource costs** — Standard costs per archetype tier?
- [ ] **Talent requirements** — Do some archetypes require Pods/Teams?
- [ ] **Upgrade paths** — Can archetypes upgrade into each other?

---

## Design Constraints

1. **Must be learnable** — See archetype once, recognize it everywhere
2. **Must support asymmetry** — Companies feel different despite shared pieces
3. **Must scale consistently** — All companies reach similar power at similar times
4. **Must be balanceable** — Tune archetype, tune all instances

---

## Economic Slope Requirement (Critical)

⚠️ **From Master Design:**  
**Shipping must increase a player's economic slope.**

Each archetype must improve:
- Resource generation rate
- Resource conversion efficiency
- Output multipliers
- Tempo advantages

**Dead builds = bad design.**

---

## Alternatives Considered

### Rejected: Fully Unique Nodes
**Why not:** Balance explosion, teaching burden, testing nightmare

### Rejected: Zero Unique Nodes
**Why not:** No asymmetry, boring sameness

### Rejected: Random Node Draws
**Why not:** Loses thematic company identity, reduces planning

---

## Testing Approach

1. **Create archetype pool** (15-20)
2. **Design 2-3 company trees** using archetypes
3. **Playtest for balance** (do all archetypes get used?)
4. **Refine power levels**
5. **Expand company roster** using validated archetypes

---

## Dependencies

**Requires:**
- Resource System (costs)
- Turn Structure (when nodes unlock)
- Victory Conditions (output targets)

**Required by:**
- Roadmap Trees (companies built from archetypes)
- Balance testing (all companies must be tested)

---

## Next Steps

1. **Brainstorm archetype effects** — Create initial pool
2. **Categorize by tier** — Prototype vs App vs Flagship vs Platform
3. **Assign power levels** — Set output targets
4. **Build test company** — Remix archetypes into one tree
5. **Playtest** — Validate archetype balance

---

## Related Documents

- [roadmap-trees.md](./roadmap-trees.md) — Trees built from archetypes
- [resource-system.md](./resource-system.md) — Archetype costs
- [victory-conditions.md](./victory-conditions.md) — Archetype output targets
- `../companies/` — Individual company trees (TBD)
