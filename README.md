# ☕ Coffee Shop Sales Dashboard

An **end-to-end interactive dashboard** project built using **Excel, MySQL, and Power BI** to analyze sales performance, customer behavior, and revenue trends for a fictional coffee shop chain.  

---

## 📌 Problem Statement  
Coffee shops generate large volumes of transactional data daily. However, without proper analysis, it is difficult to identify:  
- Best & worst performing products  
- Seasonal demand fluctuations  
- Store-wise revenue contributions  
- Customer purchasing trends  

This project aims to build a **data-driven dashboard** to monitor KPIs, identify actionable insights, and improve decision-making.

---

## 🛠 Tools & Technologies  
- **Excel** → Data cleaning & preprocessing  
- **MySQL** → Data storage & querying  
- **Power BI** → Data modeling, visualization, and dashboard creation  

---

## 🔄 Approach  

1. **Data Cleaning (Excel)**  
   - Removed duplicates & nulls  
   - Standardized date/time & categorical values  
   - Created mapping for product categories  

2. **Database Management (MySQL)**  
   - Imported cleaned dataset into MySQL  
   - Wrote SQL queries for aggregation and exploratory analysis  

3. **Data Visualization (Power BI)**  
   - Imported MySQL data into Power BI  
   - Built visuals (bar charts, line charts, maps, KPIs)  
   - Added slicers for date, product type, and store location  

---

## 📊 Dashboard Preview  

![Dashboard Screenshot](dashboard.png)  
*(Add more annotated visuals here if possible — showing slicers, charts, KPIs, etc.)*

---

## 🚀 Key Insights  

- **Revenue Peaks:** July recorded the highest sales, while February had the lowest.  
- **Product Demand:** Coffee contributes ~40% of total revenue; bakery items show seasonal peaks.  
- **Store Performance:** Store #3 consistently outperforms others in both sales and footfall.  
- **Customer Trends:** Weekends see 20% higher sales compared to weekdays.  
- **Category Growth:** Espresso-based drinks show increasing demand compared to plain brews.  

---

## 📂 Repository Structure  

├── Coffee Shop Sales.xlsx # Raw dataset (sanitized)
├── Coffee_Shop_Sales.pbix # Power BI dashboard
├── dashboard.png # Dashboard preview
└── README.md # Documentation

