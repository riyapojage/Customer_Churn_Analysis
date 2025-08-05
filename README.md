# Churn Analysis Project

## Overview

This project focuses on identifying patterns and predicting customer churn for a telecom firm. The process involves extracting, transforming, and visualizing data, as well as building a predictive model using machine learning. The approach outlined can be applied across industries to help businesses retain their customers.

## Table of Contents

1. [Project Overview](#overview)
2. [Technologies Used](#technologies-used)
3. [Steps Involved](#steps-involved)
   - [Step 1: ETL Process Using SQL Server](#step-1-etl-process-using-sql-server)
   - [Step 2: Power BI Data Transformation](#step-2-power-bi-data-transformation)
   - [Step 3: Power BI Metrics](#step-3-power-bi-metrics)
   - [Step 4: Power BI Visualization](#step-4-power-bi-visualization)
   - [Step 5: Predicting Customer Churn with Random Forest](#step-5-predicting-customer-churn-with-random-forest)
4. [Conclusion](#conclusion)

## Technologies Used

- **SQL Server Management Studio (SSMS)**
- **Power BI**
- **Python (for machine learning model)** 
- **Random Forest Classifier**

## Steps Involved

### Step 1: ETL Process Using SQL Server

The customer data is loaded, explored, cleaned, and transformed using SQL Server. Key tasks include:

- **Database Creation:** Load customer data into a `db_Churn` database.
- **Data Exploration:** Identify patterns such as gender distribution, contract types, etc.
- **Data Cleaning:** Handle missing values and prepare the data for further analysis.
- **View Creation:** Facilitate data extraction for reporting and machine learning.

### Step 2: Power BI Data Transformation

Data is transformed in Power BI to prepare for analysis and visualization:

- **New Columns:** Create calculated columns for churn status and monthly charge ranges.
- **Grouping:** Group age and tenure for easier analysis.
- **Unpivot Services:** Reshape service usage data for visual representation.

### Step 3: Power BI Metrics

Power BI helps calculate and display key metrics:

- **Total Customers:** Active customers in the dataset.
- **New Joiners:** Recently acquired customers.
- **Churn Rate:** Percentage of customers who churned.
- **Churn Breakdown
