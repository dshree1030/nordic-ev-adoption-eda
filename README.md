# ⚡ Nordic EV Adoption vs Charging Infrastructure (2020–2024)

## 📊 Project Overview

This project analyzes the relationship between **electric vehicle (EV) adoption** and **charging infrastructure development** across Nordic countries:

- Norway  
- Sweden  
- Denmark  
- Finland  
- Iceland  

The goal is to evaluate whether charging infrastructure is keeping pace with EV adoption and identify potential infrastructure pressure points.

---

## 🎯 Objectives

- Analyze EV adoption trends across Nordic countries  
- Evaluate charging infrastructure growth  
- Create an **EV-per-Charger KPI** to measure infrastructure readiness  
- Compare EV growth vs charger growth  
- Identify countries with potential charging pressure  

---

## 📁 Dataset

Source: International Energy Agency (IEA)

Includes:
- EV stock
- EV sales
- EV charging points
- Vehicle categories (cars, vans, trucks, buses)
- Powertrain types (BEV, PHEV, FCEV)

---

## 🧹 Data Processing

Key steps:
- Filtered Nordic countries
- Cleaned and aggregated EV stock data
- Combined fast + slow charging points
- Merged datasets
- Created final analysis dataset
- Built EV-per-Charger KPI

---

## 📌 Key Metric

### EV-per-Charger Ratio

EV Stock / Charging Points

### Interpretation:
- Lower value → better infrastructure readiness  
- Higher value → higher charging pressure  

---

## 📊 Key Visualizations

- EV Stock Growth (2020–2024)  
- Charging Infrastructure Growth  
- EVs per Charger Trend  
- EV Readiness Ranking (2024)  

---

## 🔍 Key Insights

- Norway leads in EV infrastructure maturity  
- Denmark and Iceland show strong charging expansion  
- Sweden experienced rapid infrastructure scaling in 2023  
- Finland shows periods of infrastructure lag and recovery  
- EV adoption is generally growing faster than infrastructure in some periods  

---

## ⚠️ Charging Pressure Analysis

This analysis uses EV-per-Charger as a proxy for infrastructure pressure.

Countries with higher ratios may experience increased demand on public charging networks.

Note: This is a country-level analysis and does not include geographic charger locations.

---

## 🛠️ Tools Used

- Python  
- Pandas  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 📁 Project Structure

nordic_ev_analysis/
│
├── data/
│ ├── raw/
│ └── processed/
│
├── notebooks/
│ ├── 01_data_cleaning.ipynb
│ └── 02_analysis_and_visualization.ipynb
│
├── images/
│ ├── ev_stock_growth.png
│ ├── charging_growth.png
│ ├── ev_per_charger.png
│ └── ev_readiness_ranking.png
│
├── README.md
└── requirements.txt

---

## 🚀 How to Run

- Clone repo
- Install requirements: `pip install -r requirements.txt`
- Open Jupyter Notebook
- Run notebooks in order
