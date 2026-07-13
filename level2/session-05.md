---
title: "Level 2 — Session 5: COUNTIF, SUMIF, AVERAGEIF, IFS, IFERROR"
layout: default
---
[← Session 4](session-04.md) | [Level 2 Overview](overview.md)

# Session 5: COUNTIF, SUMIF, AVERAGEIF, IFS, IFERROR

**1. Session Title:** COUNTIF, SUMIF, AVERAGEIF, IFS, IFERROR

**2. Learning Goal:** Learners can summarise data based on conditions, handle multiple conditions with IFS, and catch formula errors gracefully with IFERROR.

**3. Duration:** 2.5 hours

**4. Facilitator Preparation:** Use `l2_microloan_repayments.csv` — a good dataset for counting/summing by Status and Business Type.

**5. Materials Needed:** Laptop per learner, `l2_microloan_repayments.csv`, projector.

**6. Sample Dataset:** `l2_microloan_repayments.csv` — microloan tracker for women-owned small businesses.

**7. Live Demonstration Steps**
1. Build `=COUNTIF(range,"Fully Paid")` to count how many loans are fully repaid.
2. Build `=SUMIF(range,"Fully Paid",amount_range)` to total the value of fully repaid loans.
3. Build `=AVERAGEIF(range,"Tailoring",loan_range)` to find average loan size for tailoring businesses.
4. Introduce `IFS` for more than 2 outcomes: `=IFS(D2=0,"Not Started",D2<E2,"Partial",D2>=E2,"Complete")` to classify repayment progress.
5. Introduce `IFERROR` by intentionally creating a lookup error from Session 3, then wrapping it: `=IFERROR(VLOOKUP(...),"Not Found")`.

**8. Guided Hands-On Activity**
Together: build COUNTIF and SUMIF formulas to summarise loans by Status, then wrap one lookup formula in IFERROR to replace `#N/A` with a friendly message.

**9. Independent Practice Task**
Learners calculate: (a) total amount repaid by business type using SUMIF, (b) average loan amount for "Grocery Store" businesses using AVERAGEIF, (c) an IFS formula classifying each loan as "Fully Paid," "Partial," or "Not Paid" based on amounts (cross-checking against the existing Status column).

**10. Expected Output**
Working COUNTIF, SUMIF, AVERAGEIF, IFS, and at least one IFERROR-wrapped formula, all producing sensible results.

**11. Common Mistakes and Fixes**
- *Mistake:* Typing the condition without quotation marks (e.g. `=COUNTIF(range,Fully Paid)`). *Fix:* Remind learners text conditions always need quotation marks.
- *Mistake:* Mismatched range sizes between the condition range and the sum/average range in SUMIF/AVERAGEIF. *Fix:* Always check both ranges start and end on the same rows.
- *Mistake:* Using IFERROR to "hide" a real problem instead of fixing it. *Fix:* Teach IFERROR as a *last step* for genuinely expected issues (e.g. "not found" cases) — not a way to avoid understanding why a formula fails.

**12. Reflection Questions**
- How could COUNTIF/SUMIF help your NGO or cooperative report to donors monthly, without manual counting?
- When is it appropriate to use IFERROR versus fixing the root cause of an error?

**13. Assignment**
Build one COUNTIF or SUMIF formula summarising a real category in your own work.

**14. Facilitator Notes**
These "conditional" functions are some of the most immediately useful skills in the whole course for report-writing. Connect explicitly to real reporting tasks learners already do by hand.

---
[← Session 4](session-04.md) | [Level 2 Overview](overview.md) | [Next: Session 6 →](session-06.md)
