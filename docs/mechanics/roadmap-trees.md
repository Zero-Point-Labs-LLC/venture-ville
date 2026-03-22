# Roadmap Tree System

**Status:** ✅ Philosophy locked, ⚠️ Implementation details TBD  
**Last Updated:** 2026-03-22  
**Dependencies:** Resource System, Talent System

---

## Problem Statement

Companies need:
- **Strategic differentiation** — Unique playstyles and paths
- **Meaningful progression** — Build toward clear goals
- **Flexible choices** — Multiple viable starting strategies
- **Convergence tension** — Competition for shared endgame goals

---

## Solution: Company-Specific Roadmap Trees

Each company has a **unique upgrade tree** representing product development and strategic milestones.

### Node Structure

**Each node requires:**
- Combinations of Resources (⚙️ ✏️ 🧭 📣 👥)
- May require Talent pieces (Pods/Teams)

**Each node generates:**
- 👥 **Users** (victory points)
- 💰 **Money** (scaling power)
- 🎴 **Progress Cards** (tactical options)

### Tree Architecture

```
[Multiple Starting Nodes]
         ↓
   [Parallel Branches]
         ↓
   [Convergence Layer]
         ↓
  [Platform / Ecosystem]
```

**Design Goals:**
1. **Early divergence** — Multiple viable opening moves
2. **Parallel development** — Work on multiple branches simultaneously
3. **Late convergence** — Compete for flagship products and platforms
4. **Platform dominance** — Endgame rewards ecosystem control

---

## Strategic Intent

### Node Types (Conceptual)

| Node Type | Purpose | Output Focus |
|-----------|---------|--------------|
| **Prototype** | Early capability | Economy shapers (conversions, discounts) |
| **MVP** | Initial product | Small User/Money gain |
| **App** | Full product | Economic engines (recurring, multipliers) |
| **Flagship** | Market leader | Large User spike, platform foundation |
| **Platform** | Ecosystem | Network effects, dominance |

### Economic Slope Requirement

⚠️ **Critical Design Constraint:**  
**Shipping must increase a player's economic slope.**

- Prototypes → improve resource conversion efficiency
- Apps → create recurring income or output multipliers
- Platforms → compound network effects

Early nodes that don't improve economy create dead builds.

---

## Shared Archetypes vs Unique Trees

### Design Philosophy

**Companies differ via:**
- Node **ordering** (what unlocks when)
- Branch **triggers** (what enables what)
- Theme **branching** (strategic emphasis)
- Victory **path** (User-heavy vs Money-heavy)

**Companies do NOT differ via:**
- Unique rule systems per node
- Company-specific resource types
- Completely custom mechanics

### Why Shared Archetypes?

✅ **Teach time** — Learn once, recognize everywhere  
✅ **Balance** — Easier to test and tune  
✅ **Strategic clarity** — Focus on path selection, not rule interpretation

---

## Node Count Targets

**Per company tree (estimated):**
- Starting nodes: 3-5
- Mid-tier nodes: 5-7
- Convergence nodes: 3-4
- Platform nodes: 1-2

**Total: 12-18 nodes per company**

Allows ~6-10 builds per game (depending on pacing).

---

## Alternatives Considered

### Rejected: Fully Unique Mechanics per Company
**Why not:** Balance explosion, teaching complexity, fragmented identity

### Rejected: Shared Linear Track for All Companies
**Why not:** No asymmetry, boring strategic sameness

### Rejected: Random Node Draws (Deck Building)
**Why not:** Loses thematic company identity, reduces planning

---

## Open Questions

- [ ] **Exact node counts** per company?
- [ ] **Upgrade archetype pool size** — How many shared building blocks?
- [ ] **Node visibility** — Are all nodes visible from start, or revealed?
- [ ] **Branching constraints** — Can you work multiple branches simultaneously?
- [ ] **Platform mechanics** — What makes endgame platforms special?

---

## Risks & Concerns

⚠️ **Balance testing burden** — Each company tree multiplies testing complexity  
⚠️ **Dead-end paths** — Poorly designed branches waste player time  
⚠️ **Engine timing parity** — All companies must reach strong engines at similar turns

---

## Dependencies

**Requires:**
- Resource System (node costs)
- Talent System (some nodes may require Pods/Teams)
- Upgrade Archetypes (shared building blocks)

**Required by:**
- Victory Conditions (Users/Money generation)
- Turn Structure (node unlock timing)

---

## Related Documents

- [upgrade-archetypes.md](./upgrade-archetypes.md) — Shared node types (TBD)
- [resource-system.md](./resource-system.md) — What nodes cost
- [victory-conditions.md](./victory-conditions.md) — What nodes generate
- `../companies/` — Individual company tree designs (TBD)
