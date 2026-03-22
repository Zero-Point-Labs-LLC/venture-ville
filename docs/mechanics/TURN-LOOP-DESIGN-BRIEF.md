# Turn Loop Design Brief

**Priority:** CRITICAL  
**Audience:** Architect Agent (Baltar)  
**Date:** 2026-03-22

---

## Design Requirements (Non-Negotiable)

The turn loop must achieve ALL of these simultaneously:

### 1. ✅ Complex Enough for Variety

**Requirements:**
- Turns shouldn't feel repetitive
- Players need meaningful decisions each turn
- Multiple viable strategies should emerge
- High replay value through varied gameplay

**Success Metrics:**
- 5+ distinct viable opening strategies
- Players don't repeat exact same turn pattern more than 2-3 times in a row
- Postgame analysis reveals different strategic paths to victory

---

### 2. ✅ Not Boring or Samey

**Requirements:**
- Avoid "roll dice, collect stuff, build, pass" monotony
- Each turn should create interesting moments
- Players should feel agency and tension
- Asymmetry should create different experiences per company

**Anti-Patterns to Avoid:**
- Scripted optimal turn sequences
- Waiting for your turn with nothing to do
- Turns that feel mechanically identical
- Predictable "build order" meta

**Success Metrics:**
- Non-active players stay engaged (average distraction time <30 seconds)
- Players report "tough decisions" at least 2-3 times per game
- Different companies create qualitatively different turn experiences

---

### 3. ✅ Balanced

**Requirements:**
- No single dominant strategy
- All companies/paths viable
- Comeback mechanics exist (trailing players have hope)
- Skill matters more than luck

**Balance Targets:**
- Win rate variance across companies: <10% difference
- Comeback potential: 2nd/3rd place should win 30%+ of games
- Luck vs skill ratio: ~30% luck / 70% skill
- First player advantage: <5% win rate boost

**Mechanisms to Consider:**
- Catch-up mechanics for trailing players
- Anti-runaway-leader systems
- Multiple scoring vectors (can't optimize just one thing)

---

### 4. ✅ On Theme (Startup Narrative)

**Requirements:**
- Should FEEL like running a startup (not abstract resource management)
- Mechanics reinforce narrative (funding pressure, market volatility, pivots)
- Thematic coherence - actions make sense in startup context
- Players naturally use startup vocabulary during play

**Thematic Touchstones:**
- "We need to ship this quarter" (urgency)
- "Should I raise funding or bootstrap?" (strategic tension)
- "The market just shifted" (volatility)
- "I need to pivot my strategy" (adaptation)
- "We're scaling too fast" (growth vs stability)

**Anti-Patterns:**
- Generic Euro-game resource conversion
- Mechanics that make no thematic sense
- Jargon that doesn't map to startup reality

---

### 5. ✅ Unique (Signature Mechanic)

**Requirements:**
- Not just "Catan with a startup skin"
- Signature mechanic that defines the game
- Something players haven't seen before (or rare combination)
- Memorable and distinctive ("the game where you...")

**Potential Signature Mechanics to Explore:**
- Funding timeline pressure + individualized consequences
- Market event dual-track (Time + Event)
- Asymmetric company engines with shared archetypes
- Progress card discipline system
- Reorg capacity tension (growth vs stability)

**Success Metric:**
- Players describe the game without comparing it to another game
- "This is the game where you manage runway pressure while racing platforms"

---

## Design Challenge: The Golden Triangle

```
    COMPLEX/VARIED
         /\
        /  \
       /    \
      /  ✨  \
     /  SWEET \
    /   SPOT   \
   /            \
  /______________\
SIMPLE/     UNIQUE/
ACCESSIBLE  THEMATIC
```

**The 3 proposals should each navigate this differently:**

### Option A: Conservative (Accessibility First)
- Maximize learnability and flow
- Keep just enough depth to avoid boredom
- Proven mechanics with light twists
- **Risk:** May feel derivative

### Option B: Innovative (Uniqueness First)
- Push thematic resonance and signature hook
- Accept higher complexity if it serves theme/uniqueness
- Bold new mechanic even if learning curve is steeper
- **Risk:** May alienate casual players

### Option C: Hybrid (Balance All Five)
- Find the golden balance point
- Clever integration that achieves all goals
- Most design effort, highest potential payoff
- **Risk:** May compromise too much, satisfy nobody

---

## Evaluation Criteria for Proposals

For EACH proposal, explicitly address:

### ✅ Variety Check
- What creates variety between games?
- What creates variety between turns?
- How many decision points per turn?
- What prevents optimal scripting?

### ✅ Engagement Check
- What do non-active players do?
- What prevents monotony?
- Where is the tension/excitement?
- What's memorable about turns?

### ✅ Balance Check
- What prevents runaway leaders?
- How do trailing players catch up?
- What creates skill expression?
- How is luck mitigated?

### ✅ Theme Check
- What makes it feel like a startup?
- What narrative emerges during play?
- Do mechanics reinforce theme?
- Would this work with different theme? (If yes, may be too generic)

### ✅ Uniqueness Check
- What's the signature hook?
- How is this different from Catan/Wingspan/Splendor?
- What will players remember?
- What creates "only in Venture Ville" moments?

---

## Research Guidance

When analyzing other games, ask:

1. **What problem does this turn structure solve?**
2. **What does it do BETTER than alternatives?**
3. **What are its weaknesses?**
4. **Could we adapt this while staying thematic?**
5. **What's the unique hook we can steal/remix?**

---

## Success Definition

**A successful turn loop proposal:**

- ✅ Can be explained in 2 minutes
- ✅ Creates tough decisions every turn
- ✅ Keeps all players engaged
- ✅ Supports 20-30 turns without feeling long
- ✅ Rewards skill and planning
- ✅ Feels unmistakably like a startup race
- ✅ Has a "signature moment" that defines the game

**The ultimate test:**
> If a player describes Venture Ville to a friend, would they say:
> "It's kind of like Catan..." ❌
> OR
> "It's the startup game where you race to IPO while managing runway pressure..." ✅

---

## Final Note

**This is THE critical design decision.**

The turn loop is the heartbeat of the game. Get it right, and everything else falls into place. Get it wrong, and no amount of polish will save it.

Take the time. Do the research. Think deeply.

We're building something special here.

---

**Next Steps After Proposals:**
1. Review all 3 proposals
2. Paper prototype the most promising one
3. Playtest with simple components
4. Iterate based on what breaks
5. Lock it down and build the rest of the game around it
