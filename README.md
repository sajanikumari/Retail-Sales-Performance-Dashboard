# Retail Sales Performance Dashboard

An interactive Power BI dashboard tracking retail sales performance across regions and time, built on a synthetically generated retail transactions dataset.

## Objective
Track revenue, profit margin, and regional/seasonal performance to identify which regions and periods are under- or over-performing.

## Tools
Python (data generation), Excel / Power Query (cleaning), Power BI (DAX)

## About the dataset
The 5,000+ transaction dataset used here is **synthetically generated** (via `retail_data_generator.ipynb`) to simulate realistic retail sales patterns — it is not sourced from a real business. This was a deliberate choice to practice the full pipeline (generation → cleaning → analysis → dashboarding) end-to-end.

## What this project does

### Data Cleaning (Power Query)
- Removed duplicate records and standardized date/category fields
- Created calculated columns for revenue and profit analysis

### Dashboard (Power BI)
- Built an interactive dashboard tracking revenue, profit margin, average order value, regional sales, and monthly growth trends
- DAX measures for total sales, month-over-month growth, top product categories, and regional contribution

## Key takeaway
Identified top-performing regions and seasonal revenue dips in the simulated data, translating findings into example inventory and promotion recommendations.
