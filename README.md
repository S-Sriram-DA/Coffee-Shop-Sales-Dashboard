# ☕ Coffee Shop Sales Dashboard

## 📌 Problem Statement
A coffee shop chain needed an interactive dashboard to track sales performance, customer preferences, and revenue trends. The goal was to identify peak hours, top-performing products, and underperforming items to improve staffing, inventory, and marketing strategies.

## 🛠 Tools & Technologies
- **SQL (MySQL)** → extracted and aggregated raw sales data using joins, filtering, and grouping  
- **Excel** → additional data cleaning, removing duplicates, formatting timestamps, preparing lookup tables  
- **Power BI** → data modelling (star schema), DAX measures, KPIs, and interactive dashboards  
- **Word / Documentation** → documented SQL queries and workflow for reproducibility  

## 🔄 Approach
1. Queried raw transaction data in SQL to prepare summary tables.  
2. Cleaned and transformed the extracted data in Excel (dedupe, timestamps, category mapping).  
3. Imported cleaned datasets into Power BI and built a star-schema data model.  
4. Created KPIs and interactive visuals to monitor sales, customer behavior, and trends.  
5. Designed dynamic filters/slicers for location, date, and product category.  
6. Documented SQL queries and analysis steps in Word for reporting.

## 📊 Key Insights & Recommendations
- **Morning peak hours (8–10 AM)** generated over 30% of daily sales → increase staff during this period to reduce wait times.  
- **Weekend sales were consistently higher** than weekdays → launch targeted weekend promotions or combos.  
- **Seasonal beverages boosted Q4 revenue by ~25%** → expand the seasonal product line and market earlier in the year.  
- **Top 3 products contributed ~45% of revenue** → ensure steady inventory to avoid stockouts.  
- **Bottom 3 products contributed <5% of sales** → consider discontinuing or rebranding them, or run promotions to test improvement.  

## 📸 Dashboard Preview
![Dashboard preview](./dashboard_1.png)  
![Dashboard preview](./dashboard_2.png)

## 📂 Files in this repo
- `Coffee_Shop_Sales.pbix` — Power BI file  
- `Coffee Shop Sales.xlsx` — sample dataset (sanitized)  
- `dashboard_1.png`, `dashboard_2.png` — dashboard screenshots  
- `docs/SQL_Queries.docx` — SQL queries used for data extraction (optional)  

## 🔗 Demo / PBIX Download
- Download the Power BI file: `Coffee_Shop_Sales.pbix` (included in this repo)  

## ⚠️ Notes
- Data is sanitized and contains no PII.  
- For questions or walkthrough: your.email@example.com

