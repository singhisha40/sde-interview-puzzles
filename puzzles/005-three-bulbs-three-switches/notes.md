# 📝 Notes: 3 Bulbs and 3 Switches

---

## What Tripped Me Up

I kept thinking about this as a binary problem — on or off. With 3 switches and only 1 entry, I thought it was impossible to identify all three since two bulbs would always look the same (both off).

The puzzle feels impossible until you realize you're not limited to observing just *light*. You can also observe *heat*. That's the unlock.

---

## The Key Insight

> **You have more information available than the problem explicitly tells you to use.**

Light gives you 2 states: on / off.  
Heat gives you an extra state: warm / cold.

Combined: on, off-warm, off-cold → **3 states for 3 switches** → solved in one visit ✅

This is a great reminder in interviews: always ask yourself — *"Am I using all the information available to me?"*

---

## Connection to Previous Puzzles

| Day | Puzzle | States used |
|-----|--------|-------------|
| Day 4 | Anesthesia Injection | 3 states per rat (round 1 / round 2 / never) |
| Day 5 | 3 Bulbs & Switches | 3 states per bulb (on / warm / cold) |

Both puzzles are about **squeezing 3 states out of what looks like a 2-state system**. Same underlying pattern, different physical setup.

---

## Pattern to Remember

**"Impossible with 2 states → possible with 3 states"**

When a puzzle seems to give you one fewer observation than needed, look for a **hidden third state** in the physical world:

- Bulbs: light + heat
- People: statement + timing of statement
- Coins: weight + which side lands up

This kind of lateral thinking is what separates a good interview answer from a great one.

---

## Interview Tips

- State the problem clearly first: *"With just on/off, two bulbs will always look the same. I need a third distinguishable state."*
- Then introduce the heat trick naturally: *"A bulb that was recently on will still be warm — that's my third state."*
- Name the exact sequence: Switch 1 on for 10 min then off, Switch 2 on, Switch 3 always off
- Walk through all three identifications: glowing → Switch 2, warm → Switch 1, cold → Switch 3
- This puzzle is asked at MakeMyTrip and Qualcomm — keep the answer crisp and confident

---

## Difficulty Felt: 3/10

Very easy once the heat trick clicks. The puzzle has a satisfying "of course!" moment. The only reason people get stuck is they limit themselves to observing only what the problem explicitly mentions.

---

## Date Solved: June 2026