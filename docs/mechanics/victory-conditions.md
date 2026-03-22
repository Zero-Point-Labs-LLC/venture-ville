# Victory Conditions

**Status:** ⚠️ NEEDS DEVELOPMENT (High Priority)  
**Last Updated:** 2026-03-22  
**Dependencies:** Roadmap Trees, Funding Timeline

---

## Problem Statement

The game needs **clear win conditions** that:
- Reward both User acquisition and Money generation
- Create strategic variety (multiple paths to victory)
- Build toward satisfying climax (not sudden anti-climax)
- Maintain tension until the end

**Currently undefined:**
- Exact thresholds for winning
- Scoring mechanics
- Endgame trigger
- Tiebreakers

---

## Design Philosophy (Locked)

### Dual Victory Tracks

Players win through combination of:
- 👥 **Users** — Market positioning, influence, momentum
- 💰 **Money** — Scaling power, late-game dominance

**Strategic intent:**
- Early game → focus on Users (market share)
- Late game → Money becomes critical (platform power)
- Balanced strategies rewarded

---

## Victory Models to Consider

### Option 1: First to Threshold
**Mechanic:** First player to reach X Users AND Y Money wins

**Pros:**
- Clear goal
- Creates race tension
- Simple to track

**Cons:**
- May end abruptly
- Trailing players feel hopeless
- No comeback potential

---

### Option 2: Point-Based (Highest Score)
**Mechanic:** At game end, sum Users + Money + bonuses

**Pros:**
- Allows comebacks
- Multiple scoring vectors
- Rewards diverse strategies

**Cons:**
- Less dramatic climax
- Victory may feel arbitrary
- Harder to track who's winning

---

### Option 3: Milestone System
**Mechanic:** First to achieve 3 of 5 milestones wins

**Example milestones:**
- Reach 15 Users
- Reach $50M Money
- Complete a Platform node
- Reach Series C funding
- Control 3 Teams

**Pros:**
- Flexible victory paths
- Clear progress markers
- Strategic variety

**Cons:**
- Complex tracking
- May incentivize narrow strategies
- Harder to balance

---

### Option 4: Hybrid (Threshold + Endgame Scoring)
**Mechanic:** First to IPO triggers endgame, then highest score wins

**Pros:**
- Combines race and points
- Endgame climax
- Comeback potential

**Cons:**
- More complex
- Two victory systems to learn
- May confuse new players

---

## Proposed Victory Formula (Rough Draft)

**For discussion:**

```
Victory Score = (Users × 2) + Money + Funding Stage Bonus
```

**Funding Bonuses:**
- Seed: +0
- Series A: +10
- Series B: +20
- Series C: +30
- IPO: +50

**Win condition:** First to 100 points OR highest score when Time runs out

**This is highly tentative and needs testing.**

---

## Open Questions

### Critical

- [ ] **Victory type** — Threshold, points, milestones, or hybrid?
- [ ] **User threshold** — How many Users to win?
- [ ] **Money threshold** — How much Money to win?
- [ ] **Endgame trigger** — What ends the game?

### High Priority

- [ ] **Scoring formula** — How are Users/Money weighted?
- [ ] **Funding bonuses** — How much does funding stage affect score?
- [ ] **Platform bonuses** — Do late-game platform nodes score extra?
- [ ] **Tiebreakers** — How are ties resolved?

### Medium Priority

- [ ] **Visible leaders** — Should players know who's winning?
- [ ] **Hidden scoring** — Any secret victory points?
- [ ] **Sudden death** — Is instant victory possible?

---

## Design Constraints

1. **Must support 20-30 turn target** — Victory shouldn't come too early/late
2. **Must reward engine building** — Not just lucky rolls
3. **Must create tension** — Close games, not blowouts
4. **Must be calculable** — Players should estimate victory distance

---

## Alternatives Considered

### Rejected: Pure User Count
**Why not:** Ignores Money, creates single strategy

### Rejected: Pure Money Accumulation
**Why not:** Ignores Users, loses startup theme

### Rejected: Complex Multi-Variable Formula
**Why not:** Too opaque, players can't track progress

---

## Pacing Implications

### From Master Design

**Game arc:**
- **Early:** Capability divergence (Users > Money)
- **Mid:** Convergence + friction (Users ≈ Money)
- **Late:** Platform dominance (Money > Users?)

**Victory conditions must support this arc.**

---

## Testing Checklist

- [ ] Playtest with threshold-based victory
- [ ] Playtest with point-based victory
- [ ] Compare game lengths (turns per game)
- [ ] Measure comeback potential
- [ ] Check for runaway leader problems
- [ ] Verify strategic variety (multiple paths viable)

---

## Dependencies

**Requires:**
- Roadmap Trees (source of Users/Money)
- Funding Timeline (affects scoring/endgame)
- Turn Structure (victory check timing)

**Required by:**
- Strategic balance (node output tuning)
- Endgame pacing

---

## Next Steps

1. **Choose victory model** — Threshold, points, or hybrid?
2. **Set target numbers** — Establish victory thresholds
3. **Create scoring sheet** — Design player mat or tracker
4. **Playtest** — Validate numbers and pacing

---

## Related Documents

- [roadmap-trees.md](./roadmap-trees.md) — Source of Users/Money
- [funding-timeline.md](./funding-timeline.md) — May affect endgame scoring
- [turn-structure.md](./turn-structure.md) — When victory is checked (TBD)
- [MASTER-DESIGN.md](../../MASTER-DESIGN.md) — Core victory philosophy
