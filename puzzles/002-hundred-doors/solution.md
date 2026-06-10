# ✅ Solution: 100 Doors

**Answer: Doors 1, 4, 9, 16, 25, 36, 49, 64, 81, 100 are open (perfect squares)**

---

## Key Observation

A door gets toggled once for **every walk number that divides it**.

In other words, door **N** is toggled during walk **i** if and only if **i is a divisor of N**.

So the total number of times door N is toggled = **total number of divisors of N**.

---

## When is a door open at the end?

- Door starts **closed**
- Each toggle flips it
- After an **odd** number of toggles → door is **open** ✅
- After an **even** number of toggles → door is **closed** ❌

So the question becomes: **which numbers have an odd number of divisors?**

---

## Why do perfect squares have odd divisors?

Divisors always come in **pairs**: if `i` divides `N`, then `N/i` also divides `N`.

Example — divisors of 12: (1,12), (2,6), (3,4) → 6 divisors → even → door closed.

**But** if `i × i = N` (i.e. N is a perfect square), then `i` pairs with itself — it's counted only once.

Example — divisors of 9: (1,9), (3,3) → but 3 is only counted once → 3 divisors → odd → door open ✅

---

## Verification

| Door | Divisors | Count | Open? |
|------|----------|-------|-------|
| 1 | 1 | 1 (odd) | ✅ |
| 2 | 1, 2 | 2 (even) | ❌ |
| 4 | 1, 2, 4 | 3 (odd) | ✅ |
| 9 | 1, 3, 9 | 3 (odd) | ✅ |
| 12 | 1, 2, 3, 4, 6, 12 | 6 (even) | ❌ |
| 16 | 1, 2, 4, 8, 16 | 5 (odd) | ✅ |
| 25 | 1, 5, 25 | 3 (odd) | ✅ |
| 100 | 1, 2, 4, 5, 10, 20, 25, 50, 100 | 9 (odd) | ✅ |

---

## Final Answer

The open doors are all **perfect squares ≤ 100**:

**1, 4, 9, 16, 25, 36, 49, 64, 81, 100** → 10 doors open ✅