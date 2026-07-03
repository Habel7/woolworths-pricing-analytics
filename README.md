# Woolworths FY25 Pricing Analytics - Tableau Dashboard

An interactive Tableau dashboard analysing the pricing and value-perception environment facing Woolworths Group, built from public data sources: the Woolworths Group FY25 Annual Report, ABS retail and CPI statistics, ACCC supermarkets inquiry findings, and published Roy Morgan customer-perception figures.

<!-- Add a dashboard screenshot here after exporting from Tableau:
![Dashboard](dashboard.png) -->

## Key findings

- NSW, VIC, and QLD together drive roughly 70% of national supermarket revenue, making them the priority markets for any pricing strategy deployment.
- Food inflation has unwound from its 2022–23 peak, but the accumulated price gap versus general CPI has structurally shifted customer value expectations — supporting sustained price investment over short-term discounting.
- Category-level inflation drivers vary widely, so price reductions land hardest when targeted at the food sub-categories still carrying the most price sensitivity.
- Competitor perception data (price trust vs. quality) positions the major chains on a quadrant view, quantifying the value-perception gap Woolworths' pricing program needs to close.

## What's in the dashboard

| View | Purpose |
|---|---|
| Hero + KPI tiles | Food inflation, food share of spend, price-trust and competitor benchmarks at a glance |
| Drivers — categories | Which food sub-categories are driving inflation |
| Drivers — states | Geographic distribution of supermarket turnover |
| Competitor / Quadrant | Price-trust vs. perception positioning of major chains |
| Data Sources | Full source list and notes |

## Data preparation

The FY25 Annual Report (200+ pages) was manually extracted and reshaped into flat, Tableau-ready tables covering P&L, segment performance, eCommerce, store network, and sustainability metrics. ABS series were cleaned and joined at the state and category level. All packaged data files are included in the `.twbx`.

## How to open

Download `Woolworths_FY25_Pricing_Analytics.twbx` and open it in Tableau Desktop or the free [Tableau Reader](https://www.tableau.com/products/reader). All data sources are packaged inside the file — no external connections needed.

## Sources

Woolworths Group Annual Report 2025 · ABS Retail Trade & CPI · ACCC Supermarkets Inquiry (2025) · Roy Morgan supermarket customer research (published figures)
