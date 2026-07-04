# POWERBI
power bi projects and dashboards of different topics
# Customer Complaint Analysis Dashboard

An end-to-end business intelligence project designed to aggregate, clean, and visualize customer service feedback. This interactive Power BI dashboard provides stakeholders with data-driven insights to monitor complaint volumes, track resolution performance, and ensure compliance with Service Level Agreements (SLAs).

## 🚀 Features & Analytical Insights
* **Trend Analysis:** Track complaint volume spikes across monthly and quarterly intervals to identify systemic service bottlenecks.
* **Performance Metrics:** Monitor average resolution times and team performance against target operational goals.
* **SLA Compliance Tracking:** Dynamic KPIs highlighting the percentage of complaints resolved within standard SLA windows versus breached cases.
* **Granular Filtering:** Deep-dive filters to dissect complaints by category, region, submission channel (e.g., email, phone, web), and severity level.

## 🛠️ Tech Stack & Tools
* **Data Visualization:** Microsoft Power BI
* **Data Modeling & ETL:** Power Query (M Language)
* **Analytical Computations:** DAX (Data Analysis Expressions)
* **Data Preprocessing & Validation:** Microsoft Excel

## 📐 Data Architecture & Modeling
The project follows a robust ETL (Extract, Transform, Load) and modeling workflow:
1. **Data Cleaning (Excel & Power Query):** Handled missing values, formatted date metrics, removed duplicates, and validated data types.
2. **Star Schema Model:** Designed an efficient star schema structure within Power BI connecting the core fact table (`Fact_Complaints`) to optimized dimension tables (`Dim_Customers`, `Dim_Dates`, `Dim_Categories`).
3. **DAX Measures:** Engineered custom formulas to dynamically compute business metrics, including:
   * Total Complaints Volume
   * SLA Breach Rate (%)
   * Average Resolution Duration (Days)
   * Month-over-Month (MoM) Growth in Complaints

## 📂 Repository Structure
```text
├── Data/
│   └── customer_complaints_dataset.xlsx  # Cleaned source dataset
├── Dashboard/
│   └── customer_complaint_dashboard.pbix # Power BI report file
└── README.md                             # Project documentation
