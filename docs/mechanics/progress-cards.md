# Progress Card System

**Status:** ✅ Core philosophy locked, ⚠️ Card design TBD  
**Last Updated:** 2026-03-22  
**Dependencies:** Advancement Tracks (loosely)

---

## Problem Statement

The game needs:
- **Tactical variability** — Surprise moments, non-deterministic swings
- **Interactive disruption** — Ways to interfere with opponents
- **Disciplinary identity** — Thematic coherence across resource types
- **Low bookkeeping** — Instant-impact effects, not complex tracking

---

## Solution: Cities & Knights–Inspired Tactical Decks

5 discipline-specific decks that provide **swingy, reactive, one-shot effects**.

### Card Earning Mechanic

**Players roll discipline dice each turn.**  
- Matching die → draw Progress Card from that discipline's deck
- Advancement tracks act as **global thresholds** (not card gates)
- No hoarding restrictions (draw → use when ready)

### Card Philosophy

**Play → Impact → Move On**

- Short text (1-2 sentences)
- Immediate effect (no ongoing tracking)
- Swingy impact (game-changing moments)
- Reactive timing (use during opponent's turn if allowed)

---

## Deck Identities

### 🔴 Engineering Deck
**Theme:** Sabotage / Denial / Reversals

**Example Effects:**
- "Cancel opponent's build this turn"
- "Reverse a recent upgrade"
- "Block resource production on a hex"

**Strategic Role:** Defense, disruption, technical superiority

---

### 🟢 Design Deck
**Theme:** Information / Swaps / Perception Pressure

**Example Effects:**
- "Peek at opponent's hand"
- "Swap two resources with another player"
- "Force opponent to discard"

**Strategic Role:** Mind games, information advantage, flexibility

---

### 🔵 Product Deck
**Theme:** Tempo / Extra Actions / Coordination

**Example Effects:**
- "Take an extra build action this turn"
- "Unlock two nodes simultaneously"
- "Skip funding penalty once"

**Strategic Role:** Acceleration, efficiency, compounding

---

### 🟣 Marketing Deck
**Theme:** Hype Spikes / Market Theft / Viral Growth

**Example Effects:**
- "Steal Users from another player"
- "Double User gain from next node"
- "Force opponent to lose Users"

**Strategic Role:** User acquisition, momentum swings

---

### 🟠 Recruiting Deck
**Theme:** Human Capital Volatility / Talent Poaching

**Example Effects:**
- "Poach a Manager from opponent"
- "Instant Contractor without cost"
- "Cause opponent layoffs"

**Strategic Role:** Team disruption, hiring spikes, organizational chaos

---

## Strategic Intent

### Deck Balance Goals

- **No dominant deck** — Each should be situationally powerful
- **Counterplay exists** — Cards should have strategic counters
- **Timing matters** — Holding cards for optimal moment is key
- **Not victory-deciding alone** — Cards accelerate engines, don't replace them

### Psychological Impact

Cards should create:
- 😮 **Surprise** — "I didn't see that coming"
- 🤔 **Adaptation** — "I need to adjust my strategy"
- 😤 **Tension** — "They might have a counter"
- 🎉 **Celebration** — "Perfect timing!"

---

## Alternatives Considered

### Rejected: Single Shared Deck
**Why not:** Loses thematic discipline identity, bland effects

### Rejected: Deck Leveling System
**Why not:** Adds complexity, creates runaway leader problems

### Rejected: Permanent Card Effects
**Why not:** Increases bookkeeping, slows game, creates balance nightmares

---

## Open Questions

- [ ] **Deck size** per discipline? (15-20 cards each?)
- [ ] **Hand limit** or unlimited hold?
- [ ] **Reactive timing** — Can cards interrupt opponent turns?
- [ ] **Discard rules** — When do used cards refresh?
- [ ] **Starting cards** — Do players begin with any?
- [ ] **Advancement bonuses** — Do higher track levels unlock better draws?

---

## Design Constraints

1. **Must be readable in 3 seconds** — Simple text, clear effects
2. **No multi-turn tracking** — Instant resolution only
3. **Thematically coherent** — Effects match discipline identity
4. **Balanced across decks** — No "best deck" syndrome

---

## Risks & Concerns

⚠️ **Swingy randomness** — Too much RNG may frustrate strategic players  
⚠️ **Balance complexity** — 5 decks × 15-20 cards = difficult testing  
⚠️ **Kingmaking** — Late-game cards may unfairly decide winner  
⚠️ **Teach burden** — Players need to understand all 5 deck themes

---

## Dependencies

**Requires:**
- Advancement Tracks (optional thresholds)
- Turn Structure (when cards are drawn)

**Required by:**
- Turn Structure (card timing in action sequence)

---

## Related Documents

- [advancement-tracks.md](./advancement-tracks.md) — Global progression that may affect card quality
- [turn-structure.md](./turn-structure.md) — When cards are drawn and played (TBD)
- `../../design/cards/` — Individual card designs (TBD)
