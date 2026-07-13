---
title: "Level 2 — Session 4: INDEX-MATCH"
layout: default
---
[← Session 3](session-03.md) | [Level 2 Overview](overview.md)

# Session 4: INDEX-MATCH

**1. Session Title:** INDEX-MATCH

**2. Learning Goal:** Learners understand why INDEX-MATCH is more flexible than VLOOKUP and can build a basic INDEX-MATCH formula.

**3. Duration:** 2 hours

**4. Facilitator Preparation:** Reuse `l2_cooperative_sales_data.csv` and `l2_lookup_reference_table.csv`. Prepare one example where VLOOKUP would fail (looking up a column to the LEFT of the lookup column) to show INDEX-MATCH's advantage.

**5. Materials Needed:** Laptop per learner, both datasets, projector.

**6. Sample Dataset:** `l2_cooperative_sales_data.csv` and `l2_lookup_reference_table.csv`.

**7. Live Demonstration Steps**
1. Show the limitation: VLOOKUP can only look to the right of the lookup column. Set up a scenario where you need to look up Product Code from Product Name (Code is to the left in the reference table) — VLOOKUP struggles here.
2. Introduce `MATCH(lookup_value, lookup_array, 0)` alone first — show it returns a *position number*, not the value itself.
3. Introduce `INDEX(return_array, row_number)` alone — show it returns a value from a given position.
4. Combine them: `=INDEX(return_array, MATCH(lookup_value, lookup_array, 0))`.
5. Use this combined formula to solve the "look to the left" problem that VLOOKUP couldn't.

**8. Guided Hands-On Activity**
Together: build one INDEX-MATCH formula that looks up Product Code using Product Name, where Code sits to the left of Name in the reference table.

**9. Independent Practice Task**
Learners build their own INDEX-MATCH formula to pull Standard Price using Product Name, and compare the result to the VLOOKUP version from Session 3.

**10. Expected Output**
A correct INDEX-MATCH formula producing the same result as VLOOKUP, but demonstrated on a "look left" scenario VLOOKUP can't handle.

**11. Common Mistakes and Fixes**
- *Mistake:* Mixing up the order of arguments inside MATCH. *Fix:* Read the formula aloud as a sentence: "Find [this value] inside [this list], give me an exact match (0)."
- *Mistake:* Forgetting the `0` (exact match) inside MATCH. *Fix:* Repeat the same discipline as VLOOKUP's FALSE — always specify exact match for name/code lookups.
- *Mistake:* Believing INDEX-MATCH is "harder" and avoiding it. *Fix:* Reassure learners it's normal to find this the hardest formula in the course — mastery comes with repetition, not immediate ease.

**12. Reflection Questions**
- What is one situation in your own work where VLOOKUP would fail but INDEX-MATCH would work?
- Do you feel more confident with VLOOKUP or INDEX-MATCH right now — and why?

**13. Assignment**
Try rebuilding your Session 3 lookup formula using INDEX-MATCH instead, and note any differences you notice.

**14. Facilitator Notes**
This is the most conceptually demanding session in Level 2. It's fine to spend extra time here and revisit briefly in Session 5. Do not skip the "why" — understanding beats memorising.

---
[← Session 3](session-03.md) | [Level 2 Overview](overview.md) | [Next: Session 5 →](session-05.md)
