---
title: "Level 1 — Session 6: Basic Formulas & Functions"
layout: default
---
[← Session 5](session-05.md) | [Level 1 Overview](overview.md)

# Session 6: Basic Formulas & Functions

**1. Session Title:** Basic Formulas & Functions

**2. Learning Goal:** Learners can write simple formulas (+, -, *, /) and use SUM, AVERAGE, MIN, MAX, and COUNT.

**3. Duration:** 2 hours

**4. Facilitator Preparation:** Use `l1_market_sales.csv`. Prepare a simple explanation of "cell reference" vs "typing the number directly."

**5. Materials Needed:** Laptop per learner, `l1_market_sales.csv`, projector.

**6. Sample Dataset:** `l1_market_sales.csv` — market sales by trader, item, quantity, and unit price.

**7. Live Demonstration Steps**
1. Show that every formula starts with `=`.
2. Build `=Quantity*UnitPrice` manually in a new column to double check the Total Sales column.
3. Introduce `=SUM(range)` to total all sales.
4. Introduce `=AVERAGE(range)` to find average sale value.
5. Introduce `=MIN()` and `=MAX()` to find smallest and largest sales.
6. Introduce `=COUNT()` to count how many sales were recorded.
7. Show the difference between typing a number and clicking a cell reference — and why cell references are better (they update automatically).

**8. Guided Hands-On Activity**
Together: build a small summary box below the data showing Total Sales, Average Sale, Highest Sale, and Number of Transactions using the functions above.

**9. Independent Practice Task**
Learners calculate: total quantity sold, average unit price, and the highest single sale — using formulas, not by reading and calculating manually.

**10. Expected Output**
A working summary box with 4 correct formula-based answers that update if the data changes.

**11. Common Mistakes and Fixes**
- *Mistake:* Typing numbers directly into a formula instead of referencing cells. *Fix:* Show what happens when you change the original number — the direct-number formula doesn't update, but the cell-reference formula does.
- *Mistake:* Forgetting the `=` sign, so Excel just shows text. *Fix:* Remind learners every formula begins with `=`.
- *Mistake:* Selecting the wrong range in SUM/AVERAGE. *Fix:* Teach learners to click-and-drag to select the range instead of typing cell references from memory.

**12. Reflection Questions**
- Why is a formula better than a calculator for repeated work?
- Which of these 4 functions (SUM, AVERAGE, MIN, MAX) would be most useful in your own work?

**13. Assignment**
Using your own data (or the market sales file), calculate total, average, min, and max for any numeric column.

**14. Facilitator Notes**
Some learners fear "formulas" as a scary word. Reframe it early: "A formula is just a question you're asking Excel to answer for you."

---
[← Session 5](session-05.md) | [Level 1 Overview](overview.md) | [Next: Session 7 →](session-07.md)
