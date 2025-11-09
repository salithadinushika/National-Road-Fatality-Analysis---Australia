# Understanding Road Fatalities in Australia: A Data‑Driven Insight

---

## Overview
Road safety remains a critical public health challenge in Australia. Despite investments in enforcement, infrastructure, and education, the national annual fatality trend across the last 10 years has remained relatively stable. This project investigates underlying patterns and identifies high-impact groups that should be prioritized for targeted interventions.

![Annual Fatalities Trend](./images/annual-fatalities-trend.png)
*Annual fatalities trend over the last 10 years in Australia.*

![Annual Fatalities Trend](Dashboard.jpg)
*Annual fatalities trend over the last 10 years in Australia.*

The interactive Excel dashboard presents all key performance indicators (KPIs) using graphs and charts, allowing users to explore trends effectively and make data-driven decisions.

---

## 1. Problem Statement
Although multiple agencies run road safety programs, the persistent average number of annual fatalities suggests limited effectiveness of current strategies. This project focuses on uncovering patterns by state, demographic group, road environment, and temporal factors to identify high-contributing groups, enabling better policy prioritization and more effective allocation of resources.

---

## 2. Dataset
- Source: [National Road Safety Data Hub](https://datahub.roadsafety.gov.au/)
- Dataset: [Australian Road Deaths Database (Sept 2025)](https://datahub.roadsafety.gov.au/sites/default/files/documents/Australian%20Road%20Deaths%20Database%20September%202025.xlsx)
- Years analyzed: Last 10 years (2015–2025)
- Notes: Data cleaning included handling missing values, grouping categories, and creating derived columns for easier visualization.

---

## 3. Tools Used
- **Microsoft Excel** — for data transformation, cleaning, pivot tables, slicers, and interactive dashboard layout
- **Charts & Graphs** — bar charts, pie charts, and line charts for KPI visualization
- **Interactive Features** — slicers and tick boxes for dynamic KPI filtering

---

## 4. Data Cleaning & Preparation
Key steps included:
- **Missing values:** Labeled as "Unknown"
- **Year filter:** Last 10 years selected
- **Category grouping:** Granular variables (e.g., speed limits) consolidated into logical ranges: 0–29, 30–59, 60–89, 90–119, 120+ km/h
- **Derived columns:** Months, Maximum Speed Limit Groups, Age Groups, Time-of-Day Groups, Road User Groups

![Time of Day Grouping](./images/time-of-day-grouping.png)
*Example of Time of Day grouping used to simplify KPI visualizations.*

---

## 5. KPI Analysis & Key Insights
The analysis was conducted across ten dimensions:

- Annual Fatalities Trend  
- Fatalities by Month  
- Fatalities by Road User  
- Fatalities by Weekday  
- Fatalities by Time of Day  
- Fatalities by Speed Limit (km/h)  
- Fatalities by Gender  
- Fatalities by State  
- Fatalities by Remoteness  
- Fatalities by Age Group  

**Primary insight:** National annual fatalities have remained relatively stable, suggesting current broad programs may not be sufficiently targeted.

---

## 6. Data Visualization & Interactive Dashboard
The dashboard presents all KPIs interactively using graphs and charts:

- Select year ranges and one or multiple states  
- KPIs update automatically  
- "High-Contributing Groups" selector identifies top contributing demographic or environmental groups

![Dashboard Overview](./images/dashboard-screenshot.png)
*Full interactive dashboard showing KPIs and filters.*

### Highest Risk Profiles Feature
A dedicated section titled **"Highest Risk Profiles"** allows users to select any combination of KPIs via tick boxes and view the **top three contributing risk groups instantly**. This facilitates targeted decision-making for policymakers.

![Highest Risk Profiles](./images/highest-risk-profiles.png)
*Dashboard section highlighting the top contributing risk groups based on user-selected KPIs.*

---

## Conclusion & Next Steps
Targeted interventions guided by data are more effective than one-size-fits-all programs. The dashboard helps identify priority groups and design measurable interventions.

**Capabilities demonstrated:** End-to-end Excel data pipeline, cleaning, KPI selection, interactive dashboard design, and policy-relevant insights.

---

## Credits & Dataset
Data source: [National Road Safety Data Hub](https://datahub.roadsafety.gov.au/)

---

## Repository Structure
