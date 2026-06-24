# COPD-Patient-Profile-Dashboard

## Table of Contents

* [Project Overview](#project-overview)
* [Dashboard Features](#dashboard-features)
* [Key KPIs](#key-kpis)
* [Visualizations](#visualizations)
* [Insights](#insights)
* [Recommendations](#recommendations)

## Project Overview

This project presents an interactive Power BI dashboard developed to analyze Chronic Obstructive Pulmonary Disease (COPD) patient data. The dashboard provides insights into patient demographics, disease severity, lung function, exercise capacity, and comorbidities to support data-driven healthcare decision-making.

**The analysis focuses on:**

* Understanding the demographic profile of COPD patients
* Examining disease severity across gender and age groups
* Evaluating lung function indicators (FEV1 and FVC)
* Assessing patient mobility through 6-Minute Walk Test results
* Identifying the prevalence of common comorbidities
* Supporting evidence-based healthcare planning and reporting

## Tools Used

* Microsoft Power BI
* Microsoft Excel
* Power Query
* DAX

## Dataset Description

The dataset contains 101 COPD patient records and 24 healthcare-related variables, including demographic information, lung function test results, disease severity classifications, mobility assessments, and comorbidity indicators.

**Key variables include:**

* Age
* Gender
* Smoking Status
* COPD Severity
* FEV1 and FVC Lung Function Scores
* 6-Minute Walk Test (MWT)
* Diabetes
* Hypertension
* Ischemic Heart Disease (IHD)
* CAT, HAD, and SGRQ Assessment Scores

## Data Preparation

Main data preparation steps performed:

* Reviewed and validated healthcare records
* Handled missing values in mobility assessment variables
* Standardized categorical fields
* Created calculated measures for KPIs
* Developed relationships and DAX calculations for reporting
* Designed interactive filters and slicers for dashboard navigation

## Key KPIs

* Total Patients: 101
* Average Patient Age: 70 Years
* Male Patients: 64.36%
* Female Patients: 35.64%
* Moderate COPD Cases: 42.57%
* Severe COPD Cases: 26.73%
* Patients with At Least One Comorbidity: 36.63%
* Average 6-Minute Walk Test Distance: 399.11 Meters
* Average Predicted Lung Function (FEV1PRED): 58.58

## Visualizations

### Dashboard Overview

![COPD Dashboard](Dashboard_Screenshot.png)

### Key Dashboard Components

1. Patient Demographics Analysis
2. COPD Severity Distribution
3. Lung Function Comparison by Gender
4. Comorbidity Analysis
5. Exercise Capacity Assessment
6. Interactive KPI Monitoring
7. Severity and Age Group Filtering

## Insights

* The majority of COPD patients are male, representing 64.36% of the dataset.
* The average patient age is 70 years, indicating COPD predominantly affects older adults.
* Moderate COPD is the most common severity category, accounting for 42.57% of cases.
* Male patients demonstrate higher average FEV1 and FVC values than female patients.
* More than one-third of patients have at least one comorbidity, highlighting the need for integrated healthcare management.
* Diabetes is the most common comorbidity among COPD patients.
* The average 6-Minute Walk Test distance of 399.11 meters suggests reduced physical capacity among patients.

## Recommendations

* Strengthen early screening and monitoring programs for older adults.
* Focus awareness and prevention initiatives on high-risk populations.
* Implement integrated care approaches for patients with COPD and comorbid conditions.
* Expand pulmonary rehabilitation programs to improve patient mobility and quality of life.
* Utilize dashboard-driven reporting to support healthcare planning and resource allocation.
* Continue collecting additional clinical and environmental data for deeper analysis and improved decision-making.
