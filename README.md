# National Road Fatality Analysis — Australia

![Dashboard Screenshot](./images/dashboard-screenshot.png)

## Overview
This project analyzes **national road fatalities in Australia** over the last 10 years using official data from the [National Road Safety Data Hub](https://datahub.roadsafety.gov.au/). The goal is to uncover patterns in road deaths across demographics, road types, and time periods, and to provide actionable insights for policymakers and road safety authorities.

The interactive dashboard presents all key performance indicators (KPIs) using graphs and charts, allowing users to explore trends effectively.

---

## Dataset
- Source: [Australian Road Deaths Database (September 2025)](https://datahub.roadsafety.gov.au/sites/default/files/documents/Australian%20Road%20Deaths%20Database%20September%202025.xlsx)
- Years analyzed: Last 10 years (2015–2025)
- Notes: Data cleaning included handling missing values, grouping categories, and creating derived columns for easier visualization.

---

## Tools Used
- **Microsoft Excel** — for data cleaning, transformation, pivot tables, and dashboard creation
- **Charts & Graphs** — bar charts, pie charts, line charts for KPI visualization
- **Interactive Features** — slicers, tick boxes, and dynamic KPI filtering

---

## Data Cleaning & Preparation
Key steps included:
- Handling missing values (labeled as "Unknown")
- Selecting the last 10 years of relevant data
- Grouping categorical variables for simplicity (e.g., speed limits grouped into ranges)
- Creating helper columns: Age Group, Time of Day buckets, Remoteness level, Weekday names

**Example: Time of Day Grouping**

| Time Range | Label          |
|------------|----------------|
| 00:00–05:59| Early Morning  |
| 06:00–11:59| Morning        |
| 12:00–17:59| Afternoon      |
| 18:00–23:59| Evening        |

---

## Key KPIs Analyzed
- Annual Fatalities Trend
- Fatalities by Month
- Fatalities by Road User
- Fatalities by Weekday
- Fatalities by Time of Day
- Fatalities by Maximum Road Speed Limit
- Fatalities by Gender
- Fatalities by State
- Fatalities by Remoteness
- Fatalities by Age Group

**Primary Insight:** The annual fatality count has remained relatively constant over the past 10 years, suggesting that current broad programs may not be sufficiently targeted.

---

## Interactive Dashboard & Features
### Highest Risk Profiles
The dashboard includes a **dedicated section** titled "Highest Risk Profiles" where users can:
- Select any combination of KPIs using tick boxes
- Instantly view the **top three contributing risk groups** based on their selection
- Focus interventions on high-impact areas to reduce fatalities

### Dashboard Features
- Select year ranges and states
- Automatically update KPI visualizations
- Explore patterns by demographics, road types, and temporal factors

![Dashboard Screenshot](./images/dashboard-screenshot.png)

---

## Conclusion
This project demonstrates:
- End-to-end data analysis in Excel
- Data cleaning, aggregation, and KPI creation
- Dashboard creation with interactive charts
- Policy-relevant insights for road safety intervention prioritization

---

## Repository Structure
