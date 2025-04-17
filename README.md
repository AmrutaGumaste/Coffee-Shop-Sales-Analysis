# Coffee-Shop-Sales-Analysis

📝 Overview
This project provides a Power BI dashboard and a PowerPoint summary analyzing revenue performance for a fictional coffee shop chain. It is designed to help stakeholders quickly understand sales trends, marketing impacts, and operational insights.

📁 Files Included

File Name	Description
Coffee_Sales.pbix	Power BI report containing all visuals and DAX measures
Coffee_Sales_Dashboard_Summary.pptx	Executive PowerPoint summary presentation
coffee_shop_revenue.csv	Source dataset used in the dashboard (if included)
📊 Key Features in Power BI Report
KPIs: Total Sales, Customers, Average Order Value, Revenue per Employee

Revenue Over Time: Daily revenue trends across the reporting period

Marketing Impact: Analysis of revenue vs marketing spend category

Operational Metrics: Revenue per hour, per employee, foot traffic insights

Customer Behavior: Impact of customer count and foot traffic on sales

🔧 DAX Measures Used
Total Sales = SUM('coffee_shop_dashboard_data'[Daily_Revenue])

Transaction Count = COUNTROWS('coffee_shop_dashboard_data')

Distinct Category Count = DISTINCTCOUNT('coffee_shop_dashboard_data'[Marketing_Spend_Category])

Custom calculated measures for filtered analysis also included.

🖼️ How to Use
Open Power BI File (Coffee_Sales.pbix)

Navigate through report pages for interactive visuals

Use slicers (e.g., date, category, location) to filter data dynamically

For presentation or offline use, refer to the .pptx summary file

🗂️ Suggested Enhancements
Add location-based segmentation

Enable time-based filters (monthly, quarterly)

Embed predictive analytics for future revenue forecasting

