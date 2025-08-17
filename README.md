# 📊 Tableau Sales Project

## Overview  
This project demonstrates a **complete sales analysis workflow** using structured CSV datasets and interactive dashboards built in **Tableau**.  
It showcases how to connect raw data (customers, products, orders, and locations) into meaningful insights for business decision-making.  

## 📁 Project Structure  
- **Customers.csv** — 793 rows. Contains customer information (`Customer ID`, `Customer Name`).  
- **Location.csv** — 632 rows. Geographic data (`Postal Code`, `City`, `State`, `Region`, `Country/Region`).  
- **Orders.csv** — 9,994 rows. Transaction data (`Order ID`, `Order Date`, `Ship Date`, `Customer ID`, `Product ID`, `Sales`, `Quantity`, `Discount`, `Profit`).  
- **Products.csv** — 1,894 rows. Product catalog (`Product ID`, `Category`, `Sub-Category`, `Product Name`).  
- **tableau-sales-project.pdf** — Dashboard layout (exported from Tableau).  

## 🔑 Key Features  
- **Sales Dashboard**  
  - Overview of revenue, profit, and order quantity (Year-over-Year).  
  - Monthly and weekly sales trends.  
  - Product subcategory performance comparison.  
  - Top and bottom months highlighted automatically.  

- **Customer Dashboard**  
  - Customer segmentation and behavior analysis.  
  - Number of orders per customer distribution.  
  - Top 10 customers by profit with additional KPIs (rank, orders, last order date).  
  - Monthly customer and sales activity trends.  

- **Interactivity & Filters**  
  - Year selection to explore historical data.  
  - Drill-down filters by region, product, and customer.  
  - Interactive navigation between dashboards.  

## 📊 Example KPIs  
- **Total Sales** = `SUM(Sales)`  
- **Profit Margin** = `SUM(Profit) / SUM(Sales)`  
- **Average Order Value (AOV)** = `SUM(Sales) / COUNTD(Order ID)`  
- **Customer Lifetime Value (CLV)** (proxy) = `Total Sales / Number of Customers`  

## 📈 Insights & Findings  
Based on the dashboards and data exploration, the following business insights were identified:  
1. **Seasonal Trends** — Sales peak during Q4, with December showing the highest order volume and profit, suggesting strong holiday-driven demand.  
2. **Profitability by Sub-Category** — Technology products deliver the highest profit margins, while Furniture often shows lower profitability due to higher discounting.  
3. **Regional Performance** — The West region generates the most revenue, but the East region shows stronger growth potential year-over-year.  
4. **Customer Segmentation** — A small group of top customers contributes disproportionately to total profit, highlighting opportunities for loyalty and retention programs.  
5. **Order Behavior** — Most customers place fewer than five orders, but high-value customers tend to purchase across multiple categories, increasing their lifetime value.  

## 🛠 Tech Stack  
- **Tableau Desktop / Tableau Public** — dashboard creation.  
- **CSV (UTF-8, cp1251, latin1)** — data storage and integration.  
- **Python & OCR** (optional) — used to extract and document dashboard specifications from the original PDF.  

## 🎯 Project Goal  
The main objective is to **demonstrate business intelligence (BI) skills**:  
- Preparing and cleaning data,  
- Designing interactive dashboards,  
- Building KPIs for sales and customer analytics,  
- Presenting insights for business stakeholders.  
