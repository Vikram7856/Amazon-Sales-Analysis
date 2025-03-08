# Amazon Sales Analysis

## 📌 OBJECTIVE:
To understand the sales performance of different items and identify sales trends based on:
- Yearly sales
- Quarterly sales
- Monthly sales
- Yearly-month wise trends

## 📝 PROBLEM STATEMENT  
Sales management has become crucial to address increasing competition and optimize distribution methods to reduce costs and maximize profits. In today's commercial and business enterprises, sales management plays a vital role. The task involves performing **ETL (Extract-Transform-Load)** on an Amazon dataset to analyze sales trends **month-wise, year-wise, and yearly-month wise**. The key deliverables include identifying key sales metrics and influencing factors, establishing meaningful relationships between attributes, and providing data-driven insights to optimize sales strategies.


# 📊 Amazon Sales Dataset Description

## 📂 Dataset Overview  
This dataset contains **65,280** sales records from Amazon, detailing transaction-level data, including product sales, pricing, discounts, and key sales metrics. The data is useful for analyzing sales trends, profitability, and customer purchasing behavior.

## 🏷️ Column Descriptions  

| Column Name                         | Data Type        | Description |
|--------------------------------------|-----------------|-------------|
| **Custkey**                          | `int64`         | Unique customer identifier |
| **DateKey**                          | `object`        | Date of transaction (MM/DD/YYYY) |
| **Discount Amount**                  | `float64`       | Discount applied to the sale |
| **Invoice Date**                      | `datetime64`    | Date of invoice issued |
| **Invoice Number**                    | `int64`         | Unique invoice ID |
| **Item Class**                        | `object`        | Category of the item |
| **Item Number**                       | `object`        | Unique item identifier |
| **Item**                              | `object`        | Name of the product |
| **Line Number**                       | `int64`         | Order line number within invoice |
| **List Price**                        | `float64`       | Original listed price of the item |
| **Order Number**                      | `int64`         | Unique order ID |
| **Promised Delivery Date**            | `object`        | Expected delivery date |
| **Sales Amount**                      | `float64`       | Total amount generated from sales |
| **Sales Amount Based on List Price**  | `float64`       | Sales revenue assuming no discount |
| **Sales Cost Amount**                 | `float64`       | Cost incurred for the sale |
| **Sales Margin Amount**               | `float64`       | Profit margin from sales |
| **Sales Price**                       | `float64`       | Actual selling price after discounts |
| **Sales Quantity**                    | `int64`         | Number of units sold |
| **Sales Rep**                         | `int64`         | ID of the sales representative |
| **U/M**                               | `object`        | Unit of measurement (e.g., EA for each) |





---

🚀 **Let's dive into the analysis and extract meaningful business insights!**

