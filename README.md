# air-quality-analysis-powerbi
# 🌍 Air Quality Analysis Dashboard (Excel + Power BI)

## 📌 Project Overview

This project analyzes air quality data across different cities and states to identify pollution patterns and high-risk regions.

The project demonstrates:

* Data Cleaning (Excel & Power Query)
* Data Modeling (Power BI)
* DAX Calculations
* Interactive Dashboard Design

---

## 🛠️ Tools Used

* Microsoft Excel
* Power BI
* DAX
* Power Query

---

## 📂 Dataset Features

* Location: Country, State, City, Station
* Pollutants: PM2.5, PM10, NO2, CO, OZONE
* Metrics: Min, Max, Average Pollution
* Geo Data: Latitude, Longitude

---

## 🧹 Data Cleaning

* Replaced missing values (`NA` → null)
* Converted numeric columns
* Standardized date format
* Trimmed text fields

---

## 🛠️ Feature Engineering

* Created Pollution Range
* Categorized pollution levels (Good → Severe)

---

## 🧱 Data Model

* Fact Table: AirQuality
* Dimensions: Location

---

## 📏 DAX Measures

```DAX
Avg Pollution = AVERAGE(AirQuality[pollutant_avg])
Max Pollution = MAX(AirQuality[pollutant_avg])
Total Records = COUNTROWS(AirQuality)
```

---

## 📊 Dashboard Features

### 🔹 KPI Cards

* Avg Pollution: 42.95
* Total Records: 3445
* Max Pollution: 341

### 🔹 Visuals

* State-wise pollution analysis
* Top polluted cities
* Pollution category distribution
* Geographic map visualization

---

## 🎛️ Slicers

* Pollutant Type
* State
* Pollution Category

---

## 📈 Key Insights

* Majority of observations fall under “Good” category
* PM2.5 and PM10 dominate pollution levels
* Certain cities show consistently high pollution

---

## ⚠️ Limitations

* Dataset is a single snapshot (no time-series analysis)

---

## 🔮 Future Improvements

* Add time-based data for trend analysis
* Build predictive models
* Integrate weather data


---

## 🚀 How to Use

1. Open `.pbix` file in Power BI
2. Use slicers to filter data
3. Explore insights interactively


---

## ⭐ If you found this useful

Give this repo a ⭐ and connect on LinkedIn!
