# leaderstribe-excel-workshop

A GitHub Pages facilitator site for **Leaders Tribe's "Excel for Data Analysis for Women"** training — an 8-week, two-level (Beginner + Intermediate) Excel workshop built for facilitators teaching African women in NGOs, cooperatives, savings groups, and small businesses.

This repository contains entirely original Excel-focused content and datasets.

## What this site is for

This is a **facilitator tool**, not a marketing or organisational website. Every page exists to help someone stand in front of a room and run a practical Excel workshop, session by session.

## Site structure

```
leaderstribe-excel-workshop/
├── index.md                    # Homepage
├── setup.md                    # Workshop setup guide
├── schedule.md                 # Full 8-week schedule
├── facilitator-guide.md        # All-in-one facilitator guide (entire curriculum, one page)
├── rubrics.md                  # Assessment rubrics (Level 1 & 2 capstones)
├── facilitator-tips.md         # Classroom management & facilitation tips
├── common-errors.md            # Common learner errors and fixes (consolidated)
├── workbook-structure.md        # How to build the downloadable practice workbook
├── level1/
│   ├── overview.md
│   └── session-01.md ... session-08.md
├── level2/
│   ├── overview.md
│   └── session-01.md ... session-08.md
├── capstone/
│   ├── level1-capstone.md      # "Everyday Data Story"
│   └── level2-capstone.md      # "Community Data in Action"
├── datasets/                   # Practice CSV datasets (African community context)
├── _config.yml                 # GitHub Pages / Jekyll configuration
└── README.md
```

## Curriculum overview

**Level 1 — Beginner (8 sessions):** Excel interface & navigation, data entry & formatting, sorting & filtering, basic data cleaning, Excel Tables, basic formulas & functions, IF statements & simple charts, conditional formatting & basic reports. Capstone: **Everyday Data Story**.

**Level 2 — Intermediate (8 sessions):** Remove Duplicates & Text-to-Columns, Flash Fill & Data Validation/dropdowns, VLOOKUP & XLOOKUP, INDEX-MATCH, COUNTIF/SUMIF/AVERAGEIF/IFS/IFERROR, PivotTables, PivotCharts & Slicers, Dashboards. Capstone: **Community Data in Action**.

Every session page follows the same 14-part facilitator template: learning goal, duration, preparation, materials, sample dataset, live demo steps, guided activity, independent practice, expected output, common mistakes & fixes, reflection questions, assignment, and facilitator notes.

## Datasets

All practice datasets in `/datasets` use realistic African community and small-business contexts: market trading (Onitsha, Kano, Kejetia), women's savings groups (ajo/esusu-style), women-owned cooperatives (Nairobi, Mombasa), NGO beneficiary registers, microloan repayment tracking, and community health records. Level 2 datasets are intentionally messier (duplicates, inconsistent formatting) to match real intermediate-skill scenarios.

## Running this site locally

```bash
gem install bundler jekyll
bundle exec jekyll serve
```
Then visit `http://localhost:4000`.

## Publishing to GitHub Pages

1. Push this repository to GitHub under the name `leaderstribe-excel-workshop`.
2. In the repo settings, go to **Pages** and set the source to the `main` branch, root folder.
3. GitHub will publish the site at `https://<your-username>.github.io/leaderstribe-excel-workshop/`.

## License / usage

Built for Leaders Tribe facilitator use. Adapt freely for your own workshop cohorts — please keep the practical, facilitator-first spirit of the material intact.
