# 🥇 Problem: Pay an Employee Using a Gold Rod of 7 Units

**Source:** GeeksForGeeks 100 Puzzles  
**Puzzle #:** 003  
**GFG Link:** https://www.geeksforgeeks.org/aptitude/puzzle-4-pay-an-employee-using-a-gold-rod-of-7-units/  
**Difficulty:** Easy  
**Topic:** Logic / Binary Representation

---

## Problem Statement

An employee works for an employer for **7 days**.  
The employer has a **gold rod of 7 units** in length.

The employer must pay the employee **1 unit of gold per day** — so that at the end of each day, the employee's total gold increases by exactly 1 unit.

**Rules:**
- The employer can make **at most 2 cuts** in the rod
- After each cut, there are pieces that can be given or taken back as change
- The employee cannot spend any part of the rod during the 7 days

**How should the employer cut and distribute the gold rod?**

---

## Constraints

- Exactly 7 days of work
- Gold rod = 7 units total length
- Maximum 2 cuts allowed (produces at most 3 pieces)
- Each day the employee must hold gold totalling exactly that day's number (1 on day 1, 2 on day 2... 7 on day 7)
- The employer can give pieces and also take back pieces as change

---

## Expected Answer

Cut the rod into pieces of **1, 2, and 4 units**.  
Using these three pieces, the employer can pay exactly 1 unit per day for all 7 days.