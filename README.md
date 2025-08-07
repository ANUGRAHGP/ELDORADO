# 🇮🇳 India Air Quality Dashboard (Power BI)

## 📌 Overview

This project analyzes air quality data across Indian cities and states using Power BI, offering deep insights into pollution patterns, seasonal variations, prominent pollutants, and the correlation between electric vehicle adoption and AQI. The dashboard helps identify **emerging, established, and severe air quality hotspots**, enabling data-driven decisions for policy makers, researchers, and sustainability advocates.

---

## 📊 Key Features

- ✅ **City & State-Level AQI Insights**  
  View average AQI by state, city, and month with clear visualizations.

- 🌤️ **Seasonal & Monthly Trends**  
  Understand how AQI changes across **Summer, Monsoon, and Winter** seasons.

- 🗓️ **Weekday vs Weekend Pollution**  
  Compare air quality behavior in metro cities on weekdays and weekends.

- ⚠️ **Hotspot Detection**  
  Classifies cities into:
  - **Emerging Hotspots**
  - **Established Hotspots**
  - **Severe Hotspots**  
  Based on AQI and % of unhealthy days (Moderate, Poor, Very Poor, Severe).

- 🔍 **Top Pollutants by Zone & State**  
  Identify the two most frequent pollutants contributing to poor air quality.

- 🚗 **EV vs AQI Correlation**  
  Tracks % EV adoption from vehicle registration data and compares it to AQI changes by state.

---

## 🗂️ Data Sources

- **AQI Dataset:** Hourly/daily AQI data across Indian cities
- **Vehicle Registration Data:** State-wise vehicle registration by fuel type (Electric, Petrol, Diesel, etc.)

---

## 🛠️ Tools & Technologies

- **Power BI:** Dashboard creation and visualization  
- **Python (Pandas, NumPy):** Data cleaning, wrangling, and preprocessing  
- **CSV/Excel Files:** Raw data formats  
- **Git:** Version control  
- **Power BI DAX:** Advanced aggregations and calculations  

---

## 📈 Metrics Used

- **Average AQI**
- **% of Unhealthy Days** (`Status ∈ [Moderate, Poor, Very Poor, Severe]`)
- **EV Penetration %** = Electric vehicles / Total vehicles
- **Top Pollutants** using frequency count
- **Hotspot Classification**:
  - **Emerging Hotspot:** Avg AQI > 100 and 30–50% unhealthy days
  - **Established Hotspot:** Avg AQI > 150 and 50–75% unhealthy days
  - **Severe Hotspot:** Avg AQI > 200 and >75% unhealthy days or >20% days of Very Poor/Severe

---

## 📁 Folder Structure

