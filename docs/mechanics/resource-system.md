# Resource System

**Status:** ✅ Locked  
**Last Updated:** 2026-03-22  
**Dependencies:** None (foundational)

---

## Problem Statement

Players need a production economy that:
- Represents startup capabilities
- Enables strategic specialization
- Creates meaningful trade-offs
- Supports asymmetric strategies

---

## Solution: 5-Resource Economy

Resources represent **what a startup produces or accumulates**.

### Resource Types

| Resource | Symbol | Represents | Primary Use |
|----------|--------|------------|-------------|
| **Engineering** | ⚙️ | Infrastructure / Technical Leverage | Build technical capabilities |
| **Design** | ✏️ | Usability / Differentiation / Creation | Improve user experience |
| **Product** | 🧭 | Convergence / Monetization Logic | Ship and scale products |
| **Marketing** | 📣 | Growth / Distribution | Acquire users |
| **Hiring** | 👥 | Organizational Expansion | Build team capacity |

### Spending Resources

Resources are spent to:
- **Unlock roadmap nodes** (product development)
- **Build Talent pieces** (organizational growth)
- **Trigger scaling actions** (special abilities)

---

## Strategic Intent

### Resource Philosophy

- **Engineering** — Rarely generates Users directly (technical leverage ≠ user growth)
- **Design + Marketing** — Primary drivers of early-game user acquisition
- **Product** — Convergence point (ties everything together)
- **Hiring** — Enables execution liquidity
- **No single dominant path** — Multiple viable resource strategies

### Asymmetry Goals

Companies should:
- Start with different resource generation patterns
- Excel in different resource combinations
- Converge toward balanced late-game economies

---

## Design Constraints

1. **No direct resource-to-victory conversion** — Resources enable engine building, not instant wins
2. **Must support trading** (if trading mechanic exists)
3. **Production must be spatially distributed** (board placement matters)
4. **Scarcity should be player-driven, not systemic** — You can get any resource, but not all at once

---

## Alternatives Considered

### Rejected: 3-Resource System
**Why not:** Too simple, limits strategic depth and company differentiation

### Rejected: 7+ Resource System
**Why not:** Too complex for teach time, dilutes strategic clarity

### Rejected: Tech Tree Resources
**Why not:** Creates gating problems, reduces early flexibility

---

## Open Questions

- [ ] **Production topology:** How are resources generated each turn?
- [ ] **Starting resources:** Do players begin with any resources?
- [ ] **Resource caps:** Is there a hand limit?
- [ ] **Trading:** Can players trade resources?

---

## Dependencies

**Required by:**
- Roadmap Trees (nodes cost resources)
- Talent System (builds cost resources)
- Turn Structure (production timing)

**Requires:**
- Board design (spatial distribution)

---

## Related Documents

- [talent-system.md](./talent-system.md) — How resources become organizational capacity
- [roadmap-trees.md](./roadmap-trees.md) — How resources unlock products
- [victory-conditions.md](./victory-conditions.md) — Resources don't directly score, but enable scoring engines
