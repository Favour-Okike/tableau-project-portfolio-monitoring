# Project Portfolio Monitoring Dashboard (Tableau)

## Overview

This project presents an end-to-end Tableau analytics solution for monitoring project portfolio performance across multiple regions.

The solution was developed using Tableau Prep and Tableau Desktop to transform raw project data into interactive dashboards that support executive decision-making, risk monitoring, and project performance analysis.

The dashboards track project performance across three key dimensions:

* Cost Performance
* Schedule Performance
* Deliverables Performance

Alert mechanisms were implemented to identify projects that deviate significantly from planned targets.

---

## Live Interactive Dashboard

View the interactive Tableau Public dashboard:

🔗 https://public.tableau.com/app/profile/favour.okike/viz/Tableaufinalprojectworkbook/RegionalPerformanceMonitoring

---

## Dashboard Preview

### Executive Portfolio Overview

*Insert screenshot here*

This dashboard provides a high-level portfolio view including:

* Total Projects
* Alerted Phases
* Alert Rate
* Average Cost Variance
* Average Duration Variance
* Average Deliverables Variance

---

### Project Performance Analysis

*Insert screenshot here*

This dashboard compares project performance across project types and highlights:

* Cost Variance by Project Type
* Duration Variance by Project Type
* Deliverables Variance by Project Type
* Regional Alert Distribution

---

### Regional Performance Monitoring

*Insert screenshot here*

This dashboard provides geographic analysis of project performance using:

* Interactive World Map
* Country-Level Monitoring
* Project Type Filters
* Phase Filters
* Time Filters

---

### Risk Prioritization Dashboard

*Insert screenshot here*

This dashboard identifies:

* Top Risk Countries
* Top Risk Projects
* High-Risk Areas Requiring Management Attention

---

## Data Preparation

Data preparation was performed using Tableau Prep.

Key steps included:

1. Importing source datasets
2. Cleaning and validating fields
3. Standardizing data types
4. Joining project and country data
5. Creating analytical fields
6. Exporting a consolidated dataset for Tableau Desktop

---

## Key Calculations

### Cost Variance %

```text
(Actual Cost - Planned Cost) / Planned Cost
```

### Duration Variance %

```text
(Actual Duration - Planned Duration) / Planned Duration
```

### Deliverables Variance %

```text
(Actual Deliverables - Planned Deliverables) / Planned Deliverables
```

### Alert Logic

Alerts are triggered whenever:

```text
ABS(Variance) >= 15%
```

---

## Key Performance Indicators (KPIs)

The solution includes:

* Total Projects
* Alerted Phases
* Alert Rate
* Average Cost Variance %
* Average Duration Variance %
* Average Deliverables Variance %

---

## Key Insights

Analysis of the project portfolio revealed:

* Significant cost overruns within IT projects
* Greater schedule delays in IT initiatives compared with marketing projects
* Deliverable completion rates below planned targets
* Higher concentrations of alerts within specific geographic regions
* Clear identification of high-risk countries and projects requiring intervention

---

## Files Included

### Tableau Workbook

```text
Tableau final project workbook.twbx
```

### Tableau Prep Workflow

```text
Tableau final project prep flow.tfl
```

### Prepared Dataset

```text
Tableau final project output data.csv
```

### Project Documentation

```text
Tableau_Project_Summary_Guide.pdf
```

---

## Skills Demonstrated

* Tableau Desktop
* Tableau Prep
* Data Cleaning
* Data Modeling
* Dashboard Design
* KPI Development
* Business Intelligence
* Data Visualization
* Risk Analysis
* Project Portfolio Analytics

---

## Author

**Favour Okike**

Master's in Data Science & Business Analytics
