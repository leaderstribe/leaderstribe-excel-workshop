---
title: "Level 2 — Session 1: Remove Duplicates & Text-to-Columns"
layout: default
---
[← Level 2 Overview](overview.md)

# Session 1: Remove Duplicates & Text-to-Columns

**1. Session Title:** Remove Duplicates & Text-to-Columns

**2. Learning Goal:** Learners can identify and remove duplicate records safely, and split one column of combined text into separate columns.

**3. Duration:** 2 hours

**4. Facilitator Preparation:** Load `l2_ngo_beneficiaries_duplicates.csv` (contains 2 genuine duplicate rows) and `l2_full_names_to_split.csv` (surname-first names to split).

**5. Materials Needed:** Laptop per learner, both datasets above, projector.

**6. Sample Dataset:** `l2_ngo_beneficiaries_duplicates.csv` — an NGO beneficiary list with accidental duplicate entries (common when multiple field officers register the same person). `l2_full_names_to_split.csv` — names stored as "Surname Firstname" needing to be split.

**7. Live Demonstration Steps**
1. Open `l2_ngo_beneficiaries_duplicates.csv` and manually point out the two duplicate rows (Beneficiary ID B001 and B002 appear twice).
2. Select the data, go to Data tab > Remove Duplicates, choose to check all columns, and run it. Show the confirmation message ("2 duplicate values found and removed").
3. Discuss: what if only SOME columns match, not all? Decide as a group what counts as a "true duplicate" (e.g. same Beneficiary ID + same Phone Number).
4. Open `l2_full_names_to_split.csv`. Select the Full Name column, go to Data tab > Text to Columns.
5. Choose "Delimited," select "Space" as the delimiter, and finish — showing the name split into two columns.
6. Rename the new columns "Surname" and "First Name."

**8. Guided Hands-On Activity**
Together: run Remove Duplicates on the NGO beneficiary list and confirm the row count drops correctly. Then split the names file using Text to Columns.

**9. Independent Practice Task**
Learners must decide, before running Remove Duplicates, which columns should be checked to define "duplicate," then apply it and report how many duplicates were found.

**10. Expected Output**
A cleaned beneficiary list with duplicates removed, and a names file with Surname and First Name in separate columns.

**11. Common Mistakes and Fixes**
- *Mistake:* Running Remove Duplicates on the wrong selection (missing some columns), which removes rows that aren't really duplicates. *Fix:* Always select the FULL data range, headers included, before starting.
- *Mistake:* Not making a backup copy before removing duplicates — this is destructive and cannot always be undone after saving. *Fix:* Teach the habit: **Save a copy first**, always, before Remove Duplicates.
- *Mistake:* Choosing the wrong delimiter in Text to Columns (e.g. comma instead of space). *Fix:* Use the Preview window in the Text to Columns wizard before clicking Finish.

**12. Reflection Questions**
- Why might the same beneficiary get registered twice in real NGO fieldwork?
- What could go wrong if you remove duplicates without checking first?

**13. Assignment**
Find a real list (from a WhatsApp group, phone contacts, or club register) and check it for duplicate entries.

**14. Facilitator Notes**
Stress the "backup before you clean" habit strongly here — this is the first genuinely destructive tool in the course. Make it a rule, not a suggestion.

---
[← Level 2 Overview](overview.md) | [Next: Session 2 →](session-02.md)
