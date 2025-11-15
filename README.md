# EV-Charging-Analytics

Analysis of electric vehicle (EV) charging behavior in Palo Alto using clustering, predictive modeling, and exploratory business analytics.  
This project was developed as part of the DTU course **42577 – Introduction to Business Analytics** and aims to segment EV users, forecast hourly station energy consumption, and provide strategic insights for long-term infrastructure planning.

---

## Project Context

**Course:** 42577 – Introduction to Business Analytics  
**Institution:** Technical University of Denmark (DTU)  
**Academic Period:** 2024  
**Format:** Jupyter Notebook report + supporting scripts

Electric vehicles (EVs) are essential for reducing emissions and enabling sustainable mobility. This project puts the student in the role of an EV charging provider aiming to improve charging operations, predict demand, and guide future investments.

The dataset (**EVChargingStationUsage.csv**) contains thousands of charging events, including start/end times, energy consumption, geographical information, plug type, and user identifiers. Each row represents a charging session.  
**The CSV file is not included in this repository because it exceeds GitHub's file size limits, but it was used locally throughout the analysis.**

---

## Goals

### 1. Mandatory Component – Clustering
Cluster users based on their charging habits (time of day, weekdays vs weekends, energy usage patterns).

### 2. Mandatory Component – Forecasting
Predict next-day hourly energy consumption for each charging station.  
The model must outperform a naïve historical-average baseline.

### 3. Exploratory Component
Choose additional business-relevant research questions, such as:

- Where should new charging stations be built?  
- How much revenue is lost due to hoarding?  
- Which areas have alignment between demand and infrastructure?
