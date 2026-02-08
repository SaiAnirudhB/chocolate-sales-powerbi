# 🍫 Chocolate Sales Dashboard – Power BI Project

## 📌 Project Overview
This project is an **end-to-end Power BI sales analytics dashboard** built to analyze chocolate sales performance across products, countries, time periods, and salespeople.

The goal of this project is to demonstrate **real-world data analyst skills**, including:
- Data cleaning using Power Query  
- Data modeling using star schema  
- Writing DAX measures for KPIs and time intelligence  
- Building interactive and business-focused dashboards  

This project is suitable for **Data Analyst / Power BI Developer roles**.

---

## 🛠️ Tools & Technologies Used
- Power BI Desktop  
- Power Query (ETL)  
- DAX (Data Analysis Expressions)  
- GitHub (project documentation & version control)

---

## 📂 Dataset Description
The dataset contains **transaction-level chocolate sales data** with the following fields:

- Sales Person  
- Country  
- Product  
- Date  
- Sales Amount  
- Boxes Shipped  

The data represents sales activity across multiple countries and time periods.

---

## 🔄 Data Cleaning & Transformation (Power Query)
All data preparation was performed in **Power Query**.

### Cleaning steps performed:
- Removed currency symbols and formatting from Sales Amount  
- Converted columns to correct data types (Date, Number, Text)  
- Renamed columns for business readability  
- Ensured numeric consistency for sales and quantity fields  
- Validated date values for time-based analysis  

The cleaned data was then loaded into the Power BI data model.

---

## 🧱 Data Modeling
A **Star Schema** data model was implemented.

### Tables used:
- **Fact Table:** Chocolate Sales  
- **Dimension Table:** Calendar  
- **Measures Table:** All Measures  

### Modeling decisions:
- One-to-many relationship between Calendar[Date] and Chocolate Sales[Date]  
- Separate measures table to organize all DAX calculations  
- Single-direction filtering to maintain model integrity  

---

## 📐 DAX Measures Implemented
Key business metrics calculated using DAX:

- Total Sales  
- Average Sales  
- Sales Last Year (LY)  
- Year-over-Year (YoY) Growth %  
- 3-Month Moving Average  
- Top Performer Identification  
- Month-over-Month (MoM) metrics  

All DAX logic is documented in **DAX_Measures.md**.

---

## 📊 Dashboard Features

### KPI Cards
- Total Sales  
- YoY Growth %  
- Average Sales  

### Interactive Slicers
- Year  
- Product  
- Country  

### Sales Trend Analysis
- Monthly sales trend  
- 3-Month Moving Average to smooth volatility  

### Product Performance
- Top 5 products by total sales  

### Sales Performance Breakdown
- Country → Salesperson performance  
- Detailed table with product-level metrics  

### Top Performer Highlight
- Best-performing salesperson based on sales contribution  

---

## 📸 Project Screenshots

### Dashboard Overview
![Dashboard Overview](Screenshot%20(132).png)

### Sales Trend & Moving Average
![Sales Trend](Screenshot%202026-02-08%20012948.png)

### Data Model (Star Schema)
![Data Model](Screenshot%202026-02-08%20013302.png)

### Power Query – Data Cleaning
![Power Query](Screenshot%202026-02-08%20013938.png)

---

## 🧠 Business Insights
- Strong **Year-over-Year sales growth (~54%)**
- A small number of products contribute the majority of revenue
- Certain countries and salespeople consistently outperform others
- Moving average analysis highlights long-term sales trends
## 📁 Repository Structure

