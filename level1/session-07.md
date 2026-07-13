---
title: "Level 1 — Session 7: IF Statements & Simple Charts"
layout: default
---
[← Session 6](session-06.md) | [Level 1 Overview](overview.md)

# Session 7: IF Statements & Simple Charts

**1. Session Title:** IF Statements & Simple Charts

**2. Learning Goal:** Learners can write a basic IF formula to classify data, and build a simple column or pie chart.

**3. Duration:** 2.5 hours

**4. Facilitator Preparation:** Use `l1_savings_group_contributions.csv`. Decide the IF logic in advance (e.g. "Full" if contribution = 2000, "Short" if less).

**5. Materials Needed:** Laptop per learner, `l1_savings_group_contributions.csv`, projector.

**6. Sample Dataset:** `l1_savings_group_contributions.csv`.

**7. Live Demonstration Steps**
1. Explain IF in plain language: "IF something is true, do this; otherwise, do that."
2. Build `=IF(D2>=2000,"Full Payment","Short Payment")` in a new column.
3. Copy the formula down the column and check results make sense.
4. Select the Town column and Contribution column (using Ctrl to select non-adjacent columns), then Insert > Column Chart.
5. Add a chart title and axis labels.
6. Build a simple Pie Chart showing total contribution by town.

**8. Guided Hands-On Activity**
Together: write the IF formula for Payment Status, then build one column chart showing contributions by member for Week 3.

**9. Independent Practice Task**
Learners write their own IF formula (e.g. classify contributions as "Above Average" or "Below Average" using the AVERAGE from Session 6), then create a pie chart of contributions by town.

**10. Expected Output**
A working IF-based classification column and one properly labelled chart.

**11. Common Mistakes and Fixes**
- *Mistake:* Missing quotation marks around text results in IF (e.g. `=IF(D2>=2000,Full,Short)`). *Fix:* Remind learners that any text inside a formula needs quotation marks.
- *Mistake:* Selecting the wrong data range for the chart, producing a confusing chart. *Fix:* Always select headers + data together, and check the chart preview before finalising.
- *Mistake:* Comparing text instead of numbers (e.g. contribution stored as text "2000" instead of number 2000). *Fix:* Confirm the column is truly numeric (right-aligned) before writing the IF formula.

**12. Reflection Questions**
- How could an IF formula help you flag which members are behind on contributions?
- Which chart type told the "story" of the data better — column or pie? Why?

**13. Assignment**
Build one IF formula and one chart using your own data before next session.

**14. Facilitator Notes**
Charts often produce the biggest "wow" reaction of the whole workshop. Let learners enjoy this moment — it's a great confidence boost heading into the final session.

---
[← Session 6](session-06.md) | [Level 1 Overview](overview.md) | [Next: Session 8 →](session-08.md)
