# Student-Mental-Health-Analysis
An end-to-end Excel analysis of student burnout factors using Kaggle data.

Project Overview
This project analyzes a dataset of 1,000+ students (sourced from Kaggle) to identify the core drivers of academic burnout and mental health risks. Using Microsoft Excel and Power Query, I transformed raw survey data into an interactive dashboard that highlights the relationship between lifestyle habits (sleep, study hours) and mental well-being.

Technical Workflow
1. Data Cleaning & Preprocessing (Power Query)
Standardization: Renamed truncated headers and standardized categorical values (e.g., Gender, Risk Levels).
Null Handling: Identified missing values in clinical scores and applied median imputation to maintain data integrity.
Data Types: Validated numerical fields (Age, Sleep Hours) to ensure compatibility with Pivot Table calculations.

2. Data Modeling & Feature Engineering
Composite Mental Health Index: Created a custom calculated column to aggregate Anxiety, Depression, and Stress levels into a single metric (0-10 scale).
Risk Tiering: Developed logic to "bin" students into four categories: Low, Moderate, High Risk, and Critical based on the Composite Index.
Sleep Quality Logic: Categorized sleep hours into "Deprived" (<6hrs) vs. "Sufficient" to enable comparative analysis.

3. Key Research Questions
The Sleep Gap: Does sleep deprivation directly correlate with higher burnout scores?
Pressure Points: Which external factor (Financial Stress vs. Family Expectations) has a higher impact on mental health?
The Academic Threshold: Is there a "breaking point" where increased study hours lead to diminishing returns in mental stability?

Author: kelvinsindo
Tools Used: Microsoft Excel, Power Query, Pivot Tables
Data Source: Kaggle Student Mental Health Dataset
