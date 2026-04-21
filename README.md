# READMITTED: How America's Hospitals Are Failing the 30-Day Standard

A data analysis of 11,720 hospital-condition records from the CMS Hospital
Readmissions Reduction Program (HRRP), covering FY2024 (July 2021–June 2024).
Built as a portfolio piece demonstrating healthcare data analysis relevant to
value-based care and CMS compliance.

## What's in this repo

- `readmitted.qmd` — Quarto markdown file containing all R code, analysis, and write-up
- `artometrics.css` — custom HTML theme (same across all Artometrics reports)
- `chart1_states_penalized.png` — share of hospitals penalized by state (top 20)
- `chart2_err_by_condition.png` — average excess readmission ratio by condition
- `chart3_penalty_by_ownership.png` — penalty tier distribution by hospital ownership type

## What the analysis covers

Three charts working through where the U.S. hospital readmission problem is
most concentrated — and what it means for value-based care platforms:

1. Which states have the worst share of penalized hospitals
2. Which conditions are hardest for hospitals to manage (by average ERR)
3. Which ownership types carry the most systemic compliance risk

## Data source

Centers for Medicare & Medicaid Services. *Hospital Readmissions Reduction
Program (HRRP)*. CMS Provider Data Catalog, dataset ID: 9n3s-kdb3.
Retrieved via CMS metastore API. Program year FY2024 (discharge period
July 1, 2021 – June 30, 2024).

https://data.cms.gov/provider-data/dataset/9n3s-kdb3

## Tools

- R / Quarto
- tidyverse · ggplot2 · ggtext · scales · httr · jsonlite

## Disclosure

This analysis is based on publicly available CMS data. AI was used to assist
in code generation, analysis, and writing. All interpretation and editorial
framing is the author's own.