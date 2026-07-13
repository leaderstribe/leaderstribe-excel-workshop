---
title: "Level 2 — Session 6: PivotTables"
layout: default
---
[← Session 5](session-05.md) | [Level 2 Overview](overview.md)

# Session 6: PivotTables

**1. Session Title:** PivotTables

**2. Learning Goal:** Learners can build a basic PivotTable to summarise large data by category without writing formulas.

**3. Duration:** 2.5 hours

**4. Facilitator Preparation:** Use `l2_cooperative_sales_data.csv` — good size and structure for a first PivotTable (Cooperative, Region, Product, Month, Units Sold).

**5. Materials Needed:** Laptop per learner, `l2_cooperative_sales_data.csv`, projector.

**6. Sample Dataset:** `l2_cooperative_sales_data.csv` — sales orders across 3 cooperatives, multiple products, and 3 months.

**7. Live Demonstration Steps**
1. Convert the data range to a Table first (Ctrl+T) — reinforce the Level 1 Session 5 habit.
2. Insert > PivotTable, placing it on a new worksheet.
3. Drag "Cooperative" to Rows, "Units Sold" to Values (confirm it shows Sum, not Count).
4. Drag "Month" to Columns to see units sold by cooperative, broken down by month.
5. Add "Product" to Filters, and show how filtering to one product changes the whole table.
6. Rename Value field labels to something clear, e.g. "Sum of Units Sold" → "Total Units Sold."

**8. Guided Hands-On Activity**
Together: build a PivotTable showing Total Units Sold by Cooperative and Month, then add Product as a filter.

**9. Independent Practice Task**
Learners build their own PivotTable showing Total Sales Value (Units Sold × Unit Price — may need a helper column first) by Region and Category.

**10. Expected Output**
A working PivotTable correctly summarising sales data by at least two dimensions (e.g. Cooperative and Month).

**11. Common Mistakes and Fixes**
- *Mistake:* Source data isn't a proper Table, so the PivotTable doesn't auto-update with new rows. *Fix:* Always convert to a Table before building a PivotTable.
- *Mistake:* Values area shows "Count" instead of "Sum" because of one blank or text cell in the column. *Fix:* Check the column for stray blanks/text, clean it, then click Value Field Settings to change Count to Sum.
- *Mistake:* Learner feels overwhelmed by the Field List. *Fix:* Teach the 4 boxes one at a time (Filters, Rows, Columns, Values) using the plain-language framing: "Rows = what to group by, Values = what to measure."

**12. Reflection Questions**
- What would take you the longest to calculate by hand that a PivotTable just did in seconds?
- Which two categories in your own data would you most want to compare with a PivotTable?

**13. Assignment**
Build a PivotTable using two of your own real categories (e.g. contributions by member and by month).

**14. Facilitator Notes**
Expect a mix of excitement and intimidation. Slow down when introducing the Field List — this is often the single biggest confidence-building moment of Level 2 once it clicks.

---
[← Session 5](session-05.md) | [Level 2 Overview](overview.md) | [Next: Session 7 →](session-07.md)
