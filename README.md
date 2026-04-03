# 📊 BlinkIT Grocery Sales Performance Dashboard – Power BI

## 📝 Overview
This Power BI project presents a comprehensive Grocery Sales Performance Dashboard for BlinkIT.  
The dashboard analyzes sales trends across items, outlets, and locations to uncover key drivers of performance and profitability.  
It helps decision-makers optimize inventory, marketing strategy, and outlet operations.

---

## 🎯 Objectives
- Provide visibility into total sales and item-level performance  
- Compare Outlet Types and Outlet Location Types  
- Identify top and bottom performing Item Types  
- Analyze the impact of Item Visibility and Item Weight on sales  
- Understand the influence of outlet ratings and establishment year  

---

## 📂 Dataset Description

**Source:** BlinkIT Grocery Data (Excel/CSV) (https://github.com/as764994-droid/blinkit-grocery-sales-performance-dashboard-powerbi/blob/main/BlinkIT%20Grocery%20Data.xlsx) 
**Rows:** ~8,523  
**Model Type:** Single Fact Table  

### Key Columns
- Sales  
- Item Type  
- Item Identifier  
- Outlet Type  
- Outlet Location Type  
- Item Visibility  
- Item Weight  
- Rating  
- Outlet Establishment Year  

**Time Range:** 2011–2022

---

## 📌 Business Requirements
- Track Total Sales, Average Sales, and Customer Rating  
- Compare sales and ratings across Outlet Types  
- Identify sales contribution by Item Type  
- Analyze Item Visibility and its correlation with Sales  
- Examine sales performance by Outlet Location Type  

---

## 📊 Key Performance Indicators (KPIs)

| KPI | Description | Formula |
|-----|-------------|---------|
| **Total Sales** | Total revenue from all transactions | `SUM('BlinkIT Grocery Data'[Sales])` |
| **Average Sales** | Avg sales per transaction | `AVERAGE('BlinkIT Grocery Data'[Sales])` |
| **Total Items** | Total unique items | `DISTINCTCOUNT('BlinkIT Grocery Data'[Item Identifier])` |
| **Average Rating** | Mean customer rating | `AVERAGE('BlinkIT Grocery Data'[Rating])` |

---

## 📈 Visuals Used
- **KPI Cards:** Total Sales, Avg Sales, Avg Rating  
- **Donut Chart:** Sales by Item Type  
- **Bar Chart:** Sales & Ratings by Outlet Type  
- **Scatter/Line Chart:** Visibility vs Sales  

---

## 📌 Dashboard Sections
1. **Key Metrics & Trends**  
2. **Outlet & Location Performance**  
3. **Item Analysis & Visibility Insights**  

---

## 🔍 Key Insights

### 🏬 Outlet Performance
- **Supermarket Type1** generates the highest total sales  
- **Supermarket Type3** shows high customer satisfaction despite lower sales  

### 🌍 Location Insights
- **Tier 3** locations contribute the highest overall sales  
- Tier 2 follows closely  

### 🍎 Item Insights
- Highest-selling categories:  
  - Fruits & Vegetables  
  - Snack Foods  
  - Household Items  

### 👁 Visibility Insights
- Low visibility items often show **high sales**, indicating strong recurring demand  
- High visibility does not guarantee high revenue  

---

## 🛠 Tools & Technologies
- Power BI Desktop  
- DAX for data modeling  
- Power Query (M Language) for data transformation  

---

## 📥 Installation / How to Use
1. Download all repository files  
2. Open `BLINKIT.pbix` (https://github.com/as764994-droid/blinkit-grocery-sales-performance-dashboard-powerbi/blob/main/BLINKIT.pbix) in **Power BI Desktop**  
3. If file path changes:  
   Go to **Home → Transform Data → Data Source Settings**  
4. Refresh to view updated insights  

---

## 📘 Conclusion
The BlinkIT Sales Dashboard provides actionable insights into outlet performance, item profitability, and customer engagement.  
It serves as a strategic tool for improving inventory planning, marketing, and operational efficiency.

---

## 📩 Contact
**Priyanshu Sahu**  
((https://github.com/sahuPriyanshu9))

---
