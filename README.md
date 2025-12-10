# Ecommerce Retail Insights Project

## Skills & Tools
![Excel](https://img.shields.io/badge/Excel-4CAF50?style=flat&logo=microsoft-excel&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-00758F?style=flat&logo=mysql&logoColor=white)
![Data Analysis](https://img.shields.io/badge/Data%20Analysis-FF6F61?style=flat)
![Data Cleaning](https://img.shields.io/badge/Data%20Cleaning-4285F4?style=flat)
![Data Visualization](https://img.shields.io/badge/Data%20Visualization-F4B400?style=flat)
![Business Analytics](https://img.shields.io/badge/Business%20Analytics-0F9D58?style=flat)

## Project Overview
This project analyzes transactional data from a UK-based online retailer, **Giftify Online** (fictional name for portfolio), which sells all-occasion gifts. The goal is to extract actionable insights on product performance, customer behavior, sales trends, and regional performance to help management make data-driven decisions on marketing, inventory, and sales strategy.

## Business Context
- **Company:** Giftify Online  
- **Data Period:** 01/12/2010 – 09/12/2011  
- **Customers:** Both wholesalers and individual buyers  
- **Dataset Size:** 541,909 transactions  
- **Industry:** E-commerce / Retail  

### Challenges / Pain Points
1. The company carries hundreds of products, but management doesn’t know which products are top sellers or underperforming, leading to overstocking low-demand items.  
2. They have thousands of customers, but high-value and loyal customers are unidentified, making marketing campaigns untargeted.  
3. Sales fluctuate over time, but monthly and seasonal trends are unclear, leading to missed opportunities for promotions during peak periods.  
4. Orders come from multiple countries, but regional performance is not tracked, limiting insights on potential market expansion.  
5. Some transactions include discounts or returns, but their impact on revenue and profitability is unknown, preventing optimized pricing strategies.  

## Your Role as an Analyst
- Extract, clean, and summarize transactional data leveraging **SQL** for querying and **Excel** for data cleaning and analysis.  
- Analyze product performance, customer behavior, sales trends, and regional revenue.  
- Provide actionable recommendations to management, including:  
  - Focusing on top products and optimizing inventory  
  - Targeting high-value customer segments with marketing campaigns  
  - Identifying peak periods and regions for promotions  
  - Suggesting strategies for pricing or discounts  

## Business Objectives
1. **Product Analysis:** Identify top-selling and underperforming products to optimize inventory and marketing focus.  
2. **Customer Segmentation:** Identify high-value and loyal customers for targeted campaigns.  
3. **Sales Trend Analysis:** Determine monthly and seasonal trends to guide promotions and inventory planning.  
4. **Regional Performance:** Analyze sales by country/region to identify expansion opportunities.  
5. **Discount & Returns Impact:** Assess how discounts and returns affect revenue and profitability to inform pricing strategy.  

## Key Business Questions
1. Which 5–10 products generate the most revenue, and which are underperforming?  
2. Who are the top customers by total spend and purchase frequency?  
3. How does revenue vary month-to-month, and are there seasonal peaks or dips?  
4. Which countries or regions generate the highest revenue, and where is expansion potential?  
5. How do returns and discounts impact overall revenue and profitability?

## Data Dictionary

| Column Name  | Data Type          | Description / Role |
|--------------|------------------|------------------|
| InvoiceNo    | Categorical/String | Unique invoice identifier; invoices starting with 'C' indicate returns. |
| StockCode    | Categorical/String | Unique product identifier; used to track product performance and returns. |
| Description  | Categorical/String | Product description; provides product details. |
| Quantity     | Integer           | Number of units sold; negative values indicate returns, positive values indicate sales. |
| InvoiceDate  | DateTime          | Date and time of the transaction; used for trend, seasonality, and promotion analysis. |
| UnitPrice    | Float / Currency  | Price per unit in GBP; zero values may indicate promotional/free items. |
| CustomerID   | Categorical/String | Unique customer identifier. |
| Country      | Categorical/String | Country of the customer; used for regional analysis. |

