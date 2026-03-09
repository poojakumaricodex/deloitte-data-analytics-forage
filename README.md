# Deloitte-Data-Analytics-Forage
Deloitte Data Analytics Virtual Experience – Tableau dashboard analysing machine downtime.

This repository contains my solution for the Deloitte Data Analytics Virtual Experience Program on Forage.

## Project Overview

The objective of this project was to analyze machine telemetry data from multiple Daikibo factories to identify:

• Which factory experienced the most machine downtime  
• Which machines caused the most downtime in that factory  

The analysis was performed using Tableau to create an interactive dashboard.

---

## Dataset Information

The dataset contains telemetry data collected from 4 factories:

• Daikibo Factory Meiyo – Tokyo, Japan  
• Daikibo Factory Seiko – Osaka, Japan  
• Daikibo Factory Berlin – Berlin, Germany  
• Daikibo Factory Shenzhen – Shenzhen, China  

Each factory contains multiple machines sending telemetry messages every 10 minutes.

---

## Data Processing

A calculated field **"Unhealthy"** was created where:

Unhealthy status = 10 minutes downtime

This allowed calculation of total downtime across factories and machine types.

---

## Dashboard Description

The Tableau dashboard contains two visualizations:

1️⃣ **Down Time per Factory**
- Shows total downtime in minutes for each factory.

2️⃣ **Down Time per Device Type**
- Shows which machines contribute most to downtime.

The dashboard is interactive. Selecting a factory filters the device breakdown.

---

## Key Insight

The factory with the highest downtime was:

**Daikibo Factory Seiko (Osaka)**

The machines contributing most to downtime were:

**Laser devices**

---

## Tools Used

• Tableau  
• Data Visualization  
• Data Analysis  

---

## Dashboard Preview

<img width="518" height="336" alt="Screenshot 2026-03-09 224116" src="https://github.com/user-attachments/assets/d23e9fb8-8ef8-4f34-8bef-17422240213d" />


---

## Author

Pooja Kumari  
Aspiring Data Analyst
