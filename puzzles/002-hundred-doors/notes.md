# 📝 Notes: 100 Doors

---

## What Tripped Me Up

My first instinct was to simulate it — manually track every door for all 100 walks. That would work but it completely misses the elegant pattern.

The real challenge is resisting the urge to brute-force it and instead asking: *"Is there a pattern here?"*

---

## The Key Insight

> **A door stays open only if it's toggled an odd number of times.**  
> **A number has an odd number of divisors only if it's a perfect square.**

This is the entire puzzle in two lines. Once you see this, the answer is immediate.

The deeper idea: divisors pair up (i and N/i), which makes the count even — *unless* the number is a perfect square, where the square root pairs with itself and contributes just one toggle instead of two.

---

## The "aha" Moment

Thinking about door 36:
- Toggled on walks: 1, 2, 3, 4, 6, 9, 12, 18, 36
- That's 9 divisors → odd → open ✅
- 36 = 6² → perfect square → makes sense!

Thinking about door 24:
- Toggled on walks: 1, 2, 3, 4, 6, 8, 12, 24
- That's 8 divisors → even → closed ❌
- 24 is not a perfect square → makes sense!

---

## Pattern to Remember

This puzzle is really about **properties of divisors**, which shows up in:
- Number theory problems
- Sieve of Eratosthenes
- Finding factors efficiently in coding problems
- Any problem involving "how many times does X happen to N?"

---

## Interview Tips

- Don't start simulating — the interviewer wants to see you find the pattern
- Say: *"A door toggles once per divisor. Divisors come in pairs, except for perfect squares."*
- List the 10 open doors confidently: 1, 4, 9, 16, 25, 36, 49, 64, 81, 100
- Bonus: generalise — *"For N doors, the answer is all perfect squares up to N, so ⌊√N⌋ doors will be open"*

---

## Difficulty Felt: 4/10

Slightly harder than the horses puzzle because you need to connect "odd number of toggles" → "odd number of divisors" → "perfect squares." Each step is simple, but you need all three together.

---

## Date Solved: June 2026