# Candy Sales Analysis – Power BI Dashboard

## Project Overview

An interactive Power BI dashboard which analyzes sales performance, profitability, and supply chain operations. The report converts the transactional data into business insights covering the financial, operational, and geographic aspects.
## Dashboard Pages

### Executive Sales & Margin Performance

The page gives a general overview of the business's financial performance, enabling stakeholders to evaluate revenue, profitability, target achievement, and the degree of sales concentration by geographic area. It compares revenue with targets for each division, monitors monthly revenue and gross profit margins, and identifies the cities and locations that are performing best.

![Executive Sales & Margin Performance](https://github.com/Prestonmwangi/Candy-Sales-Analysis/blob/main/Images/Executive%20Sales%20%26%20Margin%20Performance.png)
*Executive overview showing revenue, profitability, target performance, monthly trends, and geographic sales performance.*

### Logistics & Supply Chain Operations

The page looks at **operational performance and order activity**, giving information about order volumes, costs, the average order value, and shipping patterns. It compares operational performance between divisions and geographic locations as well as showing how orders are distributed among different shipping modes.

![Logistics Efficiency & Supply Chain Operations](https://github.com/Prestonmwangi/Candy-Sales-Analysis/blob/main/Images/Logistics%20Efficiency%20%26%20Supply%20Chain%20Operations.png)
*Operational overview showing order volume, costs, average order value, shipping modes, and geographic order distribution.*

## Data Model & DAX

It was built on a star schema with the Fact_Sales table supported by dimensions relating to customer, date, product, geography, and factory.

The key measures in respect of the DAX are **Total Revenue, Total Cost, Gross Profit, Gross Profit Margin %, Total Orders, Average Order Value, Total Units Sold, and Total Target**.

Key DAX measures include **Total Revenue, Total Cost, Gross Profit, Gross Profit Margin %, Total Orders, Average Order Value, Total Units Sold, and Total Target**.

## Key Business Insights

* **Chocolate** leads in revenue and order volume.
* Gross margins remain consistently strong across periods.
* **Standard Class** is the dominant shipping method.
* Revenue is concentrated among a small number of high-performing cities.

## How to Use

Open the `.pbix` file in **Power BI Desktop**, then use the Year and Division filters and dashboard navigation to explore the analysis. Selecting chart elements also enables cross-filtering across visuals.

## Tools

**Power BI · DAX · Power Query · Data Modeling · Data Visualization**
