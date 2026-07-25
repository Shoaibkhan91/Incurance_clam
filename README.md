#  Insurance Claims Analytics using Python

##  Project Overview

This project focuses on analyzing insurance claims data to understand customer behavior, claim patterns, fraud detection, and business performance. Using Python, I performed data cleaning, exploratory data analysis (EDA), feature engineering, visualization, and statistical hypothesis testing to generate actionable insights for insurance business decision-making.

The project simulates a real-world insurance analytics use case by integrating customer information with insurance claim transactions to create a comprehensive 360-degree customer view.

---

##  Business Objective

The objective of this project is to help the insurance company:

- Understand customer claim behavior
- Identify fraudulent claims
- Analyze claim trends
- Evaluate customer demographics
- Measure claim performance across different customer segments
- Support data-driven decision making using statistical analysis

---

##  Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Jupyter Notebook

---

##  Dataset

The project uses two datasets:

- **Customer Data** – Customer demographic information
- **Claims Data** – Insurance claim transactions

Both datasets were merged to create a 360-degree customer analytics dataset.

---

#  Project Workflow

## 1️ Data Integration

- Imported Customer and Claims datasets
- Merged datasets using Customer ID
- Created a unified customer view

---

## 2️ Data Audit

Performed data quality assessment by:

- Checking data types
- Validating business significance
- Identifying datatype mismatches
- Correcting incorrect data formats

---

## 3️ Data Cleaning

Performed extensive preprocessing including:

- Converted claim amount into numeric format
- Removed currency symbols
- Missing value treatment
- Duplicate removal
- Latest claim selection for duplicate customers
- Data type conversion

---

## 4️ Feature Engineering

Created new business features including:

- Customer Age
- Age Categories
  - Children
  - Youth
  - Adult
  - Senior
- Police Reporting Alert Flag
- Fraud Indicators

---

## 5️ Exploratory Data Analysis (EDA)

Performed comprehensive exploratory analysis on:

###  Customer Analysis

- Customer Segmentation
- Customer Demographics
- Gender Distribution
- Age Group Distribution

---

###  Claim Analysis

- Average Claim Amount
- Total Claim Amount
- Monthly Claim Trend
- Incident Cause Analysis
- State-wise Claims
- Segment-wise Claims

---

###  Fraud Analysis

- Fraudulent vs Non-Fraudulent Claims
- Fraud Analysis by Age Group
- Fraud Analysis by Gender
- Fraud Trend Analysis

---

###  Insurance Performance Analysis

- Claims by Customer Segment
- Claims by Gender
- Claims by Age Category
- Claims by Incident Cause
- Driver-related Claims
- Monthly Claim Performance

---

##  Data Visualization

Created various business visualizations including:

- Bar Charts
- Pie Charts
- Line Charts
- Count Plots
- Box Plots
- Faceted Bar Charts
- Monthly Trend Charts

---

##  Statistical Analysis

Performed hypothesis testing to validate business assumptions.

### Statistical Tests Used

- Independent T-Test
- Chi-Square Test
- One-Sample T-Test
- One-Way ANOVA
- Correlation Analysis

---

##  Business Questions Answered

The project addresses several real-world business problems, including:

- Average claim amount by customer segment
- Total claim amount by incident cause
- Driver-related insurance claims
- Top claim categories
- Monthly claim trends
- Fraudulent claim analysis
- Customer demographic analysis
- Gender-wise claim comparison
- Age group claim comparison
- Relationship between age category and customer segment
- Relationship between policy claims and claim amount
- Comparison of current claim amount against historical benchmarks

---

##  Key Performance Indicators (KPIs)

- Total Customers
- Total Claims
- Average Claim Amount
- Total Claim Amount
- Fraud Claim Rate
- Average Claim by Gender
- Average Claim by Segment
- Average Claim by Age Group
- Monthly Claim Trend
- Driver-related Claims
- Customer Segment Performance

---

##  Key Business Insights

- Identified customer segments with the highest claim amounts.
- Analyzed fraudulent claim patterns across age groups.
- Compared claim behavior between male and female customers.
- Evaluated customer claim trends over time.
- Determined high-risk customer groups.
- Measured insurance claim performance across customer segments.
- Validated business assumptions using statistical hypothesis testing.

---

##  Python Libraries Used

```python
import pandas as pd
import numpy as np

import matplotlib.pyplot as plt
import seaborn as sns

import scipy.stats as stats

from datetime import datetime
```

---

##  Skills Demonstrated

- Python Programming
- Pandas
- NumPy
- Data Cleaning
- Data Wrangling
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Data Visualization
- Statistical Analysis
- Hypothesis Testing
- Customer Analytics
- Insurance Analytics
- Business Intelligence

---

##  Project Structure

```
Insurance-Claims-Analytics/
 Dataset/
 Customer_Data.csv
 Claims_Data.csv
 Notebook
 Insurance_Claims_Analytics.ipynb

```

---


##  Learning Outcomes

Through this project, I gained practical experience in:

- Insurance data analysis
- Customer analytics
- Data preprocessing
- Exploratory Data Analysis (EDA)
- Feature engineering
- Fraud detection analysis
- Statistical hypothesis testing
- Business reporting
- Data visualization
- Data-driven decision making

---

##  Author

**Shoaib Khan**

 Email: SHOAIB913599@gmail.com

 LinkedIn: https://www.linkedin.com/in/shoaib-khan-1b16232b2

 GitHub: https://github.com/your-github-username

---

##  Support

If you found this project useful, please consider giving it a  Star.

---

##  Keywords

Python, Insurance Analytics, Claims Analytics, Customer Analytics, Fraud Detection, Pandas, NumPy, Matplotlib, Seaborn, Hypothesis Testing, EDA, Statistical Analysis, Data Visualization, Business Intelligence, Data Analytics.
