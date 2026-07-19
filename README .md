# Ford GoBike (Bay Wheels) — Exploratory Data Analysis

Exploratory data analysis of Ford GoBike trip-level data for the San Francisco Bay Area bike-share system. The project examines **when**, **where**, and **by whom** bikes are used, and turns those patterns into data-backed recommendations for fleet operations, station planning, and rider-segment marketing.

## 📊 Project Summary

- **Records analysed:** 94,802 individual trips
- **Type:** Individual EDA project
- **Tools:** Python, Pandas, NumPy, Plotly, Seaborn, Matplotlib

## 📁 Contents

| File | Description |
|---|---|
| `Fordgobike_EDA_Systemdata_Analysis.ipynb` | Full Jupyter notebook: data cleaning, wrangling, and 16+ visualizations |
| `Ford_GoBike_EDA_Report.docx` | Formatted written report with charts and business insights |

## ❓ Problem Statement

Bike-sharing operators need to understand usage patterns to run an efficient, profitable service. Without this insight, bikes end up unevenly distributed — shortages at high-demand stations, surpluses at low-demand ones — and marketing/pricing decisions are made without evidence of real rider behavior.

## 🎯 Business Objective

1. Improve bike and dock availability at the right stations at the right times.
2. Identify the most valuable rider segments to tailor marketing and pricing.
3. Design strategies to convert casual **Customers** into recurring **Subscribers**.

## 🔑 Key Findings

- **87% of trips** are taken by Subscribers vs. 13% by Customers.
- **Median trip duration** is 9.3 minutes — most rides are short, commute-style trips.
- **Two sharp daily peaks** at 8–9 AM and 5–6 PM, Monday–Friday, matching typical commute hours.
- **Weekdays drive volume**, but **weekends have longer average trip durations** — casual/leisure riding.
- Riders aged **25–40** make up the largest segment.
- A small set of stations near transit hubs and business districts account for a disproportionate share of trips.
- Little to no linear correlation between trip duration and rider age.

## ✅ Recommendations

1. Rebalance bikes ahead of the two daily commute peaks, prioritizing top start/end stations.
2. Prioritize fleet capacity on weekdays; schedule heavier maintenance on weekends.
3. Target the 25–40 age, Subscriber-heavy commuter segment with retention perks.
4. Launch weekend/mid-day promotions aimed at Customers to convert them into Subscribers.
5. Investigate long-duration outlier trips — possible lost/undocked bikes.

