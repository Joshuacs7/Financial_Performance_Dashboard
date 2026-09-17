# Financial Performance Dashboard — Power BI

An interactive financial performance dashboard designed to provide stakeholders with a clear view of profitability and financial performance across time, customer segments, countries, and discount bands.

## Business Objective

The objective of this dashboard is to provide a centralized view of financial performance while allowing users to explore profitability from multiple business perspectives.

The dashboard focuses on four core KPIs:

- Sales
- Profit
- Units Sold
- Profit Margin

## Dashboard Overview

The dashboard combines several complementary views of financial performance within a single interactive page.

### Profit Trend

The main visualization shows monthly performance and allows users to dynamically switch between Profit and Profit Margin.

This provides two perspectives on financial performance while keeping the dashboard focused and easy to navigate.

### Profit by Segment

A horizontal bar chart compares total profit across customer segments:

- Government
- Small Business
- Channel Partners
- Midmarket
- Enterprise

### Profit by Country

A horizontal bar chart compares total profit across the countries represented in the dataset.

### Profit Mix by Discount Band

A donut chart shows the distribution of total profit across the available discount bands:

- Low
- Medium
- High
- None

## Interactivity

The dashboard is designed as a single-page interactive reporting experience.

Users can:

- Filter by Country
- Filter by Segment
- Filter by Discount Band
- Select a date range
- Switch between Profit and Profit Margin
- Cross-highlight data across visuals
- Reset the dashboard to its initial state

## DAX

DAX measures are used to calculate the core financial metrics and support the dynamic metric selection in the main trend visualization.

Key calculations include:

- Total Profit
- Profit Margin
- Dynamic Profit / Profit Margin selection

## Design Approach

The dashboard was designed from a stakeholder perspective, with emphasis on:

- Clear visual hierarchy
- KPI visibility
- Consistent visual language
- Interactive exploration
- Efficient use of dashboard space
- Minimal visual clutter

The layout combines a dedicated filter panel, KPI cards, a primary trend visualization, and supporting comparative visuals within a single-page experience.

## Tools

- Power BI Desktop
- DAX
- Microsoft Excel
- Data Visualization
- Interactive Reporting
- Business Intelligence

## Dataset

The dashboard uses Microsoft's Financial Sample dataset as its underlying data source.

The dataset contains financial and sales-related information including sales, profit, units sold, customer segment, country, discount band, product, and date.

## Project Structure

- README.md
- Financial_Performance_Dashboard.pbix