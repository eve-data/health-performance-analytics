# Health Performance Analytics

End-to-end analytics project exploring activity, recovery, sleep, cardiovascular health and performance using multi-year Huawei Health wearable data.

## Overview

This project analyses multiple years of wearable health and activity data collected through Huawei Health.

The goal is to transform raw exports containing health metrics, activity records, GPS routes and recovery indicators into a structured analytics platform that supports retrospective analysis, performance monitoring and future decision support.

The project combines data engineering, analytics and visualisation techniques to investigate long-term relationships between training, recovery, health signals and performance outcomes.

---

## Research Questions

- How do sleep, recovery and cardiovascular metrics change over time?
- What patterns emerge before periods of reduced performance or injury?
- How does training load influence recovery and readiness?
- How does the mix of activities change across different training phases?
- Which metrics provide the earliest indication of accumulated fatigue or declining fitness?

---

## Data Sources

Huawei Health exports containing:

- Activity records
- Running workouts
- GPS routes
- Sleep metrics
- Heart rate data
- Resting heart rate
- Heart rate variability (HRV)
- Stress measurements
- Recovery indicators
- Training load metrics
- Running dynamics
- Daily movement data

---

## Project Architecture

```text
Huawei Health Export
│
├── Excel files
├── CSV files
├── JSON activity records
├── GPS route data
└── Metadata descriptions

        ↓

Bronze Layer
│
├── Raw ingestion
└── Source preservation

        ↓

Silver Layer
│
├── Data cleaning
├── Standardisation
├── Metric enrichment
└── Activity modelling

        ↓

Gold Layer
│
├── Health metrics
├── Recovery analytics
├── Training load analytics
├── Performance indicators
└── Reporting datasets

        ↓

Analytics & Applications
│
├── Power BI dashboards
├── Exploratory analysis
├── Injury and recovery investigations
└── Readiness scoring experiments
```

---

## Planned Deliverables

### Phase 1 - Data Foundation

- Data inventory
- Data dictionary
- Bronze / Silver / Gold architecture
- Data quality assessment

### Phase 2 - Historical Analytics

- Longitudinal health trends
- Activity distribution analysis
- Recovery and training load investigation
- Performance change analysis

### Phase 3 - Dashboard Development

- Health overview
- Activity insights
- Recovery monitoring
- Performance tracking

### Phase 4 - Decision Support

- Readiness score prototype
- Recovery assessment logic
- Streamlit application experiments

---

## Technology Stack

- Python
- Pandas
- Databricks
- Delta Lake
- SQL
- Power BI
- Streamlit

---

## Project Status

🚧 In Progress

Current focus: exploring raw Huawei Health exports, building the data inventory and designing the initial data model.
