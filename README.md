# AdventureWorks Sales Analytics Dashboard

![AdventureWorks logo](assets/adventureworks-logo.png)

An interactive Power BI report built for executive sales performance analysis, customer segmentation, product performance review, and regional sales exploration using the AdventureWorks business dataset.

This project is packaged as a portfolio case study: the PBIX report is included, and the documentation explains the business problem, dashboard design, data model, report pages, and analytical choices behind the build.

## Business Objective

AdventureWorks needs a single analytics experience for leaders to monitor sales performance, understand revenue and profit movement, identify product and customer patterns, and drill into operational details without switching reports.

The dashboard answers:

- How are revenue, profit, orders, returns, and customer counts performing against business targets?
- Which product categories, subcategories, and individual products are driving performance?
- Where are sales concentrated geographically?
- Which customer segments contribute the most value?
- How do monthly trends and target gaps change over time?

## Report File

Open the Power BI file here:

```text
reports/AdventureWorks_Report.pbix
```

Power BI Desktop is required to view, edit, or publish the report.

## Portfolio Highlights

- Executive KPI dashboard with revenue, profit, order, return, and customer performance.
- Drillthrough product detail page for focused product-level analysis.
- Customer detail page with segmentation and customer-level metrics.
- Geographic map page for territory and country-level exploration.
- Dynamic metric selector tables for product and customer analysis.
- Target-gap measures for revenue, profit, and order performance.
- Navigation buttons, bookmarks, custom icons, report tooltip page, and branded AdventureWorks styling.

## Report Pages

| Page | Purpose |
|---|---|
| EXEC Dashboard | Executive landing page for sales KPIs, trend monitoring, targets, slicers, and summary visuals. |
| Map | Geographic view for exploring sales performance by territory, country, and continent. |
| Product Detail | Drillthrough page for product-level trends, return behavior, and profitability context. |
| Customer Detail | Customer analytics page for segmentation, customer value, and selected customer performance. |
| Category Tooltip | Custom tooltip page used to add context to category-level interactions. |
| New Card Demo | Demonstrates Power BI's newer card visual layout. |

## Data Model

The report uses a clean dimensional model with lookup tables for calendar, customers, products, categories, subcategories, and territories. It also includes disconnected metric-selection and price-adjustment tables for interactive analysis.

Key tables identified in the report:

- `Calendar Lookup`
- `Customer Lookup`
- `Product Lookup`
- `Product Categories Lookup`
- `Product Subcategories Lookup`
- `Territory Lookup`
- `Measure Table`
- `Customer Metric Selection`
- `Product Metric Selection`
- `Price Adjustment(%)`

## Key Measures And Fields

The report includes business measures such as:

- `Total Revenue`
- `Total Profit`
- `Total Orders`
- `Total Returns`
- `Return Rate`
- `Total Customers`
- `Average Revenue Per Customer`
- `Revenue Target Gap`
- `Profit Target Gap`
- `Order Target Gap`
- `Previous Month Revenue`
- `Previous Month Orders`
- `Previous Month Returns`
- `Adjusted Profit`

## Skills Demonstrated

- Power BI dashboard design and UX flow
- Star-schema data modeling
- DAX measure development
- KPI and target-gap reporting
- Drillthrough and tooltip design
- Bookmark and button navigation
- Slicer-driven exploratory analysis
- Executive storytelling with operational detail paths

## Repository Structure

```text
adventureworks-powerbi-portfolio/
├── README.md
├── reports/
│   └── AdventureWorks_Report.pbix
├── assets/
│   └── adventureworks-logo.png
└── docs/
    ├── dashboard-storyboard.md
    └── technical-summary.md
```

## How To Use

1. Clone or download this repository.
2. Open `reports/AdventureWorks_Report.pbix` in Power BI Desktop.
3. Review the EXEC Dashboard first for the executive summary.
4. Use navigation buttons, slicers, drillthrough, and tooltip interactions to explore product, customer, and territory performance.

## Project Status

Completed:

- PBIX report packaged for GitHub.
- Portfolio README added.
- Dashboard pages and report architecture documented.
- Technical summary added for recruiter and reviewer context.

Recommended future enhancement:

- Add exported PNG screenshots of each report page to the repository after opening the report in Power BI Desktop.
