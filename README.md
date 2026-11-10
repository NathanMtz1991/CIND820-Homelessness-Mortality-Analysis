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
│   ├── Homeless_Deaths_By_Month.csv
│   ├── Homeless_Deaths_By_Cause.csv
│   ├── Homeless_Deaths_By_Demographics.csv
│   └── Homeless_Deaths_By_Setting.csv
│
├── notebooks/
│   └── M3_Part3_Analysis.ipynb
│
├── reports/
│   ├── Nathan_Martinez_Milestone1.pdf
│   ├── Milestone_2_Nathan_Martinez.pdf
│   ├── M3_Part1_Data_Analysis_Preparation_Report.pdf
│   ├── M3_Part2_Model_Development_Report.pdf
│   └── M3_Part3_Reproducibility_Report.pdf
│
├── figures/
│   ├── Figure_01_Annual_Deaths.png
│   ├── Figure_02_Monthly_Deaths.png
│   ├── ...
│   └── Figure_15_Deaths_vs_Newly_Identified.png
│
└── outputs/
    ├── Correlation_Table.csv
    ├── Transformation_Summary.csv
    └── Model_Performance.csv
```

---

# Analytical Workflow

The project follows the analytical workflow established during Milestones 1 and 2.

1. Data Acquisition
2. Data Profiling
3. Data Cleaning
4. Data Integration
5. Exploratory Data Analysis
6. Descriptive Statistics
7. Outlier Detection
8. Correlation Analysis
9. Feature Engineering
10. Predictive Modeling
11. Model Evaluation
12. Findings and Recommendations

---

# Models Implemented

## Linear Regression

A baseline predictive model used to estimate mortality levels from shelter-system indicators.

## Random Forest Regression

A tree-based ensemble model used to evaluate whether non-linear relationships improve predictive performance.

---

# Evaluation Metrics

Model performance was evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

These metrics were used to compare predictive accuracy between Linear Regression and Random Forest Regression models.

---

# Reproducibility Instructions

## Software Requirements

- Python 3.x
- Google Colab
- Jupyter Notebook

## Required Python Libraries

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Running the Analysis

1. Download or clone this repository.
2. Open the notebook located in the notebooks folder.
3. Upload all required datasets from the data folder when prompted.
4. Run all notebook cells sequentially from top to bottom.
5. Generated figures, tables, and model outputs will reproduce the results presented in the project reports.

---

# Key Deliverables

- Milestone 1 Project Design Report
- Milestone 2 Technical Design Report
- Milestone 3 Part 1 Data Analysis Report
- Milestone 3 Part 2 Modeling Report
- Milestone 3 Part 3 Reproducible Analytics Notebook
- Supporting datasets
- Analytical outputs and visualizations

---

# License

This project was completed for academic purposes as part of the CIND820 Applied Data Science course.

Datasets remain the property of the City of Toronto Open Data Portal and are used under their applicable open data licensing terms.
