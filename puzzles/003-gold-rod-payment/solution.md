# ✅ Solution: Pay an Employee Using a Gold Rod of 7 Units

**Answer: Make 2 cuts to get pieces of 1, 2, and 4 units.**

---

## The Cuts

```
Original rod: [━━━━━━━━━━━━━━━] 7 units

After 2 cuts:
  [━] 1 unit
  [━━━] 2 units
  [━━━━━━━] 4 units
```

---

## Day-by-Day Payment Table

| Day | Employer Action | Employee Holds | Total Gold |
|-----|----------------|---------------|------------|
| 1 | Give **1** | 1 | 1 ✅ |
| 2 | Take back **1**, give **2** | 2 | 2 ✅ |
| 3 | Give **1** | 1 + 2 | 3 ✅ |
| 4 | Take back **1** and **2**, give **4** | 4 | 4 ✅ |
| 5 | Give **1** | 4 + 1 | 5 ✅ |
| 6 | Take back **1**, give **2** | 4 + 2 | 6 ✅ |
| 7 | Give **1** | 4 + 2 + 1 | 7 ✅ |

---

## Why 1, 2, and 4?

These are **powers of 2**: 2⁰, 2¹, 2²

Just like binary numbers, any value from 1 to 7 can be represented as a combination of 1, 2, and 4:

| Value | Binary | Pieces used |
|-------|--------|-------------|
| 1 | 001 | 1 |
| 2 | 010 | 2 |
| 3 | 011 | 2 + 1 |
| 4 | 100 | 4 |
| 5 | 101 | 4 + 1 |
| 6 | 110 | 4 + 2 |
| 7 | 111 | 4 + 2 + 1 |

Notice: 7 = 2³ - 1, so 3 pieces (after 2 cuts) are exactly enough to cover all 7 days.

---

## Why Not Other Cut Combinations?

| Cuts | Pieces | Can cover 1–7? |
|------|--------|----------------|
| 1, 1, 5 | 3 pieces | ❌ Can't make 2, 3, 4, 6 |
| 1, 3, 3 | 3 pieces | ❌ Can't make 2, 4, 5, 6 |
| 2, 2, 3 | 3 pieces | ❌ Can't make 1, 4, 5, 6 |
| **1, 2, 4** | **3 pieces** | **✅ Covers all 1–7** |

Only the powers-of-2 split works.

---

## Final Answer

**Cut positions:** After unit 1, and after unit 3 (giving pieces of 1, 2, 4)  
**Total cuts used:** 2 ✅  
**All 7 days covered:** ✅