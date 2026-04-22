# Automated-Monthly-Operations-Report
This project focuses on automating the standard monthly reporting cycle for organizational operations. Traditionally a manual, error-prone task in Excel, this solution utilizes Power BI to provide a real-time, interactive dashboard that tracks resource utilization, financial health, and project milestones.

---

## 🎯 Objectives
- To provide real-time tracking of critical metrics such as Resource Utilization, Operating Margins, and Project Health.
- To enable stakeholders to perform "Root Cause Analysis" through interactive drill-downs and filtering rather than viewing static tables.
- To visualize month-over-month (MoM) performance and identify operational bottlenecks before they impact the bottom line.

  ---

## ⚙️ Data Preparation

### 🧼 Data Cleaning
- Brought consistancy in data ("quality" : "Quality", "Maint": "Maintenance")
- Fixed Date Column through New Column by example
- Filled null values

  ### 📈 Data Enrichment (Measures)
- Added DAX measures for:
  - `Average OEE`
  - `Total Planned`
  - `Total Production`
  - `Total Scrap`

 ---

 ## 📊 Dashboard Overview
 The dashboard consists of **two interactive pages**:

 ### 🧾 1. Overview Page

 ![Overview page](Powerbi_Images\Screenshot 2026-04-22 123236.png)

 A high-level overview with interactive KPIs, charts, filters, and navigation buttons.
