# OYO Revenue Analysis Dashboard

A powerful **Power BI** dashboard that transforms OYO hotel booking data into revenue-driven insights—highlighting performance across properties, booking channels, and time periods.

---

## 🧩 Project Highlights

- **🔍 Data Source**
  - Fact tables: bookings & revenue; Dimensions: rooms, hotels, dates
  - Metrics captured: revenue, bookings, cancellations, ADR, occupancy, realization

- **🧼 Data Preparation**
  - Use Power Query to clean raw CSVs: remove duplicates, nulls, ensure correct data types
  - Data modeling: establish relationships among fact and dimension tables
  - DAX measures: compute ADR, RevPAR, occupancy %, realization %, cancellation %

- **📊 Dashboard Features**
  - KPIs: Total Revenue, RevPAR, ADR, Occupancy %, Cancellation %
  - Visuals: time-series charts, bar clusters, pie charts, heatmaps
  - Filters by: hotel type, city, booking platform, date range

- **📈 Key Insights**
  - Revenue trends across time and hotel segments
  - Compare booking channels and their impact on ADR/Cancellations
  - Identify low-performing properties for improvement

---

## 🚀 Getting Started

1. **Clone** this repo or download the `.pbix` file.
2. Open in **Power BI Desktop**.
3. Load datasets (in `/data/` folder).
4. Refresh to run Power Query ETL and load the model.
5. Use slicers and visuals to explore revenue dynamics.

---

## 🔧 Customization & Extension

- **Update Data**: Add fresh CSVs in `/data/`, then refresh.
- **Add Measures**: Create custom DAX (e.g., MoM growth, forecasted ADR).
- **New Visuals**: Incorporate decomposition trees, scatter plots, or maps.
- **Styling**: Apply OYO branding and color themes to align with corporate design.

---

## 📋 Dashboard Structure

| Page             | Description                                          |
|------------------|------------------------------------------------------|
| Overview         | High-level metrics: revenue, ADR, occupancy trends  |
| Channel Analysis | Revenue & performance split by booking platform     |
| Property Insights| Compare hotel types, cities, and date-wise patterns |

---

## 🎯 Who Should Use This

- **Revenue Managers** – monitor performance and pricing strategies  
- **Operations** – spot occupancy inefficiencies and cancellation drivers  
- **Hospitality Analysts** – build on model or add predictive analytics features

---

## ✨ Design Principles

- **Clear & Insightful** – clean visuals, consistent layout, intuitive slicers  
- **Drill‑Down Focus** – start broad, then deep-dive into channels, types, or cities  
- **Interactive by Design** – all visuals are cross-filtered for guided exploration

---

## 🤝 Contributing

Open to:

- New data sources (e.g., seasonal pricing, guest satisfaction)
- Additional KPIs (e.g., RevPAR variance, time-to-book)
- UI improvements or accessibility features

Submit a pull request or open an issue for collaboration!
