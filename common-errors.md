---
title: Common Learner Errors and Fixes
layout: default
---

# Common Learner Errors and Fixes

A quick-reference cheat sheet for the mistakes you'll see most often, organised by topic. (Each session page also has its own specific list — this page is the consolidated "in-class emergency reference.")

## General / navigation
- **Frozen or unresponsive screen fear:** learner thinks she has "broken" the laptop. Fix: teach Ctrl+Z (Undo) as the very first shortcut, before anything else.
- **Lost file:** learner can't find where she saved. Fix: always save into one shared, clearly labelled folder created on Day 1.

## Data entry & formatting
- **Numbers stored as text** (left-aligned instead of right-aligned): breaks SUM/AVERAGE later. Fix: retype using Format Cells > Number, or use Text to Columns with no delimiter to force conversion.
- **Formatting mistaken for changing the value:** learner worries currency formatting altered her numbers. Fix: show the Formula Bar still shows the raw number.

## Sorting & filtering
- **Sorting one column only, scrambling rows:** Fix: always select the full table, or use Excel's prompt to "expand the selection."
- **Forgetting a filter is still active:** Fix: point out the small funnel icon on filtered headers.

## Cleaning
- **Inconsistent capitalization/spacing breaks lookups and grouping later** (e.g. "cash" vs "Cash "). Fix: PROPER() and TRIM(), then Paste Special > Values.
- **Deciding blanks = 0 inconsistently:** Fix: agree as a group what blank means before cleaning further.

## Tables
- **Typing new data below the Table instead of inside it:** Fix: show the blue corner handle marking the Table boundary.

## Formulas & functions
- **Missing `=` sign:** formula shows as plain text. Fix: remind learners every formula starts with `=`.
- **Typing numbers directly instead of referencing cells:** formula won't update automatically. Fix: demonstrate the difference live by changing the source number.
- **Missing quotation marks around text in IF/COUNTIF/SUMIF:** Fix: repeat rule — text conditions always need quotes.

## Lookups (VLOOKUP / XLOOKUP / INDEX-MATCH)
- **Using TRUE instead of FALSE (approximate vs exact match):** Fix: repeat rule — always FALSE (or 0 in MATCH) for name/code lookups.
- **Reference table range shifts when copied down (missing `$` absolute references):** Fix: teach F4 to lock ranges.
- **Lookup value doesn't match due to spacing/capitalization:** Fix: revisit TRIM/PROPER cleaning before troubleshooting the formula itself.

## PivotTables, PivotCharts & Slicers
- **Values area shows Count instead of Sum:** usually caused by one blank/text cell in the column. Fix: clean the column, then Value Field Settings > Sum.
- **Source data not a Table:** PivotTable won't auto-update with new rows. Fix: always Ctrl+T before building a PivotTable.
- **Slicer doesn't filter the chart:** Fix: check Report Connections to confirm the Slicer is linked to the right PivotTable.

## Dashboards
- **Too many elements crammed onto one page:** Fix: recommend 1 chart + 1–2 KPI cells + 1 Slicer as a solid first dashboard.

---
[← Back to Home](index.md)
