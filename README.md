# Understanding Road Fatalities in Australia: A Data‑Driven Insight for Smarter Road Safety Decisions

## 🎯 Overview

Despite ongoing investments in enforcement, infrastructure, and education, the national annual road fatality trend in Australia has remained relatively stable over the last 10 years.

This project investigates why current road safety strategies may have limited effectiveness by identifying **high-impact groups** that should be prioritized for targeted interventions. We leverage a comprehensive data-driven analysis to uncover specific patterns across various dimensions, enabling better policy prioritization and more effective resource allocation.

## 📊 Key Insights & Top Risk Profiles

The analysis focused on ten crucial dimensions, including demographics, road environment, and temporal factors.

### Top Fatality Profiles (Based on Gender and Age Group)

When filtering by **Gender** and **Age Group**, the following profiles contribute most significantly to total fatalities:

| Rank | Percentage | Profile Definition |
| :--- | :--- | :--- |
| **No 01** | **22.6%** | Male, Young-to-Mid Adults |
| **No 02** | **18.7%** | Male, Mature Adults |
| **No 03** | **15.8%** | Male, Young |

### Summary of Dashboard Metrics

The interactive dashboard includes Key Performance Indicators (KPIs) visualized across the following dimensions:

* Annual Fatalities Trend
* Fatalities by Month
* Fatalities by Weekday
* Fatalities by Road User
* Fatalities by Time of Day
* Fatalities by Speed Limit (km/h)
* Fatalities by Gender
* Fatalities by Remoteness
* Fatalities by State
* Fatalities by Age Group

## 🛠️ Tools & Technologies

The entire data pipeline and analysis were completed using **Microsoft Excel**. This project demonstrates strong end-to-end analysis capability using a widely accessible tool, including:

* Data transformation and cleaning.
* Creation of pivot tables and slicers.
* Design of a responsive dashboard layout.

## 📁 Dataset & Data Preparation

### Data Source
The analysis uses official records from the **National Road Safety Data Hub**:
* **Dataset:** Australian Road Deaths Database (Sept 2025).
* **Time Period:** The most recent 10 years of fatality records were selected to ensure relevance to the current environment.

### Key Preprocessing Steps
* **Missing Values:** Labeled as "**Unknown**" and kept for analysis to avoid information loss.
* **Category Grouping:** Granular values were consolidated into logical ranges (e.g., speed limits into 0-29, 30-59, 60-89, 90-119, $120+km/h$).
* **Derived Columns:** Helper columns were created to simplify visualization and aggregation for categories like Age Groups, Time-of-Day Groups, and Road User Groups.

## 💻 Interactive Dashboard

The dashboard presents all KPIs interactively, allowing users to **explore trends and patterns effectively**:

* **Custom Filtering:** Users can select year ranges and one or multiple states.
* **Automatic Updates:** KPIs update automatically based on selected filters.
* **Targeted Analysis:** The **"Highest Risk Profiles"** feature allows users to select any combination of KPIs to instantly view the top three contributing risk groups, enabling targeted decision-making.

| Metric | Value |
| :--- | :--- |
| **Total Deaths (10 years)** | 11,995 |
| **Avg. Annual Deaths** | 1,200 |
| **2025 National Forecast** | 1,288 |

---

Would you like me to generate a table of contents for this README, or perhaps add a section for potential future work?
