# Earthquake Analysis Project using SQL

## 📌 Project Overview
This project analyzes historical earthquake data using **SQL** to identify patterns in seismic activity across time.  
The goal is to understand **earthquake frequency, intensity, seasonality, and risk trends** that can support preparedness planning and situational awareness.

The project focuses on **time-based analysis**, **trend detection**, and **risk-oriented insights**, demonstrating practical SQL skills on a real-world dataset.

---

## 🎯 Objectives
- Analyze earthquake frequency across different time periods (yearly and monthly).
- Identify periods with higher seismic activity.
- Examine earthquake magnitude and depth using statistical measures such as average, minimum, and maximum.
- Identify high-risk earthquake events based on magnitude and depth.
- Observe long-term trends in earthquake occurrence and severity.

---

## 📂 Dataset Overview
The dataset contains historical records of global seismic events.

### Columns in the dataset:
- **ID** – Unique identifier for each earthquake event  
- **Date** – Date of occurrence  
- **Time** – Time of occurrence  
- **Latitude** – Latitude of the earthquake epicenter  
- **Longitude** – Longitude of the earthquake epicenter  
- **Type** – Type of seismic event (Earthquake / Nuclear Explosion)  
- **Depth** – Depth of the earthquake (km below surface)  
- **Magnitude** – Strength of the earthquake  
- **Magnitude Type** – Scale used to measure magnitude  
- **Source** – Reporting agency  
- **Status** – Review status of the event  

---

## 🧹 Data Preparation
- Combined **Date** and **Time** into a single `Datetime` column using SQL
- Ensured numeric consistency for magnitude and depth
- Filtered data where required for significant earthquake analysis

---

## 🧮 SQL Analysis
SQL was used to answer analytical questions such as:
- How many earthquakes occur annually and quarterly
- Which years experienced the most significant earthquakes
- Monthly, weekly, and hourly earthquake distribution
- Seasonal trends in seismic activity
- Time gaps between major earthquakes
- Recent earthquake activity and short-term trends

### SQL concepts used:
- Date & time functions (`PARSE_DATETIME`, `EXTRACT`, `FORMAT_DATE`)
- Aggregations (`COUNT`, `AVG`, `MAX`)
- Conditional logic (`CASE WHEN`)
- Window functions (`LAG`)
- Subqueries and time-based filtering

---

## 🔍 Insights & Findings
- Earthquakes show clear **time-based and seasonal patterns**.
- **High-magnitude earthquakes** are rare but carry high risk.
- **Shallow earthquakes** have greater potential for surface damage.
- Seismic activity peaks during specific **months and hours**.
- Significant earthquakes occur at **measurable time intervals**.

---

## 💡Suggestions
- Focus preparedness and monitoring on **high-risk periods and seasons**.
- Prioritize tracking of **shallow and high-magnitude events**.
- Use historical trends for **risk-aware infrastructure planning**.
- Strengthen early-warning systems during **peak seismic activity windows**.

---


**Arpita Badatia**  
Aspiring Data Analyst | SQL | Data Analysis
