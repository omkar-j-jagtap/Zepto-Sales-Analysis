# Zepto Sales Analysis – Power BI Project
Sales performance analysis of Zepto (10-minute grocery delivery) using Power BI. The dashboard highlights revenue, discounts, top categories/products, and actionable insights for decision-making

## Project Overview
Zepto, a leading **10-minute grocery delivery service**, generates massive sales data across multiple product categories.  
This project builds an **interactive Power BI dashboard** to analyze sales performance, product contribution, and discount effectiveness.  

The goal is to help decision-makers identify **key revenue drivers, profitable categories, and optimization opportunities**.

---
## Objectives
- To analyze total sales, revenue, discounts, and product-level performance.  
- To visualize category/subcategory contributions.  
- To evaluate discount impact on net revenue.  
- To provide a decision-making tool through an interactive dashboard.  

---

## Dataset Details
- **File Used**: `zepto_dashboard_ready.csv`  
- **Columns**:
  - `category` – Product category (e.g., Beverages, Chocolates, Ice Creams)  
  - `name` – Product Name  
  - `mrp` – Maximum Retail Price  
  - `discount_pct` – Discount percentage applied  
  - `available_qty` – Available stock quantity  
  - `discounted_price` – Price after discount  
  - `total_revenue` – Revenue generated  
  - … and other calculated measures (qty, buckets, etc.)  

Dataset was cleaned and transformed before being loaded into Power BI.

---

## Methodology
1. **Data Cleaning & Preparation**  
   - Handled missing values, corrected inconsistencies.  
   - Created calculated fields like `discount_amount`, `net_revenue`, `mrp_buckets`.  
   - Derived KPI measures (Total Sales, Net Revenue, Profit).  

2. **Dashboard Development in Power BI**  
   - Built slicers for category, MRP buckets, discount range, and product name.  
   - Designed KPIs for **Total Sales, Net Revenue, Discounts, Quantity Sold**.  
   - Created charts:
     - Sales contribution by category & subcategory.  
     - Top products by sales.  
     - Funnel analysis (Sales → Revenue → Profit).  
     - Profit distribution across MRP buckets.  
     - Category & product-level performance matrix.  

---

## Dashboard Features
- **KPI Cards** – Quick metrics for sales, revenue, discounts, and quantity.  
- **Category-wise Contribution** – Visualizes top categories & subcategories.  
- **Top Products** – Highlights best-selling items.  
- **Sales Funnel** – Tracks sales → revenue → profit stages.  
- **Profit & Discount Analysis** – Understands discount impact on margins.  
- **Filters Panel** – Dynamic filtering by category, price bucket, discount range, and product.  

---

## Key Findings
- **Total Sales (MRP): $13.42B**, **Net Revenue: $12.22B**.  
- **Average Discount: 7.62%**, showing moderate promotional spend.  
- **795K+ units sold** across categories.  
- **Top categories** include Chocolates, Packaged Foods, Ice Cream, and Beverages.  
- Some SKUs (like Aashirvaad meals, Amul products) are driving significant revenue volumes.  
- Funnel shows **drop-off from gross sales to net revenue**, highlighting discount impact.  

---

## Tools & Technologies
- **Power BI** – Dashboard development & visualization  
- **Excel / CSV** – Data storage & cleaning  
- **DAX Calculations** – Custom measures for KPIs  

---

## Dashboard Preview
![Dashboard Screenshot](Screenshot.png)

---

## Conclusion
This project demonstrates how **Power BI dashboards** can provide deep insights into grocery retail performance.  
It helps stakeholders make **data-driven decisions** on:  
- Product pricing & discount strategy  
- Category expansion  
- Inventory & stock optimization  
- Revenue growth planning  

---

## 📎 Project Files
- `zepto_dashboard_ready.csv` – Dataset  
- `Zepto_Sales_Analysis.pbix` – Power BI dashboard file  
- `README.md` – Documentation  

---
