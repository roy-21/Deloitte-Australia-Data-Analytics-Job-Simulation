# Deloitte Australia – Data Analytics Job Simulation (Forage)

This repository contains my work for the **Deloitte Australia Data Analytics Virtual Experience Program** on Forage.

The program focuses on real-world data analytics and forensic technology tasks, including data visualization, dashboard creation, and data classification.

---

##  Program Overview

### Platform
- Forage  
- Deloitte Australia – Data Analytics Job Simulation

### Tools Used
- Tableau
- Microsoft Excel
- GitHub

---

##  Task 1: Data Analysis (Tableau)

### Objective
Analyze telemetry data collected from Daikibo’s factories to answer:

1. Which factory experienced the most machine downtime?
2. Which machine types broke down the most in that factory?

### Data Description
- 4 factories:
  - Tokyo (Meiyo)
  - Osaka (Seiko)
  - Berlin
  - Shenzhen
- 9 machine types per factory
- Telemetry messages sent every 10 minutes
- Data duration: May 2021
- Format: JSON

### Steps Performed
- Imported JSON telemetry data into Tableau
- Created a calculated field **"Unhealthy"**:
  - Value = 10 minutes for each unhealthy status
- Built visualizations:
  - **Down Time per Factory**
  - **Down Time per Device Type**
- Created an interactive dashboard:
  - Factory chart used as a filter for device-level analysis

### Output
- Interactive Tableau Dashboard
- Screenshot of the dashboard highlighting the factory with the highest downtime

---

##  Task 2: Forensic Technology (Excel)

### Objective
Classify gender pay equality levels across factories and job roles.

### Dataset
Excel file with:
- Factory
- Job Role
- Equality Score (-100 to +100)

### Equality Classification Logic
| Equality Score | Equality Class |
|---------------|---------------|
| -10 to +10 | Fair |
| < -10 or > 10 | Unfair |
| < -20 or > 20 | Highly Discriminative |

### Output
- Updated Excel file with an additional column: **Equality Class**

---

##  Key Learnings
- Data visualization using Tableau
- Dashboard filtering and interactivity
- Translating data into business insights
- Data classification and forensic analysis
- Presenting analytics projects on GitHub

---

##  Disclaimer
This project was completed as part of a virtual job simulation on Forage and is intended for learning and portfolio purposes only.

---

## 👤 Author
**Sojib Chandra Roy**  
Aspiring full-stack data scientist
