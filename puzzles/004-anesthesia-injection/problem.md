# 💉 Problem: Finding the Injection for Anesthesia

**Source:** GeeksForGeeks 100 Puzzles  
**Puzzle #:** 004  
**GFG Link:** https://www.geeksforgeeks.org/aptitude/puzzle-5-finding-the-injection-for-anesthesia/  
**Difficulty:** Medium  
**Topic:** Logic / Ternary Number System

---

## Problem Statement

In a medical laboratory, there are **240 injections**. Exactly **one** of them contains anesthesia.

You have **5 rats** to help identify the anesthetic injection.

**Rules:**
- If a rat is given the anesthetic injection, it will **faint within 24 hours**
- Once a rat faints, it **cannot be used again**
- A rat can be given **more than one injection** at different times (as long as it hasn't fainted)
- You have a total of **48 hours** to find the injection

**Which injection contains the anesthesia?**

---

## Constraints

- Exactly 240 injections, exactly 1 is anesthetic
- Only 5 rats available
- 48 hours total = 2 rounds of 24 hours
- A rat that faints in round 1 cannot participate in round 2
- You must identify the exact injection, not just narrow it down

---

## Expected Answer

By numbering injections in **base 3 (ternary)** using 5 digits, and assigning each rat to one digit position, you can identify the anesthetic injection among up to **243 injections** — covering all 240 — in exactly 2 rounds.