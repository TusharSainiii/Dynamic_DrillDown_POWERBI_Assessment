1. Introduc on 
This document explains how to use the Dynamic Drill-down Sales Dashboard created in 
Power BI Desktop. 
The dashboard provides interac ve sales analysis with the ability to: 
 Drill down by me, region, and product category 
 Analyze year-over-year (YoY) sales growth 
 View rolling average sales trends 
 Dynamically filter data using slicers 
2. Data Source 
The dashboard is built using sales data imported from mul ple Excel/CSV files, including: 
 Orders and order details 
 Product and product category informa on 
 Customer and regional (office) data 
These datasets are combined using proper rela onships to form a structured data model in 
Power BI. 
3. Dashboard Overview 
The dashboard consists of the following key visualiza ons: 
 Sales Trend Over Time – Line chart with drill-down capability 
 Sales by Region – Bar chart with regional drill-down 
 Sales by Product Category – Product hierarchy drill-down 
 Year-over-Year Sales Growth – Card 
 Rolling Average Sales Trend – Line chart comparing sales and rolling average 
Addi onally, slicers are provided to filter the data dynamically. 
4. How to Use the Dashboard 
4.1 Using Drill-Down 
Drill-down allows users to explore data at deeper levels. 
Time Drill-Down 
 Click the drill-down (↓) icon on the Sales Trend chart 
 Navigate through: 
 Year → Quarter → Month → Day 
Region Drill-Down 
 Click on a region bar to drill down from: 
 Country → City 
Product Drill-Down 
 Click on a product category to view individual products: 
Product Name → Product Line 
4.2 Using Slicers 
Slicers allow users to filter the en re dashboard. 
Available slicers: 
 Year 
 Product Line 
 Country / Region 
Steps: 
1. Click on any slicer value 
2. All visuals update automa cally 
3. Mul ple slicers can be used together for refined analysis 
5. Key Metrics & DAX Measures 
The dashboard uses custom DAX measures to perform advanced analysis. 
5.1 Total Sales 
Calculates total revenue based on quan ty and unit price. 
5.2 Year-over-Year (YoY) Sales Growth 
Compares current year sales with the previous year to measure growth percentage. 
5.3 Rolling 3-Month Average Sales 
Calculates the average sales over the last three months to iden fy trends and smooth 
f
luctua ons. 
These measures update dynamically based on slicers and drill-down levels. 
6. Interac vity Features 
 All visuals are interconnected 
 Selec ng a data point in one chart filters other charts 
 Drill-down works even a er applying slicers 
 Rolling average and YoY growth respond dynamically to filters 
7. Intended Use 
This dashboard is designed to: 
 Support business decision-making 
 Analyze sales performance over me 
 Iden fy regional and product-level trends 
 Demonstrate Power BI capabili es such as data modeling, DAX, and interac vity 
8. Conclusion 
The Dynamic Drill-down Dashboard provides a comprehensive and interac ve way to analyze 
sales data using Power BI. By leveraging drill-down, slicers, and custom DAX measures, users 
can gain meaningful insights efficiently.
