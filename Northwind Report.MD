# Northwind Traders Global Sales & Operations BI

![My Image](https://github.com/R887645/Northwind-Traders-Global-Sales-Operations-BI-Analysis/blob/main/Northwind_traders%20Analysis%20(6).png?raw=true)

![My Image](https://github.com/R887645/Northwind-Traders-Global-Sales-Operations-BI-Analysis/blob/main/Northwind_report.png?raw=true)

## Project Overview  
This project builds an interactive business intelligence solution using the Northwind dataset. The dashboard provides executives with clear insights into global sales performance, product and category intelligence, regional market share, shipping efficiency, and salesforce productivity.

## Business Problem  
Northwind Traders needed a reliable BI solution to replace fragmented reporting and give executives a unified view of sales, products, shipping, and employee performance. Existing reports lacked consistency and did not support strategic decision‑making.

## My Thinking Process  
I approached the project step‑by‑step:  
- Profiled the dataset to understand tables and relationships.  
- Cleaned and transformed data for integrity and readability.  
- Designed a star schema for efficient analytics.  
- Built DAX measures to calculate KPIs.  
- Wireframed and developed a multi‑page Power BI dashboard.  
- Validated insights against business questions and recommended actions.

## Dataset & Schema  
- **Tables:** Orders, Order Details, Customers, Products, Categories, Employees, Shippers.  
- **Schema:** Star schema with `Fact_Orders` at the center linked to Customers, Employees, Shippers, Products, and Categories.  
- **Calendar Table:** Created for time intelligence and accurate YoY analysis.

## Data Cleaning & Transformation  
- Corrected data types (IDs, discounts).  
- Handled null values logically (e.g., unshipped orders excluded from shipping KPIs).  
- Created a unified fact table by merging Orders and Order Details.  
- Added derived fields like Product Status for better readability.

![My Image](https://github.com/R887645/Northwind-Traders-Global-Sales-Operations-BI-Analysis/blob/main/northwind_datacleaning.png?raw=true)

## Data Modelling  
- Star schema with cross‑filtering between Categories, Products, and Orders.  
- Calendar table linked to Fact_Orders for time‑based analysis.  
- Relationships optimized for flexible drilldowns.

![My Image](https://github.com/R887645/Northwind-Traders-Global-Sales-Operations-BI-Analysis/blob/main/Northwind_Data%20modeling.png?raw=true)


## DAX Measures  
- **Revenue KPIs:** Total Revenue, YoY Growth, Variance.  
- **Operational KPIs:** Average Order Value, Freight Costs, Fulfilment Rate.  
- **Customer KPIs:** Top Customers, Concentration Risk.  
- **Product KPIs:** Category Revenue, Discount Impact, Active vs Discontinued Products.

## Dashboard Pages & Business Questions Answered  
1. **Sales & Revenue Overview**  
   - Trends in revenue and order volume.  
   - Seasonal patterns.  
   - Top customers and YoY growth.  

![My Image](https://github.com/R887645/Northwind-Traders-Global-Sales-Operations-BI-Analysis/blob/main/Northwind_Homepage%20(1).png?raw=true)

2. **Product & Category Intelligence**  
   - Top revenue‑driving categories.  
   - Impact of discontinued products.  
   - Discount effects on margins.  
   - Underperforming vs high‑performing products. 

![My Image](https://github.com/R887645/Northwind-Traders-Global-Sales-Operations-BI-Analysis/blob/main/Northwind_Product%20andCatgory.png?raw=true)

3. **Regional, Operational & People Performance**  
   - Market share by country.  
   - Freight cost analysis.  
   - Shipper comparison (cost vs speed).  
   - Employee sales performance.  
   - Order fulfilment rate.  

![My Image](https://github.com/R887645/Northwind-Traders-Global-Sales-Operations-BI-Analysis/blob/main/Screenshot%202026-04-30%20104419.png?raw=true)

## Key Insights  
- Revenue reached **$1.27M** with **53.4% YoY growth**.  
- Seasonal dip in May–June requires targeted campaigns.  
- Top 3 customers contribute **$319K**, creating dependency risk.  
- Beverages and Dairy lead revenue; discounts don’t always drive sales.  
- Fulfilment rate strong at **97%**, but United Package is costliest and slowest.  

## Recommendations  
- Launch mid‑year promotions to address seasonal slowdown.  
- Reduce dependency on the top 3 customers by developing fast‑growing accounts.  
- Replace discontinued Meat & Poultry products to retain category demand.  
- Cap discounts at 10% for underperforming categories; reserve higher discounts for Beverages/Dairy.  
- Make Federal Shipping the default carrier to save ~$29K annually.  

## Data Limitations  
- Dataset covers partial years (2013–2015).  
- 2014 is the only complete calendar year.  
- YoY growth figures should be interpreted with caution due to incomplete periods.

## Tools Used  
- **Power BI** for modelling, DAX, and dashboard design.  
- **Power Query** for data cleaning and transformation.  
- **Excel/CSV** for staging and initial profiling.  

About Me
I am Abdul‑Azeez Rofiah Kehinde, an E‑commerce Data Analyst specializing in sales, customer behavior, and marketing analytics. 
I help businesses transform raw transactional data into actionable insights that drive revenue growth, customer retention, and strategic decision‑making. 
My expertise lies in using tools such as Excel, Power Query, SQL, and Power BI to clean, model, and visualize data, delivering dashboards that tell a clear business story and empower stakeholders to act with confidence. 
Let's connect

