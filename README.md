# Retail-Sales-Analysis
## Project Overview
This project involved analyzing a retail sales dataset from 2009–2010 with over 500K transactions. The analysis aimed to uncover key sales patterns, identify top products and customers, understand return behavior, and provide strategic recommendations. An interactive Excel dashboard was created to visualize KPIs with slicers and charts.
## Data Cleaning and Preparation
Duplicates were identified and removed using Excel's Remove Duplicates feature and COUNTIF function. Records were filtered to ensure unique InvoiceNo + StockCode + CustomerID combinations.
## Handling Cancellations
Invoices starting with 'C' were flagged as cancelled using LEFT and IF functions. The total value of cancelled transactions was calculated using SUMIFS and amounted to ₹6,29,435.08.
## Sales Performance
Top products by quantity included 'White Hanging Heart' (58,692 units) and 'WW2 Gliders'. Top products by revenue included 'Manual' (₹2.6L) and 'Cake Stand' (₹1.7L). Analysis was done using Pivot Tables.
## Pricing Strategy
Average unit prices were computed using AVERAGEIF. Items above the 90th percentile, such as 'Amazon Fee' (₹8,859.91), were identified using PERCENTILE.INC.
## Customer Analysis
Top 10 customers were ranked by total spending using DAX Measure and RANKX function. The highest customer spent ₹11,90,919.98.
## Monthly Sales Trends
Sales trends over time were analyzed using TEXT, MONTH, and YEAR functions. November and December showed peak performance.
## Geographical Insights
The UK recorded the highest number of transactions (~4.79 lakh). A pivot table was used to count transactions by country.
## Product Return Rate
Return rates were calculated as Returned Quantity / Total Ordered Quantity using SUMIFS and ABS.
## Customer Segmentation
Customers were segmented into High, Medium, and Low tiers based on total spend using QUARTILE.INC and IF. Counts: High (1,096), Medium (2,192), Low (1,096).
## Dashboard Summary
The Excel dashboard includes KPIs such as Total Revenue (₹95,05,775.56), Total Quantity Sold (5,992,601), Top Products, and Sales by Country. It features interactive slicers and charts for dynamic exploration.
