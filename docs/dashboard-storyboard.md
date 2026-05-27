# Dashboard Storyboard

## Executive Summary

The report is designed as an executive sales command center for AdventureWorks. The first page gives a high-level view of revenue, profit, order volume, return behavior, and customer performance, while the supporting pages let users move from summary KPIs into geographic, product, and customer detail.

## User Flow

1. Start on the `EXEC Dashboard` to understand overall business performance.
2. Use slicers to narrow the view by date, product, geography, or customer segment.
3. Move to `Map` to compare regional and country-level performance.
4. Drill into `Product Detail` to diagnose product-specific trends and return behavior.
5. Review `Customer Detail` to understand customer segments, occupations, income levels, and individual customer contribution.
6. Use tooltip and card demo pages as supporting report interactions.

## Page-Level Design

### EXEC Dashboard

Purpose: give leadership a fast read on performance.

Core design choices:

- KPI cards summarize revenue, profit, orders, returns, and customer performance.
- Trend visuals show movement over time.
- Target-gap measures translate raw performance into business accountability.
- Slicers make the page usable for both executive summary and quick ad hoc filtering.
- Buttons and custom icons create a polished app-like navigation experience.

### Map

Purpose: reveal where performance is coming from.

Core design choices:

- Map visual supports territory and country-level exploration.
- Slicer and navigation buttons keep the page connected to the rest of the report.
- Geographic analysis helps identify regional concentration and expansion opportunities.

### Product Detail

Purpose: support product-level performance diagnosis.

Core design choices:

- Drillthrough behavior lets users move from a product in another page into dedicated product analysis.
- Gauge and trend visuals compare product performance against targets.
- Product metric selectors support flexible analysis without creating multiple duplicate pages.

### Customer Detail

Purpose: explain who drives revenue and customer value.

Core design choices:

- Customer KPIs and trend visuals summarize selected customer behavior.
- Segmentation fields such as occupation and income level support audience analysis.
- Detail table gives the analyst a way to move from aggregate trends to specific records.

### Category Tooltip

Purpose: add contextual details while keeping the main pages uncluttered.

Core design choices:

- Compact tooltip layout supports hover-level analysis.
- Multi-row card and area chart provide fast context without leaving the current page.

## Business Value

This report helps a business user move from "what happened?" to "where should I investigate?" It combines executive KPIs, self-service filtering, drillthrough paths, and operational detail in one cohesive report experience.
