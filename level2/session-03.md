---
title: "Level 2 — Session 3: VLOOKUP"
layout: default
---
[← Session 2](session-02.md) | [Level 2 Overview](overview.md)

# Session 3: VLOOKUP 

**1. Session Title:** VLOOKUP

**2. Learning Goal:** Learners can look up information from one table into another using the VLOOKUP function.

**3. Duration:** 1.5 hours

**4. Facilitator Preparation:** Use `l2_cooperative_sales_data.csv` alongside `l2_lookup_reference_table.csv` (Product Code/Category/Standard Price reference).

**5. Materials Needed:** Laptop per learner, both datasets, projector.

**6. Sample Dataset:** `l2_cooperative_sales_data.csv` — sales orders from women's cooperatives in Nairobi and Mombasa, and `l2_lookup_reference_table.csv` — a clean reference table of product codes and standard prices.

**7. Live Demonstration Steps**
1. Explain the goal: "I want Excel to find the Standard Price automatically, instead of me typing it in by hand."
2. Build `=VLOOKUP(lookup_value, table_array, col_index_num, FALSE)` step by step: pick the Product name as the lookup value, select the reference table, count columns to find col_index_num, and always use FALSE for exact match.
3. Show a common error: forgetting FALSE, which causes wrong/approximate matches.

**8. Guided Hands-On Activity**
Together: build one VLOOKUP formula to pull Standard Price into the cooperative sales sheet.

**9. Independent Practice Task**
Learners add a "Category" column to the sales data and use VLOOKUP to pull it in automatically from the reference table.

**10. Expected Output**
A sales sheet with an automatically-filled Category (or Price) column, matched correctly for every row.

**11. Common Mistakes and Fixes**
- *Mistake:* Forgetting to lock the reference table range with `$` (absolute reference) when copying the formula down, causing it to shift and break. *Fix:* Teach F4 to quickly add `$` signs, and show what happens without it.
- *Mistake:* Using TRUE (approximate match) instead of FALSE (exact match), returning wrong results. *Fix:* Repeat the rule: "For name/code lookups, always use FALSE."
- *Mistake:* Lookup value has extra spaces or different capitalization than the reference table. *Fix:* Revisit TRIM/PROPER from Level 1 Session 4 — clean data enables reliable lookups.

**12. Reflection Questions**
- Why do lookups fail so often when data isn't clean — what does this tell you about the order of Excel skills?

**13. Assignment**
Build one lookup formula connecting two of your own real lists (e.g. member names to phone numbers, or product to price).

**14. Facilitator Notes**
This session is often where learners feel like "real" data analysts for the first time. Expect `#N/A` errors — treat them as a normal debugging step, not a failure.

---
[← Session 2](session-02.md) | [Level 2 Overview](overview.md) | [Next: Session 4 →](session-04.md)
