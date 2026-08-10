# 📊 Retail Store Sales Performance

An interactive Power BI dashboard for analyzing retail sales, revenue, products, customers, and store performance. It provides KPIs, interactive slicers, charts, and detailed sales insights to support data-driven business decisions.  Tools: Power BI, Power Query, DAX

---

## 📌 Project Overview

The **Sales Analytics Dashboard** is a Business Intelligence project developed using Microsoft Power BI.

The purpose of this project is to transform sales transaction data into meaningful and interactive business insights.

The dashboard provides analysis of:

- 💰 Total Sales
- 📦 Total Orders
- 👥 Total Customers
- 🛍️ Total Products
- 💵 Total Profit
- 🏪 Total Stores
- 🌎 Regional Sales
- 🏷️ Brand Performance
- 📦 Product Performance
- 🏬 Store Performance
- 🏙️ City-wise Sales
- 📊 Category Performance
- 📅 Year-wise Sales
- 📈 Monthly Sales Trends
- 📆 Quarterly Sales
- 🛒 Channel-wise Sales
- 📈 Year-to-Date Sales
- 📅 Month-to-Date Sales
- 🔄 Previous Year Sales Comparison

The project demonstrates the complete Business Intelligence workflow:

**Data → Data Cleaning → Data Modeling → DAX → Visualization → Dashboard → Business Insights**

---

# 🎯 Project Objectives

The main objectives of this project are:

- Analyze overall sales performance.
- Track total sales and total profit.
- Analyze total orders and customers.
- Analyze product and store performance.
- Compare sales across different regions.
- Identify high-performing brands.
- Identify profitable products and categories.
- Analyze sales by store and city.
- Analyze sales across different channels.
- Track monthly and quarterly sales trends.
- Compare current-year sales with previous-year sales.
- Calculate Year-to-Date sales.
- Calculate Month-to-Date sales.
- Create an interactive Power BI dashboard.
- Provide meaningful insights for business decision-making.

---

# 🛠️ Tools & Technologies Used

| Tool / Technology | Purpose |
|---|---|
| **Microsoft Power BI** | Dashboard development and visualization |
| **Power Query** | Data cleaning and transformation |
| **DAX** | Measures and business calculations |
| **Data Modeling** | Creating relationships between tables |
| **Power BI Visuals** | Charts, KPI cards, tables and slicers |

---

# 📂 Dataset Information

The Power BI project uses a **fact and dimension data model**.

The main data components include a central fact table and supporting dimension tables.

---

## 📌 Fact Table

### `Fact Table`

The fact table contains the transactional sales information used for the main calculations.

It is used to calculate metrics such as:

- Total Sales
- Total Orders
- Total Profit
- Total Customers
- Total Products
- Total Stores
- YTD Sales
- MTD Sales
- Previous Year Sales

---

## 🏪 Dim Store

The Store dimension contains information related to stores and sales channels.

It is used for:

- Store analysis
- Channel analysis
- Store-wise sales
- Store performance comparison

---

## 🛍️ Dim Product

The Product dimension contains product-related information.

It is used for:

- Product analysis
- Brand analysis
- Category analysis
- Product-wise sales
- Brand-wise profit

---

## 👥 Dim Customer

The Customer dimension contains customer-related information.

It is used for:

- Customer analysis
- Region analysis
- City analysis
- Regional sales comparison

---

## 📅 Dim Calendar

The Calendar dimension is used for time-based analysis.

Important fields include:

- Date
- Year
- Month
- Month Name
- Quarter

It supports:

- Monthly sales analysis
- Quarterly sales analysis
- Yearly sales analysis
- MTD calculations
- YTD calculations
- Previous-year comparison

---

# 🗂️ Data Model

The project follows a **star-schema-style data model**.

The Fact Table acts as the central table and is connected to multiple dimension tables.

```text
                     Dim Store
                         │
                         │
                         ▼
Dim Product ─────── Fact Sales ─────── Dim Customer
                         │
                         │
                         ▼
                   Dim Calendar
```

Raw Sales Data
       ↓
Data Cleaning
       ↓
Power Query Transformation
       ↓
Data Modeling
       ↓
DAX Measures
       ↓
Time Intelligence
       ↓
KPI Creation
       ↓
Data Visualization
       ↓
Interactive Dashboard
       ↓
Business Insights



## 👩‍💻 Author

**Sanghamitra Samantara**

GitHub: https://github.com/Sibanisanghamitra


*Project:* Retail Store Sales Performance
*Technology:* Microsoft Power BI
