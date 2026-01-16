# Massachusetts General Hospital - Patient & Financial Dashboard

## Table of Contents

- [Project Overview](#project-overview)

- [About Dataset](#about-dataset)

- [Tools Used](#tool-used)

- [Dashboard & Key Features](#dashboard-&-key-features)

- [Key Strategic Insights](#key-strategic-insights)




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

## Exploratory Data Analysis

### 📊 1. Overall Business Performance

First Quarter:

- Total Sales = $ 159.22k
  
- Total Orders = 5,343
  
- Total Quantity Sold = 12,097


### 🍽️ 2. Menu Category Performance

#### Sales by Category: 

- Italian is the top-selling category ($ 49.46K).

- Asian follows closely ($ 46.72K).

- Mexican ($ 34.80K) and American ($ 28.24K) trail behind.


#### Orders by Category:

- Asian leads in order volume (2,635 orders)

- Italian (2,292 orders)

- Mexican (2,266 orders)

- American (2,152 orders)


#### Quantity Sold by Category:

- Asian dishes sold the most units (3,470 dishes)

- Italian (2,948 dishes)

- Mexican (2,945 dishes)

- American (2,734 dishes)

➡️ Italian is the top performer in both sales and orders, but Asian wins in total quantity sold — suggesting many lower-priced, higher-frequency dishes.


### 🍛 3. Top 5 Performing Dishes

#### By Sales:

- Korean Beef Bowl — $ 10.55K

- Spaghetti & Meatballs — $ 8.44K

- Tofu Pad Thai — $ 8.15K

- Cheeseburger — $ 8.13K
  
- Hamburger — $ 8.05K


#### By Orders:

- Hamburger — 595

- Korean Beef Bowl — 566

- Cheeseburger — 559

- Tofu Pad Thai — 542

- Spaghetti & Meatballs — 460



#### By Quantity Sold:

- Hamburger — 622

- Korean Beef Bowl — 588

- Cheeseburger — 583

- Tofu Pad Thai — 562

- Spaghetti & Meatballs — 470

➡️ Hamburger is the most consistently ordered and consumed dish, though it is not the highest revenue generator.

➡️ Korean Beef Bowl generates the most revenue, suggesting a higher price point.



### ⏰ 4. Time-Based Buying Patterns


#### Sales Patterns

 Highest total sales occur between:

 -> 12 pm – 12:59 pm (lunch rush)

 -> 5 pm – 6:59 pm (dinner rush)

Sales dip sharply late at night (after 9 pm).


#### Orders by Time

 Peak order volumes are:

 -> 12 pm – 12:59 pm (most active hour)

 -> 5 pm – 6 pm

 -> 6 pm – 7 pm


#### Quantity Sold by Time

 Mirrors order patterns:

 -> 12 pm – 2 pm dominates sales and order volume.

 -> Moderate dinner spike again around 5 pm – 7 pm.

➡️ Midday lunch hours are the most profitable and busiest. Dinner is the second major peak.



### 💲 5. Price Distribution Insights

Most items sold fall in the $12 – $18 price range.

-> $12 - $15 range has the highest count (4,219).

-> $15 - $18 range next (3,497 ).

➡️ Your pricing sweet spot is between $12 – $18 — this is where customers buy the most.


## Key Strategic Insights


1️⃣ Optimize Around Peak Hours

Focus staffing, inventory, and promotions around 12–2 pm and 5–7 pm.


2️⃣ Leverage High-Performing Categories

Italian and Asian drive most revenue/volume.

Consider:

Adding variations to top categories

Running promotions to lift the weaker American segment


3️⃣ Flagship Items Identified

Korean Beef Bowl (high revenue dish)

Hamburger (high volume dish)

Promote as signature dishes or bundle them.


4️⃣ Pricing Strategy is Working

Majority of orders fall in the $12 – $18 window—keep core menu pricing here.
