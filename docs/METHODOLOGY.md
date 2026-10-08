# Methodology

## Objective

Analyze the supplied India COVID-19 state/UT snapshot and communicate differences in case volume, active cases, discharges, deaths, and ratios.

## Process

1. Inspect the supplied Excel `Data` sheet.
2. Validate row and column structure.
3. Check missing values and duplicate state/UT records.
4. Recalculate Active Ratio, Discharge Ratio, and Death Ratio.
5. Reconcile active, discharged, and death counts with total cases.
6. Rank states using relevant KPIs.
7. Aggregate total cases by zone.
8. Document findings, limitations, and data-quality issues.

## Weighted rates

Overall ratios use `SUM(component) / SUM(Total Cases) × 100`, not an average of state-level percentages.

## Interpretation

The analysis is descriptive. It does not establish causality, forecast future outcomes, or represent current COVID-19 conditions.
