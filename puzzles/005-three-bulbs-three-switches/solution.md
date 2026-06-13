# ✅ Solution: 3 Bulbs and 3 Switches

**Answer: Use heat as a second signal — turn one switch on for 10 minutes, then off. Turn another switch on. Leave the third off. Enter the room.**

---

## Step-by-Step Solution

### Before entering the room

| Switch | Action |
|--------|--------|
| Switch 1 | Turn ON for **5–10 minutes**, then turn **OFF** |
| Switch 2 | Turn **ON** (leave it on) |
| Switch 3 | Leave **OFF** the entire time |

### Enter the room — observe the bulbs

Each bulb will now be in one of three distinct states:

| Bulb state | Controlled by |
|------------|--------------|
| **ON (glowing)** | Switch 2 ✅ |
| **OFF but WARM** | Switch 1 ✅ (was on, now off — still warm) |
| **OFF and COLD** | Switch 3 ✅ (never turned on) |

---

## Why This Works

If you only used light (on/off), you'd have:
- Switch 2 → bulb is on ✅ (identified)
- Switch 1 and 3 → both bulbs are off ❌ (can't tell them apart)

The trick is that **a recently switched-off bulb retains heat** for several minutes. This gives you a **third state** — off-but-warm — that distinguishes Switch 1's bulb from Switch 3's bulb.

```
States used:
  Light ON          → Switch 2
  Light OFF + Warm  → Switch 1 (was on, now cooling)
  Light OFF + Cold  → Switch 3 (was never on)
```

Three switches → three states → one visit ✅

---

## What Would Happen Without the Heat Trick?

If you just turned Switch 1 on and Switch 2 off (both off when you enter), you'd see two dark bulbs with no way to tell which is which. You'd need a second entry — which isn't allowed.

---

## Final Answer

**Turn Switch 1 on for 10 min then off → Turn Switch 2 on → Enter room → Glowing = Switch 2, Warm = Switch 1, Cold = Switch 3** ✅