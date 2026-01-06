# Customer Churn Analysis & Sales Forecasting – Power BI Project

A comprehensive end-to-end data analytics project focused on **customer churn behavior**, **sales performance**, and **time-based trends**, built using **Power BI, SQL, Power Query, and DAX**.

This project demonstrates how raw transactional data can be transformed into **actionable business insights** through structured modeling, advanced calculations, and executive-level dashboards.

---

## 🔍 Business Problem

Businesses often struggle to:
- Identify **why customers churn**
- Understand **which customers and products drive revenue**
- Track **sales growth trends (MoM / YoY)**
- Spot **high-risk churn segments early**

This project addresses these challenges by building a **decision-ready analytical model** that enables stakeholders to:
- Monitor churn patterns
- Analyze revenue performance
- Understand customer value distribution
- Support data-driven retention and sales strategies

---

## 🎯 Project Objectives

- Analyze **customer churn trends** across tenure segments
- Identify **top revenue-generating customers and products**
- Track **monthly and yearly sales performance**
- Measure **Average Order Value (AOV)** and revenue contribution
- Build a **scalable data model** suitable for forecasting
- Deliver **interactive dashboards** for business users

---

## 🛠️ Tools & Technologies

| Tool | Usage |
|-----|------|
| **Power BI Desktop** | Data modeling & visualization |
| **Power Query** | Data cleaning & transformation |
| **DAX** | Business metrics & time intelligence |
| **SQL** | Data extraction & aggregation |
| **GitHub** | Version control & project showcase |

---

## 📂 Data Overview

The dataset represents a typical **e-commerce transactional system** including:
- Orders
- Order details
- Products
- Customers
- Date attributes

Key data fields:
- Order Date
- Product Price & Quantity
- Customer ID
- Product Categories
- Churn indicator

A **custom Calendar Table** was created to support:
- Monthly trends
- YoY / MoM growth
- Time-based slicing

---

## 🧱 Data Modeling Approach

- Star-schema style modeling
- Dedicated **Calendar table**
- Proper relationships between:
  - Orders ↔ Order Details
  - Products ↔ Order Details
  - Calendar ↔ Orders
- Measures preferred over calculated columns where possible

This ensures:
✔ Better performance  
✔ Scalability  
✔ Accurate time intelligence  

---

## 📊 Key Metrics & DAX Measures

- Total Revenue
- Net Revenue (excluding returns)
- Average Order Value (AOV)
- Monthly Revenue
- YoY & MoM Growth %
- Churn Rate
- Customer Lifetime Value (CLV)
- Revenue Contribution %

Advanced techniques used:
- `SUMX`
- `AVERAGEX`
- `LAG`
- `DIVIDE`
- Window functions
- Top-N analysis

---

## 📈 Insights & Dashboards

### 🔹 General Sales Insights
- Total and net revenue overview
- Monthly & yearly revenue trends
- Highest and lowest performing months
- Top product and category contribution

### 🔹 Customer Insights
- Top 10 customers by revenue
- Repeat vs new customer behavior
- Customer segmentation based on spend
- Revenue concentration analysis

### 🔹 Churn Analysis
- Churn rate by tenure band
- Identification of high-risk churn segments
- Retention patterns across customer maturity levels

### 🔹 Product & Order Insights
- Best-selling products (quantity & revenue)
- Return impact on revenue
- Volume-driven vs price-driven categories

### 🔹 Temporal & Regional Trends
- MoM & YoY growth
- Seasonal sales patterns
- Regional revenue distribution

---

## 📌 Visualization Highlights

| Visual | Purpose |
|------|--------|
| Clustered Column Chart | Churn Rate by Tenure Band |
| Bar Chart (Top N) | Top 10 Customers by Revenue |
| Line Chart | Monthly & YoY Revenue Trends |
| KPI Cards | Revenue, AOV, Churn Rate |
| Slicers | Date, Product, Region filters |

All visuals are optimized for **business storytelling and clarity**.

---

## 🚀 How to Run the Project

1. Clone the repository  
   ```bash
   git clone https://github.com/Tanujk01/powerbi-customer-churn-sales-forecasting
💡 Key Business Takeaways

New customers exhibit higher churn risk

Revenue is often driven by a small % of high-value customers

Certain products contribute disproportionately to revenue

Seasonal patterns strongly impact sales performance

These insights can directly support:
✔ Retention strategies
✔ Targeted marketing
✔ Revenue optimization


📄 License

This project is for educational and portfolio purposes.

👤 Author

Tanuj
Aspiring Data Analyst / Data Scientist
Focused on SQL, Power BI, and Business Analytics
