# Financial-Sales-Performance-Analysis-Power-BI-


## Project Overview

This project involves a comprehensive data analysis of a global financial dataset using **Power BI**. The goal was to transform raw sales data into an interactive dashboard that provides actionable insights into profitability, product performance, and regional sales trends across various market segments.


##  Tools Used

* **Power BI Desktop**: Data transformation (Power Query), DAX modeling, and Visualization.
* **Power Query**: For data cleaning and preprocessing.
* **Excel/CSV**: Source dataset.

##  Data Preprocessing & Cleaning

To ensure data quality and accuracy, the following steps were performed in Power Query:

1. **Header Cleaning**: Trimmed leading and trailing spaces from column names.
2. **Type Conversion**: Converted currency columns (Sales, Profit, COGS) from text to **Decimal Number/Currency** format.
3. **Handling Negatives**: Accounted for negative profit values (represented by parentheses in the raw data).
4. **Date Standardization**: Converted the date column to a standard Date format to enable time-intelligence analysis.
5. **Calculated Columns/DAX**: Created measures for *Total Sales*, *Total Profit*, and *Profit Margin* to enhance reporting.

##  Key Visualizations

The dashboard includes 7+ visuals designed to convey deep insights:

* **KPI Cards**: High-level overview of Total Sales, Profit, and Units Sold.
* **Sales Trend (Line Chart)**: Monthly performance tracking across 2013-2014.
* **Product Performance (Bar Chart)**: Ranking products by revenue (e.g., Paseo as the lead product).
* **Geographic Profitability (Map/Bar Chart)**: Identifying France and Germany as key profit drivers.
* **Segment Analysis (Donut Chart)**: Distribution of sales by customer segment (Government, Midmarket, etc.).
* **Gross Sales vs. COGS (Clustered Column)**: Comparison of revenue vs. production costs per segment.
* **Discount Impact (Scatter Plot)**: Correlation between discount bands and units sold.
