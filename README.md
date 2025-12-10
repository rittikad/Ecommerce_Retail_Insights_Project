# 🏆 Project Name
**E-Commerce Retail Insights Project** (Giftify Online)

---

## 📌 Project Overview  
This project analyzes transactional data from a UK-based online retailer, **Giftify Online** (fictional name for portfolio), which sells all-occasion gift items. The aim is to extract actionable insights on product performance, customer spending behavior, sales trends, and regional performance. These insights will help management make data-driven decisions around marketing, inventory planning, and overall sales strategy.

---

## 🏢 Business Context  
- **Company:** Giftify Online  
- **Data Period:** 01/12/2010 – 09/12/2011  
- **Customers:** Wholesalers & individual buyers  
- **Dataset Size:** 541,909 transactions  
- **Industry:** E-commerce / Retail  

### ⚠️ Challenges / Pain Points  
1. Hundreds of products, but unclear top-sellers vs. slow-movers → leads to overstocking.  
2. Thousands of customers, but high-value / loyal customers are unidentified → campaigns are untargeted.  
3. Sales fluctuate, but monthly and seasonal trends aren't tracked → missed promotion opportunities.  
4. Orders come from multiple countries, but regional performance is unknown → no informed market expansion.  
5. Discounts and returns exist, but their revenue impact is unclear → suboptimal pricing strategy.

---

## 🎯 Your Role as an Analyst  
- Extract, clean, and summarize transactional data using **SQL** and **Excel**.  
- Analyze product performance, customer behavior, sales trends, and regional revenue.  
- Provide actionable recommendations, such as:  
  - Optimizing inventory for high-demand products  
  - Targeting high-value customer segments  
  - Leveraging peak seasonal periods  
  - Highlighting high-performing regions  
  - Understanding pricing and discount impact  

---

## 🧭 Business Objectives  
1. **Product Analysis:** Identify top-selling and underperforming products.  
2. **Customer Segmentation:** Identify high-value and loyal customers for targeted marketing.  
3. **Sales Trend Analysis:** Analyze monthly and seasonal patterns.  
4. **Regional Performance:** Highlight strong markets and expansion opportunities.  
5. **Discount & Returns Impact:** Understand how they affect revenue and profitability.

---

## ❓ Key Business Questions  
1. Which 5–10 products generate the most revenue, and which underperform?  
2. Who are the top customers by total spend and purchase frequency?  
3. How does revenue vary month-to-month, and are there seasonal peaks?  
4. Which countries/regions generate the most revenue and show expansion potential?  
5. How do returns and discounts impact overall revenue and profitability?

---

## 📂 Available Dataset  

The raw dataset contains **541,909 transactional records** from Giftify Online, capturing all product-level sales between **December 2010 and December 2011**. Each row represents a single item purchased within an invoice, allowing for detailed analysis of customer purchases, product performance, and regional trends.

### 📄 File Details  
- **File Name:** `giftify_transactions.csv`  
- **Rows:** 541,909  
- **Columns:** 8  
- **Format:** CSV (comma-separated)  
- **Data Type:** Transaction-level retail data  

### 📊 What the Dataset Covers  
- All product-level transactions  
- Both wholesale and retail customers  
- Orders across multiple countries  
- Timestamped invoice data  
- Pricing and quantity details  
- Return transactions (reflected as negative quantities)  
- Transactions with and without identified customers  
- All product codes and descriptions used by the retailer  

---

## 📘📊 Data Dictionary

| 🏷️ Column Name   | 🔢 Data Type | 📄 Description |
|------------------|--------------|----------------|
| **InvoiceNo**    | String       | A unique identifier for each transaction. If an order contains multiple items, the InvoiceNo repeats across rows. Returns are identified by InvoiceNo starting with "C". |
| **StockCode**    | String       | Unique product code assigned to each item. |
| **Description**  | String       | Textual name/label of the product purchased. |
| **Quantity**     | Integer      | Number of units purchased. Negative values indicate product returns. |
| **InvoiceDate**  | DateTime     | Date and time when the transaction occurred (format: dd-mm-yyyy hh:mm). |
| **UnitPrice**    | Float        | Price (GBP) of a single unit of the product. |
| **CustomerID**   | String       | Unique identifier for each customer. Blank values represent unknown/guest customers. |
| **Country**      | String       | Customer’s country of residence. |
