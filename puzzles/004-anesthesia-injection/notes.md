# 📝 Notes: Finding the Injection for Anesthesia

---

## What Tripped Me Up

My first instinct was to divide 240 injections into 5 groups of 48 and give one group to each rat in round 1. If one rat faints, you know the group. But then you still have 48 suspects and only one round left — not enough to narrow it down to one injection.

The leap I was missing: **a rat isn't just a yes/no detector. It has 3 states — fainted in round 1, fainted in round 2, or never fainted.** Using that third state is everything.

---

## The Key Insight

> **48 hours = 2 rounds = 3 outcomes per rat, not 2.**

This is the puzzle's hidden depth. Most people think binary (fainted / didn't faint) and get stuck. The moment you see that *timing* of fainting is also information, the ternary (base-3) encoding becomes obvious.

- Binary thinking → 2⁵ = 32 injections max ❌
- Ternary thinking → 3⁵ = 243 injections max ✅

---

## Connection to Yesterday's Puzzle

This is Day 3's gold rod puzzle taken to the next level:

- Day 3: Represent 1–7 using base **2** (binary) with 3 pieces
- Day 4: Represent 1–243 using base **3** (ternary) with 5 rats

Both puzzles are fundamentally about **encoding information efficiently using number bases**.

---

## Pattern to Remember

**Number of distinguishable outcomes = (outcomes per unit)^(number of units)**

| Scenario | Base | Units | Max identifiable |
|----------|------|-------|-----------------|
| Binary (yes/no) | 2 | 5 rats | 2⁵ = 32 |
| Ternary (round 1/2/never) | 3 | 5 rats | 3⁵ = 243 |
| 4 rounds available | 4 | 5 rats | 4⁵ = 1024 |

This generalisation shows up in:
- Information theory (bits vs trits)
- Hash encoding
- Error detection problems
- "Poison wine" and similar interview puzzles

---

## Interview Tips

- Start with: *"Each rat has 3 possible outcomes — faint in round 1, faint in round 2, or never faint. So 5 rats give 3⁵ = 243 combinations, which covers all 240 injections."*
- Then explain the base-3 encoding clearly — draw the digit-position-to-rat mapping
- Walk through the example (injection 11201) step by step — interviewers love a concrete example
- Be ready for the follow-up: *"What if you had only 24 hours?"* → Each rat is binary (fainted or not) → 2⁵ = 32 injections max only

---

## Difficulty Felt: 6/10

This is a genuine step up from the previous puzzles. The ternary insight is non-obvious and requires connecting "time as information" with number base encoding. Worth spending extra time to really absorb before the interview.

---

## Date Solved: June 2026