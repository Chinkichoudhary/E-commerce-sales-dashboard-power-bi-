# E-commerce-sales-dashboard-power-bi-
This project focuses on building an interactive E-commerce Sales Dashboard using Power BI by integrating data from MS SQL Server.
The dashboard provides Year-to-Date (YTD) performance insights, Year-on-Year (YoY) growth, and detailed analysis across regions, products, shipping types, customer categories, and sales representatives.
The goal is to help business users track sales performance, identify trends, and make data-driven decisions.


🧩 Problem Statement
   A US-based E-commerce company wants to:
       Analyze YTD Sales performance
       Track profitability and growth
       Compare regions, products, and shipping methods
       Identify top & bottom performing areas
       Enable management to make strategic decisions using data

🛠️ Tools & Technologies Used
    Power BI Desktop
    MS SQL Server
    DAX (Data Analysis Expressions)
    Power Query
    GitHub (Version Control)

📂 Dataset Description
   The dataset contains E-commerce transactional data including:
         Order details
         Sales & profit values
         Product categories
         Customer categories
         Shipping types
         Regions & countries
         Sales representatives
         Order dates

🔄 Project Workflow (Step-by-Step)

1️⃣ Problem Understanding
     Defined business requirements and KPIs based on stakeholder needs:
         Sales, Profit, Quantity
         Growth comparison
         Performance by region, product, and staff

2️⃣ Data Import into MS SQL Server
     Imported raw E-commerce dataset into MS SQL Server
     Verified data types and table structure

3️⃣ Connecting Power BI to SQL Server
     Connected Power BI to SQL Server database
     Used Direct Import for analysis

4️⃣ Data Cleaning (Power Query)
     Performed data preparation tasks:
          Removed duplicates
          Handled missing values
          Standardized column names
          Corrected data types
          Filtered invalid records

5️⃣ Data Processing
    Created derived columns
    Prepared date hierarchy
    Structured data for analytics

6️⃣ Data Modeling
    Built relationships between fact and dimension tables
    Applied star schema
    Ensured proper cardinality and filter direction

7️⃣ DAX Measures Creation
    Created important business measures such as:
         YTD Sales
         YTD Profit
         YTD Quantity Sold
         YTD Profit Margin
         PYTD (Previous Year-to-Date) Sales
         YoY Sales Growth %

8️⃣ Data Visualization
    Designed visuals including:
         KPI cards
         Bar charts
         Line charts
         Sparklines
         Maps

9️⃣ Dashboard Creation
     Built a fully interactive dashboard with:
         Filters & slicers
         Drill-down capability
         Dynamic KPI banners

🔟 Insight Generation
      Extracted meaningful insights to answer business questions and highlight performance trends.


📈 Key Dashboard Features

🔹 KPI Banner
      Displays:
            YTD Sales
            YTD Profit
            YTD Quantity Sold
            YTD Profit Margin

🔹 Year-on-Year Analysis
      YoY growth calculated for each KPI
      YTD sparklines to show monthly trends

🔹 Regional Analysis
      YTD Sales by Region
      Identify best & worst performing regions
      Sales performance across countries

🔹 Product Analysis
      Top 5 & Bottom 5 Products by Sales
      Category-wise performance

🔹 Shipping Type Analysis
      YTD Sales by Shipping Type
      Contribution percentage of each shipping method

🔹 Customer Category Analysis
      YTD & PYTD Sales by customer category
      Brand icons added for better visualization

🔹 Sales Representative Performance
      YTD Sales performance by each sales staff
       Comparison across representatives


📊 Business Insights Delivered
         Identified high-performing regions and products
         Detected declining areas using YoY trends
         Compared shipping efficiency
         Evaluated sales team performance
         Supported strategic decision-making

Future Enhancements:
* Implement Power BI forecasting and RLS.
* Publish to Power BI Service with scheduled data refresh.
* Enhance UI with advanced tooltips.


Screenshot /Demos:

show what the dashboard look like:
 Example:[https://github.com/Chinkichoudhary/E-commerce-sales-dashboard-power-bi-/blob/main/dashboard_screenshot.png] ( dashboard preview)
 
