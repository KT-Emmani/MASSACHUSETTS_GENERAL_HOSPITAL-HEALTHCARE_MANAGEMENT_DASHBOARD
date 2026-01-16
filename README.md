# Massachusetts General Hospital - Patient & Financial Dashboard

## Table of Contents

- [Project Overview](#project-overview)

- [About Dataset](#about-dataset)

- [Tools Used](#tool-used)

- [Exploratory Data Analysis](exploratory-data-analysis)

- [Dashboard & Key Features](#dashboard-&-key-features)

- [Value Delivered](#value-delivered)

- [Skills Demostrated](#skills-delivered)




## Project Overview
This project involved designing and developing an end-to-end analytics solution for Massachusetts General Hospital to provide actionable insights into patient demographics, hospital encounters, procedures, readmissions, and financial performance. The goal was to transform raw hospital data into intuitive, executive-ready dashboards that support clinical, operational, and financial decision-making.

The solution consists of four interactive dashboards that offer both high-level summaries and detailed, patient-level views.


## About Dataset
This is a synthetic data on 974 patients of Massachussets General Hospital from 2011-2022, including information on patient demographics, insurance coverage, and medical encounters & procedures.

The dataset is a CSV file and contains 5 tables namely,
 1. Data Dictionary
 2. Encounters (contains 27,891 rows)
 3. Organization (contains 1 row)
 4. Patients (contains 1,000 rows)
 5. Payers (contains 10 rows)
 6. Procedures (contains 47,701 rows)

Dataset can be found in Maven Analytics: [download](https://mavenanalytics.io/data-playground/hospital-patient-records)

## Tools Used
- Excel & SQL - Data Cleaning & Manipulation

- Power Bi - Visualization


## Exploratory Data Analysis
The dataset captures hospital operations across patients, encounters, procedures, insurance coverage, and financial transactions over a one-year period.

### Core Metrics Observed

- Total Patients: 974
- Total Encounters: 27,891
- Total Procedures: 47,701
- Readmitted Patients: 854
- Total Billings: $101.51M
- Total Claims: $52.26M
- Total Coverage: $31.10M
- Unresolved Payments: $21.16M

The data is structured around time (monthly & weekly), encounter class, patient demographics, and payer information, enabling multi-dimensional analysis.

### Patient Demographics Analysis

#### Gender Distribution
- Male: 50.72% (494)
- Female: 49.28% (480)

📌 Insight: Gender distribution is balanced, indicating minimal gender bias in patient intake.

#### Age Distribution
- Majority of patients fall within 61–75 and 76–120 age groups.
- Average patient age: 73 years.

📌 Insight: The hospital predominantly serves an elderly population, suggesting higher demand for chronic care, follow-ups, and repeat encounters.

#### Race Distribution

- White patients make up the majority with a total number of 680 patients.
- Minority groups (Black, Asian, Hispanic, Native) represent significantly smaller proportions.

📌 Insight: Demographic skew may indicate geographic population patterns or potential access disparities worth deeper investigation.

### Encounter & Procedure Analysis

#### Monthly Trends
- Encounters and procedures remain consistently high throughout the year.
- Peaks observed around March, July, and October.
- Procedures consistently exceed encounters, indicating multiple procedures per visit.

📌 Insight: Stable utilization suggests predictable operational demand with mild seasonal variation.

#### Encounter Class Distribution

Top encounter classes by volume:

- Ambulatory - 12,537 encounters
- Outpatient - 6,300 encounters 
- Urgent Care - 3,666 encounters
- Emergency - 2,322 encounters
- Wellness - 1,931 encounters
- Inpatient - 1,135 encounters

📌 Insight: The hospital functions primarily as an outpatient and ambulatory care center, reducing inpatient congestion but increasing high-frequency visits.


#### Weekly Encounter Patterns

- Ambulatory and outpatient encounters dominate weekly volume.
- Emergency and inpatient encounters remain comparatively stable.

📌 Insight: Weekly patterns suggest staffing and resource planning can be optimized around ambulatory demand.

### Readmission Analysis

- Readmitted Patients - 854 (88% of total patients).
- Readmissions contribute significantly to repeat encounters and billing volume.

📌 Insight: High readmission rate may point to:
   - Chronic disease prevalence.
   - Gaps in post-discharge care.
   - Opportunities for preventive intervention programs.

### Insurance & Payer Analysis

#### Insurance Coverage
- No Insurance cover represents the largest category.
- Followed by Medicare and Medicaid.
- Private insurers contribute smaller shares.

📌 Insight: Heavy reliance on public insurance and uninsured patients increases financial risk and unresolved claims.

#### Top Payers by Claims
- Medicare and Medicaid generate high claim volumes but lower reimbursement rates.
- Uninsured patients contribute minimal payment despite high service utilization.

📌 Insight: Payer mix directly impacts cash flow and claim resolution timelines.

### Financial Analysis

#### Billing Overview
- Total Bill: $101.51M
- Total Claims: $52.26M
- Total Coverage: $31.10M
- Unresolved Payments: $21.16M

📌 Insight: Over 20% of billed amounts remain unresolved, posing a major revenue leakage risk.

#### Billing by Encounter Class
- Ambulatory & Outpatient encounters generate the highest billing.
- Inpatient and Emergency encounters have higher cost per visit but lower volume.

📌 Insight: High-volume, low-margin services dominate revenue streams.

#### Readmission Financial Impact
- One-time patients account for a large share of total billing - 101.51m (50.1%).
- Readmitted patients contribute comparatively less revenue - 101.1m (49.9%).

📌 Insight: Reducing readmissions could significantly improve cost efficiency and patient outcomes.

### EDA Summary & Business Implications

#### Key Findings
- Elderly patients dominate hospital utilization.
- Ambulatory and outpatient encounters drive volume and revenue.
- Readmissions significantly affect operational load and finances.
- Insurance mix creates financial risk due to high uninsured and public payer reliance.

#### Opportunities Identified
- Readmission reduction programs.
- Preventive care for high-risk age groups.
- Insurance optimization and claim follow-up strategies.
- Staffing optimization based on encounter class trends.

## Dashboard & Key Features

### Patient Overview Dashboard
Provides a snapshot of hospital activity and patient distribution:

- Total patients, encounters, procedures, and readmissions

- Monthly trends of encounters vs. procedures

- Patient breakdown by gender, race, and age group

- Encounters categorized by encounter class (Ambulatory, Outpatient, Emergency, Inpatient, etc.)

#### 🎯Impact: 
  Enables hospital leadership to quickly assess patient volume trends and population demographics.


<img width="2408" height="1471" alt="Paitent Overview" src="https://github.com/user-attachments/assets/29a8ff5f-1dbc-4ce2-bd9e-0a48299f6d6e" />



### Patient Insights Dashboard

Focuses on utilization and operational efficiency:

- Average length of encounters and procedures

- Average patient age and patient status (alive vs. deceased)

- Encounter trends by type and class (weekly and monthly)

- Most frequent encounter types and procedures

- Insurance provider analysis, highlighting coverage gaps

#### 🎯Impact: 
 Helps operations teams identify high-demand services, utilization patterns, and insurance-related risks.

 
<img width="2419" height="1471" alt="Patient Insight" src="https://github.com/user-attachments/assets/82144784-f86b-4033-b533-a0beb27cfb75" />


### Patient Information Dashboard

Delivers a patient-level drill-down view:

- Individual patient demographics and encounter history

- Encounter class distribution (ambulatory vs. outpatient)

- Procedure count, time spent, and total claim cost

- Monthly encounter and procedure activity

### 🎯 Impact: 
 Supports clinical and administrative staff in reviewing patient histories and cost profiles efficiently.
 
 
 <img width="2441" height="1468" alt="Gender Info" src="https://github.com/user-attachments/assets/81e8c140-dfdf-4fbb-ba8a-163bf5bf2eab" />



<img width="2424" height="1465" alt="Encounter" src="https://github.com/user-attachments/assets/a523a1f8-94e8-42e4-ba42-0509db14b117" />


### Financial Insights Dashboard

Analyzes hospital revenue and billing performance:

- Total billings, claims, payer coverage, and unresolved payments

- Monthly billing trends

- Claims distribution by encounter class

- Top insurance payers by total claims and payments received

- Readmission-related billing impact

#### 🎯 Impact: 
 Enables finance teams to monitor revenue streams, identify unpaid claims, and evaluate payer performance.

 
<img width="2442" height="1473" alt="Financial" src="https://github.com/user-attachments/assets/523baa52-4fd4-4d11-b5c4-dd46b8e250e0" />



## Value Delivered

- Centralized patient, operational, and financial data into a single analytics platform.

- Improved visibility into hospital performance and patient care trends.

- Enabled data-driven decisions for resource allocation, cost control, and patient management.

- Demonstrated strong capabilities in data modeling, dashboard design, and healthcare analytics.

## Skills Demonstrated

- Healthcare data analysis.

- Data modeling and KPI development.

- Interactive dashboard design in Power BI.

- Translating complex datasets into executive-level insights.

- Business storytelling with data.
