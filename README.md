# NHS Healthcare Services Analysis Dashboard

## Project Overview

This repository contains Tableau dashboards analyzing NHS England's healthcare services, focusing on outpatient, inpatient, and mental health services. The project aims to provide insights into one of the world's largest publicly funded health systems, offering valuable data for both international observers and NHS country directors.

## Dashboards

1. NHS Dashboard for International News Organisation
2. Dashboard for Country Directors NHS UK

You can view them here:

[NHS Data Analysis Dashboards](https://nidhid54.github.io/NHS-Services-Analysis/tableau_dashboards.html)

## Data Sources

The data used in these dashboards was obtained from official NHS sources:

1. Outpatient Data:
   [Hospital Outpatient Activity 2022-23](https://digital.nhs.uk/data-and-information/publications/statistical/hospital-outpatient-activity/2022-23)

2. Inpatient Activity:
   [Hospital Admitted Patient Care Activity 2021-22](https://digital.nhs.uk/data-and-information/publications/statistical/hospital-admitted-patient-care-activity/2021-22)

3. Mental Health Data:
   [NHS Mental Health Dashboard](https://www.england.nhs.uk/publication/nhs-mental-health-dashboard/)

## Data Preparation Process

1. Cleaning:
- Removed redundant entries
- Standardized formatting (date formats, numerical precision)
- Deleted unnecessary rows and columns
- Utilized Tableau's 'clean with data interpreter' for efficiency
2. Formatting:
- Implemented consistent naming conventions
- Converted data types as needed
- Created calculated fields (e.g., percentages, year-over-year changes)

## Visualizations
Dashboard 1 (International News Organization):
- Side-by-side bar chart: Mental health services comparison over time
- Treemap: Hierarchical view of finished consultant episodes
- Column chart: First attendances by Top 10 specialties 
- Pie chart: Breakdown of admission categories
- Line chart: Trends in missed appointments

Dashboard 2 (NHS Country Directors):
- Bubble chart: Quick identification of major hospital admission reasons
- Scatter graph: Regional comparison of outpatient activity over time
- Pie chart: Regional breakdown of critical care distribution
- Bar chart with line: Mental health funding trends and percentage changes

## Key Features
- Analysis of mental health services performance
- Outpatient and inpatient service distribution
- Top reasons for hospital admissions
- Regional comparisons of healthcare activity
- Trends in mental health funding

## Conclusion
This project demonstrates the transformation of complex NHS data into clear, actionable visualizations tailored to specific audience needs. The process emphasizes data integrity, relevance, and effective visual communication to support informed decision-making in healthcare.

## License
Shield: [![CC BY 4.0][cc-by-shield]][cc-by]

This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg

