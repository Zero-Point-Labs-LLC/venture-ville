# Talent System (Execution Layer)

**Status:** ✅ Locked (core progression), ⚠️ Variants need testing  
**Last Updated:** 2026-03-22  
**Dependencies:** Resource System

---

## Problem Statement

Players need:
- Physical board presence (like Catan roads/settlements)
- Organizational growth mechanics
- Clear progression fantasy
- Multiple build types for strategic variety

---

## Solution: Talent Pieces

**Teaching Model:**  
> Resources are what your startup produces.  
> Talent is how your startup grows and executes.

### Core Progression (Locked)

| Piece | Analog | Function | Progression |
|-------|--------|----------|-------------|
| **Partner** | Road | Distribution leverage, network building | Foundation |
| **Pod** | Settlement | Cross-functional team, early capability | Tier 1 |
| **Team** | City | Scaled organizational unit, full capability | Tier 2 |

**Progression Path:** Partner → Pod → Team

### Variant Pieces (Experimental)

| Piece | Function | Strategic Use |
|-------|----------|---------------|
| **Manager** | Efficiency / scaling buffer | Reduce costs or increase output |
| **Contractor** | Temporary burst capacity | One-time power spike |
| **Influencer** | Brand amplification | Marketing multiplier |

---

## Strategic Intent

### Progression Fantasy

Players should feel like they're:
1. **Early:** Building connections (Partners)
2. **Mid:** Forming teams (Pods)
3. **Late:** Scaling organizations (Teams)

### Build Diversity Goals

- **Partners** — Cheap, flexible, enable expansion
- **Pods** — Medium investment, generate resources/users
- **Teams** — Expensive, powerful engines, platform foundation
- **Variants** — Tactical timing plays, situational optimization

---

## Design Constraints

1. **Clear upgrade path** — Partner → Pod → Team must be obvious
2. **Spatial significance** — Placement should matter (board positioning)
3. **Upgrade requirements** — Teams need Pods, Pods need Partners (like Catan)
4. **Limited supply** — Creates scarcity and competition

---

## Mechanical Details

### Resource Costs (Placeholder)

| Build | Cost | Notes |
|-------|------|-------|
| Partner | 1-2 resources | Cheap expansion |
| Pod | 3-4 resources | Mid investment |
| Team | 5-6 resources | Major commitment |
| Manager | Variable | Cost reduction ability |
| Contractor | Variable | One-time burst |
| Influencer | Variable | Marketing boost |

### Upgrade Mechanics

**Pod → Team Upgrade:**
- Requires adjacent Partner connections
- Costs additional resources
- Increases output (2x or custom multiplier)
- May unlock special abilities

---

## Alternatives Considered

### Rejected: Generic "Buildings"
**Why not:** Lacks thematic resonance, no progression fantasy

### Rejected: Pure Card-Based Teams
**Why not:** Loses spatial board interaction, less tactile

### Rejected: Flat Hierarchy (No Upgrades)
**Why not:** Removes satisfying growth arc, limits late-game strategy

---

## Open Questions

- [ ] **Exact resource costs** for each piece type?
- [ ] **Supply limits** per player or global pool?
- [ ] **Variant piece balance** — Are Manager/Contractor/Influencer worth the complexity?
- [ ] **Spatial rules** — What are Partner connection constraints?
- [ ] **Team abilities** — Do Teams unlock special powers?

---

## Risks & Concerns

⚠️ **Variant overload** — Too many piece types may confuse new players  
⚠️ **Balance complexity** — Different piece abilities multiply testing burden  
⚠️ **Supply limits** — Must prevent runaway leaders while allowing expansion

---

## Dependencies

**Requires:**
- Resource System (costs)
- Board Design (spatial placement)
- Turn Structure (build timing)

**Required by:**
- Roadmap Trees (Pods/Teams may affect node unlocks)
- Victory Conditions (Team count may score points)

---

## Related Documents

- [resource-system.md](./resource-system.md) — What you spend to build Talent
- [organizational-capacity.md](./organizational-capacity.md) — Reorg mechanic complements Talent system
- [roadmap-trees.md](./roadmap-trees.md) — Pods/Teams may interact with product nodes
