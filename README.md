# 🏨 Atliq Hospitality Revenue Analytics  
### 📊 End-to-End Business Intelligence Dashboard using Power BI  

<p align="left">
  <img src="https://img.shields.io/badge/Tool-Power%20BI-yellow" />
  <img src="https://img.shields.io/badge/Data%20Model-Star%20Schema-blue" />
  <img src="https://img.shields.io/badge/Skills-DAX%20%7C%20Power%20Query%20%7C%20Analytics-green" />
</p>

---

## 🚀 Project Overview  

**Atliq Hospitality** is an *imaginary hotel chain* operating across multiple cities.  
This project delivers an **end-to-end revenue analytics solution** to help management monitor **revenue, occupancy, ADR, RevPAR, and booking trends** using **Power BI**.

🔹 Built completely inside Power BI  
🔹 Clean star schema data modeling  
🔹 Business-focused KPIs and insights  

---

## 🎯 Business Objective  

Hospitality leadership needs answers to:

- 📈 Which hotels and cities generate the highest revenue?
- 🏨 How does occupancy impact overall performance?
- 💰 What is the trend of ADR and RevPAR over time?
- 🛏️ Which room types perform better?
- ❌ How cancellations affect revenue?

This dashboard provides **clear, actionable insights** for decision-making.

---

## 🗂️ Data Architecture  

### ⭐ Star Schema Model  

**Dimension Tables**
- 📅 `dim_date`
- 🏨 `dim_hotels`
- 🛏️ `dim_rooms`

**Fact Tables**
- 📘 `fact_bookings`
- 📕 `fact_aggregated_bookings`

📌 All transformations were done using **Power Query** for clean and optimized modeling.

➡️ Star schema diagram available in `03_data_modeling/star_schema.png`

---

## 🔄 Data Transformation (Power Query)  

Key transformation steps:
- Data cleaning and standardization
- Datatype correction
- Column renaming for consistency
- Creation of aggregated fact table
- Model-ready structure for analytics

📁 Detailed steps: `02_power_query/transformation_steps.md`

---

## 📐 Key Metrics & KPIs (DAX)  

Business-critical measures created using DAX:

- 💵 **Total Revenue**
- 🏨 **Occupancy %**
- 💲 **ADR (Average Daily Rate)**
- 📊 **RevPAR**
- 📅 **Booking Count**
- ❌ **Cancellation Rate**

📁 Full DAX documentation: `04_dax_metrics/dax_measures.md`

---

## 📊 Dashboard Highlights  

✔ Executive-level revenue overview  
✔ Time-series trend analysis  
✔ Hotel & city performance comparison  
✔ Room type analysis  
✔ Clean, business-focused visuals  

📸 Dashboard screenshots available in `06_visual_proof/`

---

## 📷 Dashboard Preview  

> *(Add images here once uploaded)*


## 🛠️ Tools & Technologies  

- 🟡 **Power BI**
- 🔄 **Power Query**
- 📐 **DAX**
- 📊 **Excel** (initial data inspection)

---

## 🧠 Key Business Insights  

- Luxury hotels show higher ADR but lower weekday occupancy
- Certain cities consistently outperform others in RevPAR
- Weekends contribute disproportionately to revenue
- Specific room types have higher cancellation rates
- Seasonal trends significantly impact occupancy

📁 Detailed insights: `00_project_overview/key_insights.md`

---

## 📈 Outcome & Impact  

This solution enables stakeholders to:
- Monitor revenue performance in real time
- Identify underperforming hotels and cities
- Optimize pricing and occupancy strategies
- Make data-driven operational decisions

---

## 🔮 Future Enhancements  

- Migrate data pipeline to SQL
- Implement incremental refresh
- Add forecasting using time intelligence
- Apply role-level security (RLS)

📁 See: `07_future_improvements.md`

---

## 👤 Author  

**Yeshwan Raj**  
Aspiring Data Analyst | Power BI & Analytics  

🔗 *GitHub Portfolio Project*



