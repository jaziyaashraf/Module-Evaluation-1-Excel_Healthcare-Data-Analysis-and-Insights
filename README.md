# Healthcare Data Analytics Using Excel

## Project Overview
Analyzed healthcare data using Excel 2019 to explore patient health conditions and medical charges.

## 1. Data Cleaning
- Identified missing values marked with '?'.
- Replaced missing months with September and years with the rounded average.
- Filled missing smoker, Hospital tier, and City tier values using the mode.
- Handled missing State ID values.

## 2. Data Transformation
- Split names into Title, First Name, and Last Name.
- Converted major surgeries into numeric values.
- Checked inconsistencies in Heart Issues and smoker columns.
- Classified BMI into Underweight, Normal Weight, Overweight, and Obesity.
- Classified HbA1c into Normal, Prediabetes, and Diabetes.
- Combined year, month, and date into Date of Birth.
- Calculated age as of 8 June 2023.
- Formatted charges as currency.

## 3. Excel Formulas Used
- **VLOOKUP:** Combined three tables using Customer ID.
- **IF:** Classified weight and diabetes status.
- **DATEDIF:** Calculated age.
- **COUNTIF:** Counted patients meeting specific conditions.
- **SUM:** Calculated total major surgeries.
- **AVERAGE:** Calculated average HbA1c and charges.
- **MIN/MAX:** Identified minimum and maximum values.

## 4. Data Analysis
- Compared cancer history among smokers and non-smokers.
- Analyzed surgeries and average HbA1c by transplant history.
- Compared charges by weight and diabetes status.
- Compared average charges across hospital tiers and states.
- Explored relationships between age, BMI, HbA1c, and healthcare charges.

## 5. Dashboard
Created PivotTables, charts, and KPIs in an interactive dashboard. Added Weight Status and Diabetes Status slicers to filter and compare patient health indicators and medical charges.
