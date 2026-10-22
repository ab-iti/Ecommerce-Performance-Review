# E-Commerce Sales Analytics & Reporting

## Project Overview

This project explores e-commerce sales performance through an Excel-based analytics and reporting solution. It focuses on revenue realization, profitability, discounting, customer segments, order completion, returns, and delivery performance.

The objective is to transform raw sales data into structured analysis and management-friendly reporting that supports business decisions.

## Business Problem

Total order value does not necessarily represent realized revenue. Orders may be cancelled, remain pending, or be returned. Looking at order value alone can therefore give an incomplete picture of business performance.

This project separates order value from realized revenue and examines how discounts, customer segments, and delivery outcomes relate to sales and profitability.

## Key Questions

- How do order value and realized revenue differ?
- How much revenue and profit are associated with different discount bands?
- How does sales performance vary over time?
- Which customer segments contribute to revenue and profit?
- How do delivery outcomes relate to completed orders and customer ratings?
- What data-quality checks are needed before reporting results?

## Tools & Techniques

- **Microsoft Excel:** structured datasets, formulas, KPI calculations, and reporting.
- **PivotTables and PivotCharts:** interactive summaries and visual analysis.
- **Excel Timeline and slicers:** interactive filtering of supported PivotTable reports.
- **Power Query:** data preparation and transformation, where implemented in the workbook.
- **Analytical validation:** reconciliation checks, duplicate checks, and comparisons between order value and realized revenue.

## Project Scope

The simulated cross-border retailer dataset covers multiple years, countries, product categories, and sales channels. Analysis includes revenue, profit, discount bands, customer segments, delivery status, order completion, and returns.

## Preliminary Business Findings

The initial dataset-level checks showed:

- **138,116** orders
- **113,559** completed orders
- **₹127,907,006.57** in realized revenue
- **₹45,998,727.67** in profit
- **35.96%** profit margin
- **₹157,143,214.06** in total order value

The difference between total order value and realized revenue requires interpretation by order status; it should not automatically be treated as cash lost. These are preliminary dataset-level figures and may differ from results under interactive date or other filters.

## Deliverables

- Excel reporting workbook
- Interactive dashboard and supporting analysis

## Repository Structure

```text
ecommerce-sales-analytics/
├── README.md
├── screenshots/
└── data_sample/
```
