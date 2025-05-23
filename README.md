# Investigating-Differences-in-Observed-Weather-Patterns-Across-Three-Stations-in-Idanre-Town (Analysis Report)
A field-based research project investigating how terrain, elevation, vegetation, and landforms influence localized weather conditions across three meteorological stations in Idanre, Ondo State, Nigeria.


## 📘 Project Overview

This study investigates how environmental factors such as terrain, elevation, vegetation, and landforms influence localized weather patterns. Data was collected from three meteorological stations in Idanre, Ondo State, Nigeria—each situated in different topographical environments.

---

## 🛠 Skills & Concepts Demonstrated

- Data collection (10-minute intervals)
- Microsoft Excel for data cleaning and aggregation
- Comparative meteorological analysis
- Visualization of weather parameters
- Understanding topography-driven microclimates

---

## ❓ Problem Statement

How do terrain and topographical features like elevation, vegetation, and landforms influence observed weather patterns across three meteorological stations within the same region?

---

## 📊 Data Sourcing & Preparation

- **Stations:**
  - **Station 1**: Technical College (Open terrain)
  - **Station 2**: Idanre Hills Resort (Rocky/hilly terrain)
  - **Station 3**: Ebun Ogunyimika Secondary School (Open terrain)
- **Collection period**: 12 days  
- **Frequency**: Every 10 minutes, 12 hours per day  
- **Instruments**: Locally sourced and mounted on 10-meter poles

📎 _Upload sample files to:_  
- `data/raw_data.xlsx`  
- `data/processed_data.xlsx`

---

## 🧹 Data Transformation & Processing

- Removed outliers and invalid values
- Computed hourly and daily averages in Excel
- Standardized format across the three stations for comparison

📎 _Optional Excel exports_:  
- `data/processed_data.xlsx`

---

## 📐 Modelling Approach

No predictive models were used. The study employed descriptive statistics, observational analysis, and geophysical reasoning. Future improvements may include GIS-based or regression-based spatial analysis.

---

## 📈 Data Analysis & Visualization

### 🔄 Station Comparison Summary

| Station | Elevation (m) | Land Cover       | Topography     | Wind Obstruction |
|---------|----------------|------------------|----------------|------------------|
| 1       | 291            | Bare ground      | Flat/Open      | None             |
| 2       | 329            | Vegetation/Rock  | Hilly/Mountain | High             |
| 3       | 286            | Bare ground      | Flat/Open      | None             |

---

### 🌞 Net Radiation

- Station 2 recorded the highest net radiation due to:
  - Lower **albedo** (dense vegetation & dark rock)
  - **Higher elevation** (less atmospheric scattering)
  - **Reduced wind** (less evaporative cooling)

📎 _Upload graph to:_  
- `visualizations/net_radiation.png`

---

### 🌬 Wind Speed

- Station 2 had the **lowest wind speeds** due to obstruction by Idanre Hill.
- Stations 1 and 3 had open exposure and hence higher wind speeds.

📎 _Upload graph to:_  
- `visualizations/wind_speed.png`

---

### 🌡 Air Temperature

- Station 2 showed **cooler temperatures**:
  - Shadow effect from hill
  - Cooling from vegetation

📎 _Upload graph to:_  
- `visualizations/air_temperature.png`

---

### 💧 Relative Humidity

- All stations followed a **diurnal pattern**:
  - Morning: High humidity  
  - Noon: Drop due to solar radiation peak  
  - Evening: Gradual rise

📎 _Upload graph to:_  
- `visualizations/relative_humidity.png`

---

## ✅ Conclusion & Recommendations

- Terrain and topography **significantly influence** weather patterns, especially radiation and wind speed.
- Station 2’s microclimatic behavior affirms the importance of considering **topographical context** in environmental forecasting.
- **Recommendations**:
  - Integrate terrain-based adjustments into forecasting models.
  - Use high-resolution instruments and GIS for broader coverage.

---

## 🚀 Future Work

- Extend study across multiple seasons
- Apply machine learning or GIS-based modeling
- Use higher-precision sensors for more robust measurements

---

## 📂 Project Structure

```bash
weather-patterns-topography-analysis/
├── README.md
├── data/
│   ├── raw_data.xlsx
│   └── processed_data.xlsx
├── visualizations/
│   ├── net_radiation.png
│   ├── wind_speed.png
│   ├── air_temperature.png
│   └── relative_humidity.png
├── report/
│   └── Analysis_Report.pdf
└── summary_table.csv
