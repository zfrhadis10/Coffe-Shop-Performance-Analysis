# ☕ Coffee Shop Performance Analysis
<div align="center">
  <img src="https://raw.githubusercontent.com/zfrhadis10/Coffe-Shop-Performance-Analysis/main/Visuals/Screenshot%202026-02-10%20112455.png" width="50%" alt="Dashboard Preview">
</div>

<div align="center">

  [![SQL](https://img.shields.io/badge/SQL-PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org/)
  [![Power BI](https://img.shields.io/badge/Power_BI-Data_Visualization-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
  [![Analysis](https://img.shields.io/badge/Analysis-Business_Insights-success?style=for-the-badge)](#)

</div>

---

## 📌 Project Overview

Analyzed coffee shop sales data using **SQL** to identify key performance metrics and trends across various store locations during the 2025 operational period. This project transforms raw transactional data into actionable business insights, focusing on product performance, customer behavior, and sales patterns. Additionally, a comprehensive **Power BI dashboard** was developed to provide real-time visibility into business performance, enabling data-driven decision-making for inventory and marketing strategies.

## 🎯 Project Goals

* **Evaluate Sales Performance**: Identify top-performing products categories to understand revenue drivers.
* **Analyze Customer Behavior**: Determine peak transaction hours and purchasing habits, such as the average basket size of 1–2 items per transaction.
* **Optimize Operational Efficiency**: Pinpoint underperforming products to streamline inventory and reduce costs.
* **Strategic Growth**: Provide data-backed recommendations, such as bundles and location-specific upselling strategies.
* **Data Visualization**: Create an interactive dashboard to monitor daily revenue, transaction volume, and average order value (AOV) across all branches.

## 📊 Key Insights from SQL Analysis

* **Top Products**: **Coffee** and **Tea** consistently sell above the average unit per category, with **Latte** and **Earl Grey Rg** being the most popular specific items.
* **High-Performing Locations**: **Hell's Kitchen** leads in total transactions and revenue, while **Lower Manhattan** records the highest average spend per transaction.
* **Peak Hours**: A sharp spike in transactions occurs between **07:00 – 10:00 AM**, with the highest revenue recorded at 10:00 AM.
* **Sales Trends**: Weekdays (Monday - Friday) show higher transaction volumes and revenue compared to weekends.

## 🛠️ Tech Stack

* **Database**: PostgreSQL (Data cleaning, aggregation, and trend analysis).
* **Visualization**: Power BI (Interactive dashboards and KPI tracking).
* **Documentation**: Microsoft PDF (Executive Summary).

## ⚙️ Technical Highlights

* Aggregated 100K+ transactional records using `GROUP BY`, `HAVING`, and window functions to surface category and location-level trends.
* Used conditional filtering and date functions to analyze hourly and daily sales patterns.
* Calculated Average Order Value (AOV) and revenue metrics using derived fields across multiple joins.
* Built an interactive Power BI dashboard with KPI cards, time-series charts, and branch-level breakdowns for executive reporting.

## 💡 Recommendations

1. **Menu Optimization**: Consider delisting 18 underperforming product types to reduce storage costs and waste.
2. **Upselling Strategy**: Leverage **Sugar-free Syrup** as a high-value add-on for other coffee drinks.
3. **Operational Focus**: Improve service speed in Hell's Kitchen to handle massive morning volumes and prevent long queues.
4. **Saturday Specials**: Launch "Saturday Family Packages" to boost volume on the day with the highest spend per transaction but lowest total traffic.

---

## 📁 Repository Structure

```text
├── Visuals/
│   └── Dashboard.png
├── Coffee Shop Analysis.sql                    # SQL scripts for data analysis
├── Coffee Shop Performance Dashboard.pbix      # Interactive Power BI Dashboard
├── Executive Summary Report.pdf                # Full executive report             
└── README.md                                   # Project documentation
```
