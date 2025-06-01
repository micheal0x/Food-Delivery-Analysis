
# 🍽️ Food Delivery Performance Analysis

This notebook presents an end-to-end analysis of factors affecting food delivery performance. 
It includes data cleaning, exploratory data analysis (EDA), and key visualizations to uncover insights 
related to traffic, weather, personnel, and other operational metrics.

---

## 🔍 Objectives

- Analyze how traffic, weather, and festivals impact delivery duration.
- Evaluate delivery personnel efficiency based on performance ratings.
- Visualize geographic delivery patterns.
- Identify peak order times and vehicle impact on delivery outcomes.
- Provide recommendations to improve efficiency and customer experience.

---

## 📊 Tools Used

- **Pandas** and **NumPy** for data manipulation
- **Matplotlib** and **Seaborn** for visualization
- **Plotly** for interactive charts (optional)
- **Power BI** for dashboard creation

---

## 📁 Dataset Overview

Dataset columns include:

- `Order_DateTime`, `Delivery_duration_mins`
- `Traffic_Condition`, `Weather_Condition`, `Festival`
- `Delivery_Person_ID`, `Vehicle_Condition`
- `Latitude`, `Longitude`, `Delivery_Person_Rating`, `Age`

---

## 📈 Key Insights

- 🚗 High traffic and bad weather increase delivery time significantly.
- 🧑‍💼 Top-rated personnel are consistently faster and more reliable.
- 📍 Lagos and Abuja are high-density delivery zones.
- ⏰ Peak ordering time is between **6–9 PM**, especially on weekends and festivals.
- 🛵 Poor vehicle conditions correlate with late deliveries.

---

## ✅ Recommendations

- Increase staffing during high-demand periods and festivals.
- Optimize routing using real-time traffic and weather data.
- Launch personnel training and incentive programs.
- Introduce vehicle maintenance support for delivery riders.
- Communicate delivery delays transparently during peak and poor weather conditions.

---

## 📌 Dashboard (Power BI)

Includes visuals for:

- Average Delivery Time by Traffic & Weather
- Personnel Ratings vs Delivery Time
- Order Volume Over Time with Festival Highlights
- Delivery Location Heatmap (Latitude & Longitude)
- Peak Hour Heatmap for Orders and Pickups

---

*This notebook is part of a full project repository that includes the Power BI dashboard and presentation slides.*
