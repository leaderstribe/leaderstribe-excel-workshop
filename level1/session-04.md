---
title: "Level 1 — Session 4: Basic Data Cleaning"
layout: default
---
[← Session 3](session-03.md) | [Level 1 Overview](overview.md)

# Session 4: Basic Data Cleaning

**1. Session Title:** Basic Data Cleaning

**2. Learning Goal:** Learners can spot and fix common data problems: inconsistent capitalization, extra spaces, blank cells, and simple typos.

**3. Duration:** 2 hours

**4. Facilitator Preparation:** Use `l1_savings_group_contributions.csv` (note "chidinma eze" lowercase vs "Chidinma Eze"). Highlight these inconsistencies beforehand so you can point them out live.

**5. Materials Needed:** Laptop per learner, `l1_savings_group_contributions.csv`, projector.

**6. Sample Dataset:** `l1_savings_group_contributions.csv` — contains a genuine inconsistent name entry ("chidinma eze" vs "Chidinma Eze") and a blank cell (Fatima Bello, Week 2 absent).

**7. Live Demonstration Steps**
1. Point out "chidinma eze" typed in lowercase in Week 1 — explain Excel treats this as a different-looking entry than "Chidinma Eze," which can break sorting/lookups later.
2. Use the `PROPER()` function in a helper column to auto-capitalise names correctly.
3. Use `TRIM()` to remove extra spaces from a cell.
4. Use Find & Replace to standardise "Cash " (with trailing space) to "Cash."
5. Show how to identify blank cells using Ctrl+G > Special > Blanks.
6. Discuss: should a blank mean "zero" or "no data"? Decide together and fill consistently.

**8. Guided Hands-On Activity**
Together: create a helper column with `=PROPER(A2)` to fix all names, then copy-paste as values over the original column.

**9. Independent Practice Task**
Learners find and fix all inconsistent entries in the Payment Method column, and decide how to handle the blank contribution for Fatima Bello in Week 2.

**10. Expected Output**
A cleaned dataset with consistent name capitalization, no stray spaces, and a clear decision recorded for blank cells.

**11. Common Mistakes and Fixes**
- *Mistake:* Deleting the original data before checking the helper column is correct. *Fix:* Always keep a helper column temporarily; only delete the original after confirming with Paste Special > Values.
- *Mistake:* Confusing `TRIM()` with deleting the whole cell. *Fix:* Demonstrate that TRIM only removes extra spaces, not the text itself.
- *Mistake:* Leaving blanks without deciding what they mean. *Fix:* Always ask the group: does blank = 0, or blank = "not yet recorded"?

**12. Reflection Questions**
- Why can messy data cause wrong totals or lookup errors later?
- What's one habit you can build now to avoid messy data in your own records?

**13. Assignment**
Take any list you keep by hand (attendance, sales, contributions) and check it for capitalization and spacing inconsistencies.

**14. Facilitator Notes**
This is the session where learners often say "ah, so THAT's why my totals were wrong before!" Let that realisation land — it builds strong motivation for the rest of the course.

---
[← Session 3](session-03.md) | [Level 1 Overview](overview.md) | [Next: Session 5 →](session-05.md)
