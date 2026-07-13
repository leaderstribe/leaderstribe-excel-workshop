---
title: "Level 2 — Session 2: Flash Fill & Data Validation / Dropdowns"
layout: default
---
[← Session 1](session-01.md) | [Level 2 Overview](overview.md)

# Session 2: Flash Fill & Data Validation / Dropdowns

**1. Session Title:** Flash Fill & Data Validation / Dropdowns

**2. Learning Goal:** Learners can use Flash Fill to quickly reformat data based on a pattern, and build dropdown lists to control what can be entered in a cell.

**3. Duration:** 2 hours

**4. Facilitator Preparation:** Use the split-name output from Session 1 (`l2_full_names_to_split.csv`) for Flash Fill practice, and `l2_microloan_repayments.csv` for dropdown practice (Status column).

**5. Materials Needed:** Laptop per learner, both datasets, projector.

**6. Sample Dataset:** `l2_full_names_to_split.csv` and `l2_microloan_repayments.csv` — a microloan repayment tracker for small women-owned businesses (tailoring, grocery, hairdressing, catering).

**7. Live Demonstration Steps**
1. In a new column next to Surname/First Name, type the first correct example of "Firstname Surname" order by hand.
2. Press Enter, then start typing the next one — show Excel suggesting the rest (Flash Fill preview), and press Enter to accept, or Ctrl+E to trigger Flash Fill manually.
3. Open `l2_microloan_repayments.csv`. Select the Status column cells, go to Data tab > Data Validation.
4. Choose "List" and type the allowed values: Fully Paid, Partial, Not Paid.
5. Show how a dropdown arrow now appears, and typing anything else gives an error.
6. Show how to add an input message and error alert for friendliness.

**8. Guided Hands-On Activity**
Together: use Flash Fill to reformat all names to "Firstname Surname," then add a dropdown list to the Status column with the 3 allowed values.

**9. Independent Practice Task**
Learners create a dropdown list for "Business Type" restricted to: Tailoring, Grocery Store, Hairdressing, Catering — and test that typing an invalid entry is blocked.

**10. Expected Output**
A reformatted names column (via Flash Fill) and a working dropdown-restricted Status/Business Type column.

**11. Common Mistakes and Fixes**
- *Mistake:* Flash Fill doesn't trigger because the pattern wasn't consistent in the first 1-2 examples. *Fix:* Show a clean, consistent first example before letting Flash Fill guess.
- *Mistake:* Data Validation list typed with inconsistent commas or spaces. *Fix:* When typing the list source, ensure no extra spaces between comma-separated items.
- *Mistake:* Learner believes Data Validation fixes data that's already wrong. *Fix:* Clarify: Data Validation only controls **new** entries going forward — it doesn't clean what's already there.

**12. Reflection Questions**
- Where in your own work could a dropdown prevent typing mistakes (e.g. inconsistent business names)?
- How did Flash Fill save you time compared to retyping everything?

**13. Assignment**
Build one dropdown list for a real recurring category in your own work (e.g. payment method, attendance status).

**14. Facilitator Notes**
Dropdowns are a favourite "aha" moment for learners who manage group records — connect it directly to reducing data entry errors in their savings groups or businesses.

---
[← Session 1](session-01.md) | [Level 2 Overview](overview.md) | [Next: Session 3 →](session-03.md)
