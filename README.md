
# 📦 **Solving Inventory Inefficiencies Using SQL**

## 📝 **Overview**
Urban Retail Co. is a fast-growing mid-sized retail chain with both physical stores and online operations across several cities. With over 5,000 SKUs in its catalog—including groceries, electronics, and personal care items—the company faced significant challenges in managing inventory efficiently.

Key issues included:
- Frequent **stockouts** of high-demand products, leading to lost sales.
- Excess **overstocking** of slow-moving items, tying up working capital.
- Lack of **real-time insights** into product performance and supplier reliability.
- Inefficient, reactive decision-making due to underutilized data.

👉 **Goal**: Design and implement a **SQL-driven inventory monitoring and optimization solution** that transforms raw data into actionable insights. This solution includes analytical SQL scripts, a clean relational database design, and a Power BI dashboard for decision-makers.

---

## 🎯 **Objectives**
- Normalize the raw inventory dataset into an efficient **relational database schema**.
- Develop **SQL queries** to:
  - Calculate stock levels, stockouts, reorder points, and inventory turnover.
  - Identify fast-selling vs slow-moving SKUs.
  - Forecast demand trends based on seasonality.
  - Highlight supplier performance inconsistencies.
  - Recommend stock adjustments to reduce holding costs.
- Build an interactive **Power BI dashboard** to visualize KPIs and trends.

---

## 🛠 **Tech Stack**
| Tool        | Purpose                                        |
|-------------|------------------------------------------------|
| **MySQL**   | Data storage, cleaning, analytics, SQL queries |
| **Excel**   | Data exports, manual checks, Power BI inputs   |
| **Power BI**| Visualization, dashboard creation              |

---

## 📌 **Key Features**
✅ Normalized relational schema with ERD  
✅ Advanced SQL queries:
- Stock levels, stockouts, and reorder point estimation
- Inventory turnover and SKU performance
- Supplier reliability analysis
- Seasonal demand forecasting
- Stock adjustment recommendations  

✅ Power BI Dashboard:
- Inventory health KPIs (turnover ratio, stockout %, overstock %)
- Region-wise & product-category insights
- Supplier performance charts
- Seasonal demand trend lines

---

## 📈 **Expected Business Impact**
- **Smarter inventory decisions** based on data, not intuition  
- **Reduced stockouts and overstocks**, saving costs and boosting availability  
- **Better supplier accountability** and improved supply chain efficiency  
- **Higher customer satisfaction** due to better product availability  
- **Optimized cash flow** by reducing tied-up capital in excess inventory  

---

## 💡 **Future Enhancements**
- Real-time data ingestion pipelines (ETL)  
- Predictive analytics using machine learning models for demand forecasting  
- ERP integration for automated reorder and supply chain actions  

---

## 🚀 **How to Run**
1️⃣ Import `create_schema.sql` into your MySQL instance.  
2️⃣ Load the dataset into the database (see **Resources** below).  
3️⃣ Run individual analysis queries (e.g. `stock_level_analysis.sql`) to generate insights.  
4️⃣ Export query results to CSV and load into **Power BI** for dashboarding (see `inventory_dashboard.pbix`).  

---

## 📦 **Deliverables**
✅ SQL scripts (well-documented and optimized)  
✅ Normalized schema / ERD  
✅ Power BI dashboard file (`.pbix`)  
✅ Executive summary report (PDF / DOCX)  

---

## 📂 **Resources**
- 📄 **Dataset**: [Urban Retail Co. Inventory Dataset](https://drive.google.com/drive/folders/1434xs93SKLoZkxaRzhoxhIA_sUKT-jMY)
