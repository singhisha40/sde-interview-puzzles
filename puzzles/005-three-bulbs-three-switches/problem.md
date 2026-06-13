# 💡 Problem: 3 Bulbs and 3 Switches

**Source:** GeeksForGeeks 100 Puzzles  
**Puzzle #:** 005  
**GFG Link:** https://www.geeksforgeeks.org/aptitude/puzzle-7-3-bulbs-and-3-switches/  
**Difficulty:** Easy  
**Topic:** Logic / Observation / State Encoding  
**Asked at:** MakeMyTrip, Qualcomm

---

## Problem Statement

You are standing **outside a closed room** that contains **3 light bulbs**.

Outside the room, there are **3 switches** — each connected to exactly one bulb — but you don't know which switch controls which bulb.

**Rules:**
- You may turn the switches on or off in **any combination** before entering
- You can enter the room **only once**
- Once inside, you **cannot touch the switches again**
- You can only **observe the bulbs** from inside

**How do you determine which switch controls which bulb?**

---

## Constraints

- Exactly 3 switches, exactly 3 bulbs, one-to-one mapping
- Only one entry into the room allowed
- No tools, no mirrors, no second person
- All bulbs are working (none are burnt out)

---

## Expected Answer

Use **both light and heat** from the bulbs as two independent sources of information — giving you 3 distinguishable states from just one room visit.