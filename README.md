# BMW Sales Performance Analysis Dashboard (2010-2024)

Built in Microsoft Power BI using DAX and interactive visuals.

## Overview
This dashboard analyzes BMW sales performance from 2010 to 2024 across models, regions, fuel types, transmission types, and sales classifications. Raw sales data is transformed into an interactive Power BI report, with custom DAX measures driving key metrics like total revenue, units sold, average price, and year-over-year growth.

The report is organized into three pages, each answering a different business question.

## Pages

**Executive Summary**
A top-level view for quick decision-making: total revenue, units sold, average price, and YoY growth, alongside overall sales trends and revenue distribution by category.

**Model Performance**
Compares individual models on revenue, units sold, and price using bar, line, and scatter visuals, making it easy to spot which models are driving growth and which are underperforming.

**Market Insights**
Breaks sales down by fuel type, transmission, color, and region, with interactive filters so a viewer can drill into any segment without needing a new report built for them.

## Technical Details
- **Tool:** Microsoft Power BI
- **Data modeling:** Custom DAX measures for revenue, units sold, average price, and YoY growth calculations
- **Visuals used:** Bar charts, line charts, scatter plots, KPI cards, slicers/filters
- **Data range:** 2010-2024

## What This Project Demonstrates
- Structuring a multi-page BI report around distinct business questions rather than dumping all metrics on one screen
- Writing DAX measures for time-based calculations (YoY growth) rather than relying on pre-aggregated data
- Designing for a non-technical end user: filters and drill-downs instead of static charts

## Possible Next Steps
- Add a forecast visual projecting next-period sales based on the historical trend
- Include a comparison against a benchmark (industry average or competitor data) if that data becomes available
