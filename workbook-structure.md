---
title: Downloadable Practice Workbook Structure
layout: default
---

# Downloadable Practice Workbook Structure

This describes how to assemble the single Excel workbook (`.xlsx`) that facilitators hand out to each learner at the start of the workshop, combining all datasets into one file with clear navigation tabs.

## Recommended sheet order

1. **Cover** — Workshop name, learner name field, level (1 or 2), facilitator name, cohort dates.
2. **Instructions** — One paragraph explaining how to use the workbook, plus a list of sheet tabs and what each is for.
3. **L1-Attendance** — from `l1_attendance_register.csv`
4. **L1-Savings** — from `l1_savings_group_contributions.csv`
5. **L1-MarketSales** — from `l1_market_sales.csv`
6. **L1-EnterpriseDirectory** — from `l1_women_enterprise_directory.csv`
7. **L1-Capstone-Blank** — an empty sheet with placeholder headers for learners to build their own "Everyday Data Story"
8. **L2-Duplicates** — from `l2_ngo_beneficiaries_duplicates.csv`
9. **L2-NamesToSplit** — from `l2_full_names_to_split.csv`
10. **L2-CommunityHealth** — from `l2_community_health_data.csv`
11. **L2-CoopSales** — from `l2_cooperative_sales_data.csv`
12. **L2-LookupReference** — from `l2_lookup_reference_table.csv`
13. **L2-Microloans** — from `l2_microloan_repayments.csv`
14. **L2-Capstone-Blank** — an empty sheet with placeholder headers for "Community Data in Action"

## Tab colour convention
- Grey: Cover / Instructions
- Green: Level 1 practice sheets
- Blue: Level 2 practice sheets
- Yellow: Capstone blank sheets

## Facilitator build steps
1. Create a new blank workbook.
2. Import each CSV from the [datasets folder](datasets/) as a new sheet (Data > Get Data > From Text/CSV, or copy-paste values).
3. Rename each tab according to the list above and apply the colour convention.
4. Freeze the header row on every data sheet (see Level 1, Session 2).
5. Protect the Cover and Instructions sheets (Review > Protect Sheet) so learners don't accidentally edit them.
6. Save as `LeadersTribe_ExcelWorkshop_PracticeWorkbook.xlsx` and distribute via USB drive, shared folder, or email — do not assume reliable internet.

## Why one combined workbook?
A single file is easier for learners to keep track of, mirrors how real organisational workbooks are structured (multiple related sheets), and reduces the "which file was that again?" confusion common in multi-file workshops.

---
[← Back to Home](index.md)
