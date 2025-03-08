# 📊 Amazon Sales Analysis

## 🚀 Project Overview  
This project analyzes Amazon sales data to identify trends, optimize sales strategies, and provide actionable recommendations. Key insights include peak sales periods, top-performing products, and customer behavior, enabling data-driven decision-making to maximize revenue.

---

## 📌 OBJECTIVE:
To understand the sales performance of different items and identify sales trends based on:
- Yearly sales  
- Quarterly sales  
- Monthly sales  
- Yearly-month wise trends  

---

## 📝 PROBLEM STATEMENT  
Sales management has become crucial to address increasing competition and optimize distribution methods to reduce costs and maximize profits. The task involves performing **ETL (Extract-Transform-Load)** on an Amazon dataset to analyze sales trends **month-wise, year-wise, and yearly-month wise**. The key deliverables include identifying key sales metrics, establishing meaningful relationships between attributes, and providing data-driven insights to optimize sales strategies.

---

## 📂 Dataset Overview  
This dataset contains **65,280** sales records from Amazon, detailing transaction-level data, including product sales, pricing, discounts, and key sales metrics. The data is useful for analyzing sales trends, profitability, and customer purchasing behavior.

---

## 🏷️ Column Descriptions  

| Column Name                         | Data Type        | Description |
|--------------------------------------|-----------------|-------------|
| **Custkey**                          | `int64`         | Unique customer identifier |
| **DateKey**                          | `datetime64`    | Date of transaction (MM/DD/YYYY) |
| **Discount Amount**                  | `float64`       | Discount applied to the sale |
| **Invoice Date**                     | `datetime64`    | Date of invoice issued |
| **Invoice Number**                   | `int64`         | Unique invoice ID |
| **Item Class**                       | `object`        | Category of the item |
| **Item Number**                      | `object`        | Unique item identifier |
| **Item**                             | `object`        | Name of the product |
| **Line Number**                      | `int64`         | Order line number within invoice |
| **List Price**                       | `float64`       | Original listed price of the item |
| **Order Number**                     | `int64`         | Unique order ID |
| **Promised Delivery Date**           | `datetime64`    | Expected delivery date |
| **Sales Amount**                     | `float64`       | Total amount generated from sales |
| **Sales Amount Based on List Price** | `float64`       | Sales revenue assuming no discount |
| **Sales Cost Amount**                | `float64`       | Cost incurred for the sale |
| **Sales Margin Amount**              | `float64`       | Profit margin from sales |
| **Sales Price**                      | `float64`       | Actual selling price after discounts |
| **Sales Quantity**                   | `int64`         | Number of units sold |
| **Sales Rep**                        | `int64`         | ID of the sales representative |
| **U/M**                              | `object`        | Unit of measurement (e.g., EA for each) |

---

## 📊 Key Insights from Dataset Analysis

### 📅 **Annual Revenue Trends**
- **Highest Revenue**: 2017 ($87.46M)  
- **Second Highest Revenue**: 2019 ($77.9M)  
- **Lowest Revenue**: 2018 ($20.82M)  

---

### 📈 **Monthly Sales Trends**
- **Peak Sales Months**: March, June, and September.  
- **Lowest Sales Months**: April, May, and October.  
![Monthly Sales Analysis](https://github.com/Vikram7856/Amazon-Sales-Analysis/blob/main/Monthly%20Sales.jpg)  
*Figure 1: Monthly sales trends showing peaks in March, June, and September.*

---

### 📆 **Weekly Sales Trends**
- **Highest Sales Days**:  
  - Sunday ($56M)  
  - Saturday ($36M)  
  - Monday ($35M)  
- **Lowest Sales Days**:  
  - Wednesday ($5M)  
  - Thursday ($1M)  

---

### 🏆 **Top Customers**
- **Top 3 Customers**:  
  1. Customer ID 10021485 ($11.4M)  
  2. Customer ID 10009676 ($10.8M)  
  3. Customer ID 10025024 ($9.3M)  
![Top Customers](https://github.com/Vikram7856/Amazon-Sales-Analysis/blob/main/Top%20Customers.png)  
*Figure 2: Top customers contributing the highest sales revenue.*

---

### 🛒 **Top-Selling Products**
- **Top Products**:  
  - Better Large Canned Shrimp  
  - High Top Dried Mushrooms  
- **Insight**: These products are top performers in both domestic and international markets.  
![Top Products](https://raw.githubusercontent.com/Vikram7856/Amazon-Sales-Analysis/main/Top%20Products.png)  
*Figure 3: Top-selling products with the highest sales performance.*

---

## 🚀 Actionable Recommendations
1. **Seasonal Promotions**: Offer discounts in April, May, and October to address low sales.  
2. **Midweek Discounts**: Introduce promotions on Wednesdays and Thursdays to balance revenue.  
3. **Weekend Campaigns**: Enhance marketing efforts on Sundays, Saturdays, and Mondays to capitalize on peak sales.  
4. **Customer Loyalty Programs**: Target top customers with personalized offers to boost retention.  
5. **Product Focus**: Increase marketing and inventory for top-selling products like *Better Large Canned Shrimp* and *High Top Dried Mushrooms*.

---

## 🛠️ Technologies Used  
- **Programming Languages**: Python, SQL  
- **Libraries**: Pandas, Matplotlib, Seaborn  
- **Tools**: Jupyter Notebook, Excel, GitHub  

---

## 🎯 Conclusion  
This analysis provided actionable insights to optimize Amazon’s sales strategies, including targeted promotions, inventory management, and customer retention programs. The findings can help maximize revenue, reduce costs, and improve overall sales performance.

---

## 🔗 Dataset Link  
[Amazon Sales Dataset](https://example.com/dataset-link)
