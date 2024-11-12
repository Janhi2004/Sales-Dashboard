# Sales Dashboard

## Overview
This dashboard provides an interactive, visual overview of key sales metrics, trends, and distribution across different segments and regions. It is designed for executives and analysts to monitor performance, assess growth, and make data-driven decisions. The dashboard features comprehensive metrics for Total Sales, Total Profit, and Total Quantity, with year-over-year comparisons and monthly segment analysis.

---

## Table of Contents
1. [Project Objective](#project-objective)
2. [Data Source](#data-source)
3. [Data Cleaning and Transformation](#data-cleaning-and-transformation)
4. [Dashboard Features](#dashboard-features)
5. [Key Metrics](#key-metrics)

---

## Project Objective
The primary goal of this project is to create a dynamic and informative Tableau dashboard that enables the visualization of sales performance across various states, segments, and time frames. This project helps stakeholders gain insights into sales trends and identify areas for improvement.

---

## Data Source
- **Data Collection**: Data used for this dashboard is sourced from internal sales databases, including transaction records, customer profiles, and sales performance reports.
- **File Format**: The data is provided in `.csv` files, which are cleaned and transformed prior to being loaded into Tableau.
- **Time Period**: The dataset encompasses sales data for the years 2022 and 2021.

---

## Data Cleaning and Transformation
1. **Handling Missing Values**: Removed rows with missing or incomplete sales data to ensure accurate analysis.
2. **Date Standardization**: Converted dates to a uniform format to facilitate time-series analysis.
3. **Categorization**: Classified transactions based on segments (Consumer, Corporate, Home Office) for more granular analysis.
4. **Aggregations**: Calculated aggregate metrics for sales, profit, and quantity at different geographic levels and by product segment.
5. **Geographic Mapping**: Mapped sales data to corresponding states to enable region-based visualization.

---

## Dashboard Features
- **KPI Trend Overview**: Compares 2022 vs. 2021 (CY vs. PY) to show year-over-year changes, including monthly highs and lows.
- **Total Sales, Profit, and Quantity**: Displays key sales metrics with percentage changes from the previous year.
- **Sales and Profit Distribution by State**: Visual representation of sales and profit distribution across U.S. states, with indicators showing states above and below national averages.
- **Monthly Sales by Segments**: Interactive area chart showing monthly sales trends across different segments (Consumer, Corporate, Home Office).
- **Total Sales by Location and Manager**: Breakdown of total sales by geographic location (Canada, United States) and by manager, highlighting performance across regions.
  
---

## Key Metrics
- **Total Sales**: `$745.6K` - indicates a **21.44%** increase compared to the previous year.
- **Total Profit**: `$95.9K` - reflects a **16.04%** increase year-over-year.
- **Total Quantity**: `12,737` units - shows a **27.14%** increase.
- **Monthly Sales by Segments**:
  - **Consumer**: 50.59K
  - **Corporate**: 44.65K
  - **Home Office**: 29.72K
- **Top Managers**: Performance overview of top sales managers across regions, highlighting contributions to total sales.
  
---

This dashboard provides a comprehensive and visual snapshot of sales performance, aiding stakeholders in monitoring progress, identifying patterns, and formulating strategies for growth.
