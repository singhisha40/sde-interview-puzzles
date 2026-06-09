# ✅ Solution: Find the 3 Fastest Horses

**Answer: 7 races**

---

## Step-by-Step Solution

### Step 1 — Race everyone (5 races)

Divide the 25 horses into 5 groups of 5. Race each group.

```
Group A: A1 > A2 > A3 > A4 > A5
Group B: B1 > B2 > B3 > B4 > B5
Group C: C1 > C2 > C3 > C4 > C5
Group D: D1 > D2 > D3 > D4 > D5
Group E: E1 > E2 > E3 > E4 > E5
```

After 5 races, you know the winner of each group. The losers within a group are not eliminated globally — they just lost *within their group*.

**Races used: 5**

---

### Step 2 — Race the 5 group winners (1 race)

Race A1, B1, C1, D1, E1 against each other.

Let's say the result is: **A1 > B1 > C1 > D1 > E1**

- **A1 is the fastest horse overall.** ✅ (#1 confirmed)
- D1 and E1 cannot be #2 or #3 (at least 3 horses are faster than them)
- All horses from Group D and Group E are eliminated

**Races used: 6**

---

### Step 3 — Race the remaining candidates (1 race)

Who can still be #2 or #3? Think carefully:

| Horse | Why still a candidate |
|-------|----------------------|
| A2 | Lost only to A1 (#1), could be #2 or #3 |
| A3 | Lost only to A1 and A2, could be #3 |
| B1 | Finished 2nd in race 6, could be #2 or #3 |
| B2 | Lost only to B1, could be #3 |
| C1 | Finished 3rd in race 6, could be #3 |

That's exactly **5 horses**. Race them.

The **1st and 2nd place** finishers of this race are your **#2 and #3 fastest horses**. ✅

**Races used: 7**

---

## Why Not 6?

After race 6, you know #1 (A1) but you have 5 candidates left for #2 and #3. You cannot determine 2 positions from 5 horses without racing them — one more race is unavoidable.

## Why Not 8?

You never need to re-race A1. Once confirmed as the global fastest, it is done. This saves you one race.

---

## Final Answer

**Minimum races = 5 + 1 + 1 = 7** ✅