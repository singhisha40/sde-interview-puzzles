# 🚪 Problem: 100 Doors

**Source:** GeeksForGeeks 100 Puzzles  
**Puzzle #:** 002  
**Difficulty:** Easy  
**Topic:** Logic / Number Theory / Divisors

---

## Problem Statement

There are **100 doors** in a row, all **initially closed**.

A person walks through the row multiple times and **toggles** doors (if a door is open → close it; if closed → open it) in the following pattern:

- **Walk 1:** Toggle every door (1, 2, 3, 4, ... 100)
- **Walk 2:** Toggle every 2nd door (2, 4, 6, 8, ...)
- **Walk 3:** Toggle every 3rd door (3, 6, 9, 12, ...)
- **Walk 4:** Toggle every 4th door (4, 8, 12, ...)
- ...and so on until...
- **Walk 100:** Toggle only the 100th door

**Which doors are open at the end?**

---

## Constraints

- All 100 doors start closed
- Toggle means: open ↔ closed
- The pattern continues for exactly 100 walks
- You must find ALL doors that remain open

---

## Expected Answer

Doors **1, 4, 9, 16, 25, 36, 49, 64, 81, and 100** are open.  
These are the **perfect squares** between 1 and 100.