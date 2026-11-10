# CIND820 – Homelessness, Shelter Conditions, and Mortality Analysis

## Author

Nathan Martinez

## Project Overview

This project investigates the relationship between shelter-system conditions and mortality among shelter residents and people experiencing homelessness in Toronto.

The analysis combines multiple City of Toronto Open Data datasets to examine mortality trends, shelter occupancy pressures, homelessness indicators, housing outcomes, and demographic characteristics. Statistical analysis and predictive modeling are used to identify patterns associated with periods of elevated mortality and to evaluate whether shelter-system indicators can help explain mortality outcomes.

---

# Research Questions

## Research Question 1

What trends and patterns exist in deaths among shelter residents and people experiencing homelessness in Toronto over time?

## Research Question 2

How do mortality patterns correspond with shelter occupancy, shelter capacity utilization, active homelessness, housing placements, and shelter returns?

## Research Question 3

What demographic, environmental, and shelter-system characteristics appear most strongly associated with elevated mortality periods?

---

# Project Stages

## Milestone 1 – Project Design

- Professional context and problem definition
- Research question development
- Dataset identification and evaluation
- Data biography and ethics review
- Data quality monitoring strategy
- Proposed analytical pipeline

## Milestone 2 – Technical Design

- Data architecture planning
- Data integration strategy
- Variable selection
- Exploratory analysis framework
- Correlation analysis design
- Predictive modeling strategy
- Evaluation methodology

## Milestone 3 – Data Analysis and Modeling

### Part 1 – Data Analysis and Preparation

- Dataset profiling
- Data quality assessment
- Missing value review
- Duplicate detection
- Descriptive statistics
- Outlier analysis
- Exploratory data analysis
- Correlation analysis
- Data preparation and transformation

### Part 2 – Model Development and Evaluation

- Feature selection
- Modeling dataset creation
- Train/test split
- Linear Regression model
- Random Forest model
- Model evaluation
- Performance comparison
- Findings and limitations

### Part 3 – Reproducible Analytics Environment

- Jupyter Notebook implementation
- Reproducible workflow
- Repository documentation
- Version-controlled project structure
- Analytical outputs and reporting

---

# Data Sources

Datasets were obtained from the City of Toronto Open Data Portal.

## Primary Datasets

1. Toronto Shelter System Flow
2. Deaths of Shelter Residents
3. Deaths of People Experiencing Homelessness
4. Daily Shelter Overnight Service Occupancy and Capacity

## Supporting Data Files

- Homeless deaths by month
- Homeless deaths by cause
- Homeless deaths by demographics
- Homeless deaths by setting
- Shelter resident mean age statistics

---

# Repository Structure

```text
CIND820-Homelessness-Mortality-Analysis/

│
├── README.md
│
├── data/
│   ├── Deaths_of_Shelter_Residents.csv
│   ├── Toronto_Shelter_System_Flow.csv
│   ├── Daily_Shelter_Occupancy_Capacity.csv
│   ├── Homeless_Deaths
