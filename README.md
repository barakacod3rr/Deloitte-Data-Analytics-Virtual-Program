# 📊 Deloitte-Data-Analytics-Virtual-Internship
This repository contains all completed tasks for the Deloitte Data Analytics Virtual Experience Program (Forage), where I acted as a data analyst supporting Daikibo Industrials in identifying machine failures and gender pay inequality patterns across global factory locations.

## 🧠 Project Background
I was engaged as a data analyst by Daikibo Industrials to work on two major analytics tasks:

- Telemetry Analysis:
The tech team had compiled telemetry data from 4 factory sites: Tokyo, Osaka, Berlin, and Shenzhen. Machines (9 types) generated logs every 10 minutes throughout May 2021. My task was to help determine which machines and factories experienced the most frequent breakdowns to inform maintenance strategies and operational efficiency.

- Equality Audit:
After rising concerns over gender-based pay inequality, the company asked for a data-driven audit. I worked with their Forensic Tech team to classify levels of pay inequality across job roles and locations based on an internally developed Equality Score.

## 🛠️ Skills Utilized
Data Analysis

Data Modeling

Spreadsheets (Excel)

Tableau Dashboards

Business Insight Generation

## 🧩 Task 1
## A: Understanding the Problem – Machine Failures
The main task in this track was to investigate which factory location experienced the most machine breakdowns.
and too specific machine types with the highest failure rates. The factories were:
- Daikibo Factory Meiyo (Tokyo, Japan)
- Daikibo Factory Seiko (Osaka, Japan)
- Daikibo Berlin (Berlin, Germany)
- Daikibo Shenzen (Shenzen, China)

## B: DATA CLEANUP, DATA MODELLING AND CHOOSING THE RIGHT VISUALS

I was provided a raw JSON telemetry data, no cleaning required.
But I was to model a calculated field in Tableau called "Unhealthy" assigning a value of 10 for each unhealthy status (to represent 10 minutes of downtime).

For the visuals, I decided on using bar charts and create 2 bar charts for the 

## C: VISUAL CREATIONS
After choosing the visuals I made the data Visualizations in Tableau. Below are the images of the visualizations:
![Factory‑level breakdown dashboard](Screenshot%202025-06-26%20230657.png)
Built Tableau dashboards displaying:

- Factory-wise total breakdown time
  
- Most failure-prone machine types

The insights in Tablaeu was that:
- Daikiko Factory Seiko  - laser Welder, 480 mins - THE MAIN ANSWER
- Daikiko Factory Shenzen - Laser Cutterx, 390 mins
- Daikiko Factory Meiyo - Heavy Duty Drill, 70 mins
- Daikiko Factory Berlin - Furnace, 20 mins

## 🧩 Task 2
## A: Understanding the Problem – Gender Pay Equality
Investigated workplace equity using a provided Equality Score dataset.

Business objective: classify pay fairness across roles and locations to identify areas of discrimination.

## 🛠️ B: Data Modeling with Excel
I created a new column, "Equality Class", based on the score:

Fair (–10 to +10)

Unfair (<–10 and >10)

Highly Discriminative (<–20 and >20)

I downloaded the file below in Github:
[📊 View Task 5 Equality Table (Excel)](Task%205%20Equality%20Table.xlsx) 

## 📊 C: Results Sharing
Summarized findings in an Excel workbook with clear visual indicators.

## Certificate of Completion

[🔗  (Certificate PDF)](DelotteCert_EannBaraka.pdf) 








