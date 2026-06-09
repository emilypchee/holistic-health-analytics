# Holistic Health Analytics

![Dashboard 1 Overview](images/holistic_health_analytics_dashboard_1.png)
![Dashboard 2 Overview](images/holistic_health_analytics_dashboard_2.png)
![Dashboard 3 Overview](images/holistic_health_analytics_dashboard_3.png)

## Overview
The Holistic Health Analytics dashboard is a healthcare performance intelligence system designed to monitor patient outcomes, clinical operations, and quality of care across the care continuum.

It provides visibility into:
- Patient encounters and utilization
- Diagnosis distribution and disease burden
- Lab result abnormalities and clinical risk signals
- Care delivery performance (length of stay, no-show rates)
- Patient satisfaction and experience scores
- Operational efficiency and monthly trends

through healthcare analytics principles commonly used in clinical reporting systems, population health dashboards, and hospital performance management platforms.

## Business Question
> *"What are the key drivers of variation in patient utilization, clinical outcomes, and operational performance across time, diagnosis groups, and service lines?"*

## Dashboard Objectives
1 · Utilization, Clinical Patterns & Risk Signals
- What is the total volume of patient encounters and how does it trend over time?
- How is encounter volume distributed across diagnosis categories and conditions?
- Which diagnoses are the primary drivers of utilization?
- How is clinical demand distributed across disease groups?
- What proportion of lab results are abnormal, and how does this compare to defined thresholds?
- Which test panels contribute most to abnormal findings and clinical risk signals?
- Where are abnormal results concentrated across clinical domains?

2 · Operational Performance & Patient Experience
- What is the average length of inpatient stay and how does it compare to benchmarks?
- What is the appointment no-show rate and how does it trend over time?
- How do operational metrics vary across encounter types and time periods?
- What is the overall patient satisfaction score and its month-over-month trend?
- How do operational efficiency metrics correlate with patient experience outcomes?

## Data Model
Built on a database (15 tables).
See [data/data-dictionary.md](data/data-dictionary.md) for
column-level documentation.

## Tools Used
- **Power BI Desktop** — data model with 26 relationships, DAX measures, and report designs
- **DAX** — 38 custom measures for revenue, ranking, and time intelligence

## How to Use This File
1. Download `report/holistic_health_analytics.pbix`
2. Open in Power BI Desktop (free download from Microsoft)
3. The embedded dataset loads automatically

## About
Built as part of my ongoing journey with data storytelling.
[LinkedIn](https://www.linkedin.com/in/emilypchee/) |
[Portfolio](https://seemly-existence-5eb.notion.site/You-got-questions-Emily-Chee-got-answers-02d623d6b64c496e818930e9b725b52c)
