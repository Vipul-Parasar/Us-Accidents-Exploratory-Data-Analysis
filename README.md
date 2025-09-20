# US Accidents Data Analysis

This project performs an **Exploratory Data Analysis (EDA)** of the [US Accidents dataset](https://www.kaggle.com/sobhanmoosavi/us-accidents) to uncover insights about road accidents in the United States.  
The dataset contains over 7 million accident records (2016–2021), with features such as location, weather conditions, severity, and time of occurrence.

---

## 📌 Project Overview

The analysis focuses on:
- Cleaning and preprocessing accident data (handling missing values, duplicates, and unnecessary columns).
- Exploring accident patterns by **severity, time, location, and weather conditions**.
- Visualizing accident distributions using **matplotlib, seaborn, squarify, and folium**.
- Identifying high-risk conditions such as:
  - Time of day (rush hours vs weekends).
  - Visibility levels.
  - Specific weather conditions.
  - Road features (junctions, bumps, signals).
- Building **heatmaps** and **geospatial plots** to visualize accident-prone areas.

---

## 🛠️ Technologies Used

- **Python**  
- **Libraries:**
  - `pandas`, `numpy` → Data manipulation
  - `matplotlib`, `seaborn`, `squarify` → Data visualization
  - `folium` → Interactive maps & heatmaps
  - `opendatasets` → Kaggle dataset downloader

---

## 📂 Notebook Workflow

1. **Data Loading**  
   Downloaded from Kaggle using `opendatasets` and loaded into Pandas.

2. **Data Cleaning & Preprocessing**  
   - Dropped irrelevant columns.  
   - Converted datatypes.  
   - Removed duplicates and missing values.  

3. **Exploratory Data Analysis (EDA)**  
   - Accident severity distribution.  
   - Impact of bumps, junctions, and traffic signals.  
   - Accidents by temperature, visibility, and weather.  
   - Top accident-prone cities and states.  
   - Trends across years, months, and hours.  

4. **Visualization**  
   - Bar charts, histograms, pie charts.  
   - Treemaps for state/city accidents.  
   - Scatter plots of geolocations.  
   - Heatmaps using `folium`.

---

## 📊 Key Insights

- Majority of accidents are of **Severity 2** (moderate).  
- **California, Florida, and Texas** report the highest number of accidents.  
- Poor **visibility** increases the chance of severe accidents.  
- Certain **weather conditions** (Fog, Snow, Rain) have higher severity rates.  
- Accidents peak during **rush hours (7–9 AM, 4–6 PM)**.  
- Weekdays show different hourly patterns compared to weekends.  

---
