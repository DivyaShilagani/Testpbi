This Power BI dashboard project analyzes sales and performance data of various men's clothing brands. Built using Azure SQL Database and Power BI, the dashboard provides actionable insights into brand-level metrics such as discount percentages, profit margins, product variety, and sales trends. The goal is to help retail analysts and decision-makers identify top-performing brands and areas for improvement.

Objectives are:

- Data Integration: Connect Power BI to Azure SQL Database using both Database and Microsoft Account authentication methods.
- Data Cleaning: Perform SQL-based transformations and Power Query operations to ensure data consistency and accuracy.
- Data Modeling: Establish relationships between fact and dimension tables for efficient analysis.
- DAX Calculations: Create calculated columns for Discount %, Profit %, and Cost Price to derive deeper insights.
- Visual Analytics: Build interactive visuals including bar charts, donut charts, ribbon charts, area charts, and circle graphs.
- Brand Performance Analysis: Highlight top 5 brands by average discount %, profit %, and sales price; identify bottom 5 brands by profit %.
- Custom Visuals: Integrate visuals from Power BI AppSource to enhance report aesthetics and usability.

📊 Project Overview

- Data Source: Azure SQL Database containing brand-level retail data.
- Data Preparation:
  - Loaded raw data into Azure SQL.
  - Cleaned and transformed data using SQL queries and Power Query Editor.
- Modeling:
  - Designed a star schema linking brand, product, and sales tables.
  - Created calculated columns using DAX for key metrics.
- Visualizations:
  - Bar Chart: Top 5 brands by highest average discount % (up to 35%).
  - Donut Chart: Top 5 brands by variety count.
  - Ribbon Chart: Top 5 brands by average sales price.
  - Area Chart: Top 5 brands by highest average profit % (up to 42%).
  - Circle Graph: Bottom 5 brands by profit % (below 10%).
- Interactivity:
  - Filters and slicers for brand, category, and time period.
  - Page navigation and drill-through features for detailed brand views.
