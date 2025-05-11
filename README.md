
## 📊 Sales Performance Dashboard

This project analyzes regional sales performance using Power BI.

📥 [Download the PBIX Dashboard File](https://github.com/gurusumiran25/Sales-Performance-Dashboard/raw/main/SalesPerformance_Dashboard.pbix)

---

### 🧠 Problem Statement

The dashboard provides a high-level overview of sales performance across regions. It helps business teams answer:

* Which region is generating the highest revenue?
* What are the total orders, profit, and quantity sold?
* Are there patterns in performance across customer types?

---

### 📈 Key Metrics

* Total Sales
* Total Profit
* Total Quantity
* Total Orders
* Sales by Region
* Customer Type Breakdown

---

### ✅ Tools & Technologies Used

| Tool                   | Purpose                                      |
| ---------------------- | -------------------------------------------- |
| **Power BI Desktop**   | Data modeling, DAX measures, dashboard build |
| **MySQL**              | Backend database for storing sales data      |
| **Power Query Editor** | Data transformation and cleanup              |
| **DAX**                | Creating calculated measures and KPIs        |
| **GitHub**             | Hosting PBIX file and version control        |

---

### 📌 File

* `SalesPerformance_Dashboard.pbix` – Full Power BI project with all visuals

---

### 🔧 Steps Followed

1. **Connected Power BI to MySQL database** using native connector
2. Imported and modeled `sales_performance` table
3. Created key **measures** using DAX:

   * Total Sales = `SUM(Sales)`
   * Total Profit = `SUM(Profit)`
   * Total Quantity = `SUM(Quantity)`
   * Total Orders = `DISTINCTCOUNT(Order ID)`
4. Designed interactive visuals:

   * KPI Cards
   * Clustered Bar (Sales by Region)
   * Pie Chart (Sales by Customer Type)
5. Used slicers and filters to enable dynamic interaction
6. Applied consistent color themes, layout alignment, and formatting
7. Exported to PDF and `.pbix`, hosted on GitHub

---

📸 Dashboard Snapshots

🔹 Overview Page - 

![Screenshot 2025-05-11 184227](https://github.com/user-attachments/assets/41a93e4f-b777-41e0-bea0-d0d341b49a53)

🔹 Sales by Region (Bar Chart) - 

![Screenshot 2025-05-11 185047](https://github.com/user-attachments/assets/d93b4fce-ab43-40dd-ab9a-2f4f28dc5637)

🔹 Profit Trends (Line Chart) - 

![Screenshot 2025-05-11 185355](https://github.com/user-attachments/assets/5f497a09-db56-465e-b824-5993ef3d3339)

🔹 Customer Type Breakdown (Donut Chart) - 

![Screenshot 2025-05-11 184947](https://github.com/user-attachments/assets/cac7a484-bb08-4bc5-8f58-71f728fec6b2)


### 🧠 Insights

* Central and East regions are top contributors in terms of total sales
* Most sales come from **Retail** customers (Pie Chart)
* Over 500 orders placed, with healthy profit margins

---

### 🌟 Summary

A clean, interactive Sales Dashboard ideal for presenting to stakeholders or adding to a data portfolio. This project demonstrates Power BI fundamentals like DAX, data transformation, and real-world business application.

---

💡 *Want a live version? Set up auto-refresh via Power BI Service or move data to SQL Server with DirectQuery enabled.*

