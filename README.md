
# 📦 Zepto Inventory Management Using SQL

A data analysis project simulating real-world e-commerce inventory management using SQL queries, built for my data analyst portfolio.

---

## 🎯 Project Objective

This project replicates how a data analyst at an e-commerce platform (like Zepto) would:

- Organize raw inventory data,
- Perform SQL-based EDA (Exploratory Data Analysis),
- Clean and transform the data,
- Extract business insights through advanced SQL queries.

---

## 📊 Dataset Overview

The dataset includes information on:

- **Product Name, Category**
- **MRP & Discounted Prices** (converted from paise to ₹)
- **Available Quantity & Stock Status**
- **Weight and Quantity per Package**

---

## 🧹 Data Cleaning & Transformation

- Removed rows where MRP and discounted price = 0 (invalid pricing).
- Converted mrp and discountedSellingPrice from paise to rupees for clarity.
- Verified no NULL values were present.

---

## 🧠 Business Insights Extracted

- Top-performing categories and products
- Inventory gaps and overstock issues
- Discounts and pricing strategies

---

## 🔍 SQL Insights and Queries

🔷 **Top 10 Best-Value Products**  
• Identified products with the highest discount %, useful for marketing/promotion insights.

🔷 **High-MRP Out of Stock Products**  
• Highlights demand-heavy or supply chain–impacted products.

🔷 **Revenue Potential by Category**  
• Categories like **Packaged Food**, **IceCream & Desserts**, and **Chocolates & Candies** lead in potential revenue.

🔷 **Premium Pricing Strategy**  
• Found expensive products (MRP > ₹500) with <10% discount — indicating luxury pricing.

🔷 **Average Discount by Category**  
• Identified top 5 categories with highest average discounts — possibly linked to perishable items.

🔷 **Price per Gram Analysis**  
• Identified best value bulk items over 100g with low price/gram ratio.

🔷 **Weight-Based Categorization**  
• Grouped inventory into **Low**, **Medium**, and **Bulk** based on weight.

🔷 **Inventory Weight by Category**  
• "**Chocolates & Candies**" dominate in total inventory weight — useful for logistics.



## 🛠 Tools Used

- PostgreSQL
- Excel / CSV for raw data
- GitHub for version control
- Data Exploration & EDA via SQL
- Visualization (optional extension: Power BI)

---

## 📎 How to Run

1. Download the `.sql` and `.csv` files from the repo.
2. Use your SQL editor (like MySQL Workbench or pgAdmin) to run the queries.
3. Explore insights and visualize data using Power BI.

---

## 💼 Business Value

This project demonstrates practical SQL applications for:

- Inventory optimization  
- Discount strategy evaluation  
- Stock-out risk detection  
- Revenue forecasting  
- Product bundling or pricing decisions  

---

## 🧑‍💼 Author

**Satyabrata Khan**  
*Btech in C.S.E | Aspiring Data Analyst*  
📧 [6691satyabrata.k@gmail.com](mailto:6691satyabrata.k@gmail.com)  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/satyabrata-khan/)

---

## ✅ Status: Completed


