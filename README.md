# Maven Roasters Sales Analysis Dashboard (Excel)

## Overview
This project analyzes transactional sales data from Maven Roasters (Jan–Jun 2023) to identify sales trends, customer purchase behavior, and product performance. The analysis was conducted entirely in Excel and culminates in an interactive dashboard designed for franchise owners and operations managers.

## Business Problem
Franchise owners needed an easy-to-use dashboard to:
- Understand monthly revenue trends
- Identify peak sales days and hours
- Recognize top-performing and underperforming products
- Compare performance across store locations

## Dataset
- Timeframe: January – June 2023
- Granularity: Transaction-level data
- Key fields:
  - Transaction date & time
  - Store location
  - Product category & product type
  - Quantity sold
  - Unit price

## Data Preparation
Key steps taken to prepare the data:
- Added calculated **Revenue** field (Price × Quantity)
- Extracted:
  - Month (text format: Jan, Feb, etc.)
  - Day of Week (text format: Mon, Tue, etc.)
  - Hour of Day from transaction timestamps
- Verified date ranges, missing values, and formatting consistency

## Analysis & Pivot Tables
The following PivotTables were created:
- Monthly revenue trend
- Transactions by day of week
- Transactions by hour of day
- Transactions by product category (descending order)
- Top 15 product types by transaction volume and revenue

## Dashboard Features
- Interactive Excel dashboard using Pivot Charts
- Visualizations include:
  - Line chart: Revenue by month
  - Column charts: Transactions by weekday and hour
  - Bar chart: Transactions by product category
- Store location slicer connected to all visuals
- Clean layout with hidden raw PivotTables and removed gridlines

## Key Insights
- Sales peaked during June across all three locations, suggesting seasonal demand driven by summer holidays and increased foot traffic.
- Location-level purchasing behavior varied:
  - Astoria experienced high transaction volume on weekdays, particularly Monday, Wednesday, Thursday, and Friday.
  - Hell’s Kitchen showed peak demand on Tuesday and Friday, with consistently lower activity on Saturdays.
  - Lower Manhattan sales peaked on Mondays, indicating a strong weekday commuter-driven pattern.
- Peak purchasing hours occurred between 7–10 AM across locations, highlighting the importance of morning operations and staffing.
- The Top 15 products accounted for a substantial share of total transactions and revenue, indicating that sales are concentrated among a relatively small subset of items.
- Product-level analysis is limited to the Top 15 items; further analysis would be required to assess the performance of lower-volume products.

## Recommendations
- Adjust staffing levels to align with peak purchasing hours (7–10 AM) and high-traffic weekdays to improve service efficiency.
- Leverage top-selling products in promotions or bundles during off-peak hours to help smooth demand throughout the day.
- Conduct a deeper product-level analysis (including products outside the Top 15 and cost data) to identify opportunities for menu optimization.
- Use location-level insights to tailor inventory planning and operational decisions by store, as purchasing patterns vary across locations.

## Tools & Skills Demonstrated
- Excel formulas: TEXT, MONTH, WEEKDAY, HOUR
- PivotTables & PivotCharts
- Slicers for interactivity
- Dashboard design and data storytelling
- Basic data quality checks and profiling

## Screenshots
![Dashboard Overview](Screenshot/dashboard_astoria.png)
![Dashboard Overview](Screenshot/dashboard_hellskitchen.png)
![Dashboard Overview](Screenshot/dashboard_lowermanhattan.png)
