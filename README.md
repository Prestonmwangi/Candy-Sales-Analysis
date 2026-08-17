# Candy Sales Analysis – Power BI Dashboard
## Table of Contents
- Business Problem
- Project Objectives
- Project Overview
- Dashboard Pages
    - Executive Sales & Margin Performance
    - Logistics & Supply Chain Operations
- Key Business Insights
- Data Model & DAX
- Repository Structure
- How to Use
- Tools

## Business Problem

The business requires a clear view of sales performance, profitability, product performance, and operations to identify key performance drivers and areas for improvement.

## Project Objectives
* Measure sales and profitability performance.
* Identify top-performing products and locations.
* Analyze order volume, costs, and average order value.
* Track sales and profit trends over time.
* Provide an interactive dashboard for data-driven decision-making.

## Project Overview

An interactive Power BI dashboard that provides a clear view of sales performance, profitability, and supply chain operations, transforming transactional data into actionable financial, operational, and geographic insights.

## Dashboard Pages
### Executive Sales & Margin Performance

The page provides a high-level overview of the business's financial performance and profitability, enabling stakeholders to evaluate revenue generation, gross profit, profit margins, and sales performance across products and periods. It highlights the overall financial position of the business while making it easier to identify strong-performing product categories and sales trends.

![Executive Sales & Margin Performance](https://github.com/Prestonmwangi/Candy-Sales-Analysis/blob/main/Images/Executive%20Sales%20%26%20Margin%20Performance.png)
*Executive overview showing revenue, gross profit, profit margin, product performance, and sales trends.*

### Logistics & Supply Chain Operations

The page focuses on order activity and operational performance, providing insights into order volumes, total costs, average order value, and overall sales activity. It helps evaluate how efficiently orders are being generated and how costs relate to the volume and value of sales.

![Logistics Efficiency & Supply Chain Operations](https://github.com/Prestonmwangi/Candy-Sales-Analysis/blob/main/Images/Logistics%20Efficiency%20%26%20Supply%20Chain%20Operations.png)
*Operational overview showing order volume, costs, average order value, and overall sales activity.*

## Key Business Insights

* Strong overall profitability: $141.78K in revenue generated $93.44K in gross profit, resulting in a 65.91% gross profit margin.
* Product performance is uneven: Sales and profitability vary across products, highlighting opportunities to prioritize high-performing products and investigate weaker performers.
* Cost structure supports strong margins: $48.34K in total costs represents a relatively small proportion of revenue, supporting the business's strong overall gross margin.
* Revenue concentration across products highlights potential dependency risks, where a small group of high-performing products particularly **chocolate** can account for a disproportionate share of sales.
* Standard Class dominates shipping activity, indicating a strong reliance on the most commonly used delivery method.

## Data Model & DAX

The analysis was built using a star schema, with the sales data supported by related dimensions for products, dates, and other business attributes.

Key DAX measures include **Total Revenue, Total Cost, Gross Profit, Gross Profit Margin %, Total Orders, Average Order Value, and Total Units Sold.**

These measures provide the foundation for evaluating the business's financial performance, profitability, and order activity throughout the dashboard.

## Repository Structure
```text
Candy-Sales-Analysis/
├── Data/
├── Images/
├── Maven Toys Sales Analysis.pbix
└── README.md
```

## How to Use

Open the .pbix file in Power BI Desktop, then use the available filters and dashboard navigation to explore the analysis.

Selecting chart elements also enables cross-filtering across visuals, allowing users to investigate specific products, periods, and performance trends.

## Tools

**SQL · Power BI · DAX · Power Query · Data Modeling · Data Visualization**
