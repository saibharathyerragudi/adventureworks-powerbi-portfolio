# Technical Summary

## Report Metadata

- File: `reports/AdventureWorks_Report.pbix`
- Report canvas: 1280 x 720 on primary report pages
- Report pages: 6
- Main pages: Executive Dashboard, Map, Product Detail, Customer Detail
- Supporting page: Category Tooltip
- Power BI features: slicers, drillthrough, tooltip page, bookmarks, buttons, maps, KPI cards, gauges, line/area charts, donut charts, tables, and dynamic metric selectors

## Visual Inventory

| Page | Visuals Identified |
|---|---|
| EXEC Dashboard | Buttons, text, matrix/pivot table, shapes, KPI visuals, cards, slicers, line chart, image, clustered bar chart |
| Map | Map, slicer, navigation buttons, shapes |
| Product Detail | Drillthrough page, gauges, line chart, area chart, cards, slicers, navigation buttons |
| Customer Detail | Donut charts, cards, table, slicers, line chart, navigation buttons |
| Category Tooltip | Multi-row card and area chart |

## Model Tables

The report uses lookup and helper tables that support a dimensional analytics model:

| Table | Role |
|---|---|
| Calendar Lookup | Date filtering and trend analysis |
| Customer Lookup | Customer attributes and customer-level analysis |
| Product Lookup | Product-level reporting and drillthrough |
| Product Categories Lookup | Category-level product grouping |
| Product Subcategories Lookup | Subcategory-level product grouping |
| Territory Lookup | Geographic filtering and map analysis |
| Measure Table | Centralized business measures |
| Customer Metric Selection | Disconnected selector for customer metric switching |
| Product Metric Selection | Disconnected selector for product metric switching |
| Price Adjustment(%) | What-if or adjustment control for profitability analysis |

## Business Metrics

The model exposes measures and fields for:

- Revenue, profit, adjusted profit, and target gaps
- Orders, previous month orders, and order target gap
- Returns and return rate
- Customer count and average revenue per customer
- Product category, subcategory, and product name analysis
- Territory, country, and continent analysis
- Customer occupation and income-level segmentation

## Reviewer Notes

This project is best reviewed by opening the PBIX in Power BI Desktop and starting on the `EXEC Dashboard` page. The repository documentation is intentionally written to explain the business and technical decisions before the reviewer opens the report.

Because Power BI Desktop is required to render report pages, screenshots should be exported manually from Power BI Desktop and added to an optional `screenshots/` folder for an even stronger GitHub preview.
