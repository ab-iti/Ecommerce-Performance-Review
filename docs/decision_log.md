# Decision Log

This document records key decisions made during the development of the E-Commerce Performance Review project, including the reasoning behind them.

## Decision 1: Separate Total Order Value from Realized Revenue

**Decision:** Report total order value and realized revenue as separate metrics.

**Reason:** Not every order represents a completed sale. Orders can be cancelled, pending, returned, or completed, so total order value alone may overstate realized business performance.



## Decision 2: Use Profit Margin as a Performance KPI

**Decision:** Include profit margin alongside revenue and profit.

**Reason:** Revenue indicates sales volume in monetary terms, while profit and margin help assess profitability.



## Decision 3: Analyze Discount Bands

**Decision:** Group orders into discount bands to compare sales and profitability across discount levels.

**Reason:** Discounting can influence order value and profit. Grouping discounts makes patterns easier to compare than reviewing individual discount percentages.



## Decision 4: Include Customer Segment Analysis

**Decision:** Compare revenue and profit across customer segments.

**Reason:** Segment-level reporting helps identify where business value is concentrated and where further investigation may be useful.



## Decision 5: Use Time-Based Filtering

**Decision:** Provide a date Timeline for supported PivotTable reports and use the selected date range for related formula-driven analysis.

**Reason:** Time-based filtering makes it easier to examine performance over different reporting periods.



## Decision 6: Validate Data Before Drawing Conclusions

**Decision:** Perform data-quality and reconciliation checks before treating reported figures as business findings.

**Reason:** Duplicate records, missing values, inconsistent statuses, and mismatched totals can distort reporting.
