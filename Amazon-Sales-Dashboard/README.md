# 📊 Amazon Sales Analytics Dashboard (Power BI)

This project is an **Amazon Sales Analytics Dashboard built using Power BI**, designed to analyze **e-commerce sales performance, product trends, geographic distribution, and customer activity**.

The dashboard integrates data from **multiple Amazon datasets** and transforms raw transactional and product data into **actionable business insights** using **data modeling, joins, DAX measures, interactive navigation, tooltips, and an Amazon-inspired UI design**.

---

## 🗂 Datasets Used

This project uses **two datasets**, each serving a different analytical purpose:

### 1️⃣ Amazon Sale Report (Excel)
- Order-level sales transactions  
- Sales amount and units sold  
- Order & shipping status  
- City and state information  
- Seller-related details  

**Used for:**
- Sales performance analysis  
- Time-based trends  
- Shipping & fulfillment insights  
- Geographic analysis (state & city level)

---

### 2️⃣ Amazon Fashion Dataset (CSV)
- Product names and categories  
- Product images  
- Reviews and return-related attributes  

**Used for:**
- Product-level performance analysis  
- Review and return insights  
- Image-based product navigation  
- Category-wise analysis  

---

## 🔗 Data Modeling & Joins

- Both datasets were loaded into **Power BI and connected using relationships**
- Tables were joined using **common identifiers (product/order-related keys)**
- Joins enabled:
  - Product-wise sales aggregation  
  - Review and return analysis per product  
  - Cross-filtering across sales, geography, and product views
- In some cases, **DAX measures were used to derive metrics across tables**

This data modeling approach ensured **accurate aggregation, filtering, and drill-down analysis** across all report pages.

---

## 🚀 Key Features

- **Executive KPI Overview**
  - **Total Sales Amount**: 89.1M  
  - **Units Sold**: 120.1K  
  - **Returns**: 2M  
  - **Total Reviews**: 231.4K  
  - **Seller Count**: 19K  

- **Time-Based Sales Analysis**
  - Sales trend analysis by date  
  - Monthly sales performance tracking  
  - Identification of peak and low-performing periods  

- **Geographical Insights**
  - **Sales by State** (Top: Maharashtra, Karnataka, Tamil Nadu)  
  - **Sales by City** (Top: Bengaluru, Hyderabad, Mumbai)  

- **Product-Level Analysis**
  - Product-based navigation with images  
  - Detailed product performance metrics  
  - Units sold, sales amount, returns, and reviews per product  

- **Order & Shipping Status Analysis**
  - Orders segmented by shipping and delivery status  
  - Helps monitor fulfillment and logistics performance  

- **Interactive User Experience**
  - Page Navigator for smooth navigation  
  - Custom tooltips for deeper insights  
  - Amazon-inspired yellow color theme for brand consistency  

---

## 📸 Dashboard Preview

![Amazon Sales Dashboard](https://raw.githubusercontent.com/aniket-analytics/Power-BI-Projects/main/Amazon-Sales-Dashboard/AmazonDashboard.jpg)

---

## 🛠 Tools & Technologies

- **Power BI Desktop**
  - Power Query for data cleaning & transformation  
  - Data Modeling & Table Relationships  
  - DAX Measures  
  - Interactive Visualizations, Tooltips & Navigation  

- **Data Sources**
  - Excel & CSV-based Amazon datasets  

---
