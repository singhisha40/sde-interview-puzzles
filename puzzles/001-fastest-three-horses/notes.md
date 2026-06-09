# 📝 Notes: Find the 3 Fastest Horses

---

## What Tripped Me Up

At first instinct I thought the answer was 5 races — just race everyone and the top 3 come out naturally.  
But you can't race all 25 together. Max 5 per race. That changes everything.

Then I thought 6 — but after race 6 you still have 5 candidates for 2 positions. You can't guess. You need one more race.

---

## The Key Insight

> **Elimination is the real game — not just finding the winner.**

The trick is that after race 6, you can eliminate a huge number of horses *without racing them again*:

- If a horse lost to someone who can't be in the top 3 → it's eliminated
- If a horse was already beaten by 3 or more horses → it's eliminated
- D1 and E1 (4th and 5th in race 6) each have at least 3 horses faster than them → gone
- Everyone from groups D and E is gone
- A4, A5, B3, B4, B5, C2, C3, C4, C5 → all eliminated by logic alone

You go from 24 unknowns down to **exactly 5 candidates** using pure reasoning.

---

## Pattern to Remember

This puzzle teaches a pattern that shows up a lot in SDE interviews:

**"What can I eliminate without testing?"**

Same thinking applies in:
- Binary search (eliminate half the array each time)
- Tournament brackets
- Divide and conquer problems

---

## Interview Tips

- Always state your answer first: *"The minimum is 7 races."*
- Then walk through the reasoning step by step
- The interviewer will likely ask: *"Why not 6?"* — be ready with the 5-candidates-for-2-spots argument
- Bonus points if you generalise: *"For N horses, k per race, finding top m..."*

---

## Difficulty Felt: 3/10

Once you see the elimination trick it feels obvious. The hard part is not jumping to 5 or 6 races too quickly.

---

## Date Solved: June 2026