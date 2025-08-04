# 📦 Delivery Operations Performance Dashboard (Power BI)

This project presents an interactive dashboard built using Power BI to analyse delivery operations for a logistics company. The objective is to identify delivery performance issues, monitor compliance with cut-off timings, and evaluate efficiency across different routes.


## 🔍 Project Overview

This analysis is based on a real-world dataset from a delivery company containing:
- Trip timestamps
- OSRM-estimated times/distances
- Actual delivery performance
- Cut-off timestamps
- Route types (e.g., FTL, Carting)



## 📊 Key Features

- **Delivery KPIs**:
  - Total Trips
  - Average Delivery Time
  - On-Time vs Delayed Shipments
  - Compliance with Cut-off Timing

- **Comparative Analysis**:
  - OSRM (Expected) vs Actual Times and Distances
  - Segment-wise performance analysis

- **Operational Insight**:
  - Delay patterns by hour of day and day of week
  - Route type analysis (FTL vs Carting)
  - Cut-off compliance trends
    
##  Dashboard Snapshot

![image alrt](https://github.com/DILIPdk1101/Delivery-Operations-Performance-Dashboard/blob/a1b4ac79f7f04fabff4684bd7a74004bfbd4be9e/delivery%20project.png)

## ✅ Insights & Outcomes

- Discovered frequent cutoff violations during early morning hours on carting routes.
- OSRM time underestimates actual time consistently on longer routes.
- Weekday performance shows higher delays on Mondays and Thursdays.

These insights could inform changes in routing logic, dispatch timing, and resource allocation.


## 🧠 Future Enhancements

- Integrate weather or traffic API for deeper root cause analysis.
- Implement delay prediction using Python & ML models.
- Add drill-down filters for region, hub, or vehicle type.
- Auto-refresh Power BI reports from cloud-hosted dataset.


## 🛠 Tools & Technologies

- Power BI (DAX, Measures, Visuals)
- Excel for preprocessing
- OSRM API data (precomputed)
- GitHub for versioning




Feel free to open issues or suggestions to improve the dashboard or analysis!
