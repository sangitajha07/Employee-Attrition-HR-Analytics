# Employee Attrition & HR Analytics Dashboard

## Project Overview
This project is an HR Analytics Dashboard created using Power BI to analyze employee attrition and workforce trends.

## Objectives
- Analyze employee attrition
- Calculate attrition rate
- Analyze attrition by department and job role
- Understand the impact of overtime
- Analyze job satisfaction
- Analyze employee age, salary and tenure
- Create an interactive HR dashboard

## Tools Used
- Power BI
- DAX
- Microsoft Excel
- Data Analysis
- Data Visualization

## Dataset
The dataset contains 500 employee records with information about:

- Employee ID
- Age
- Gender
- Department
- Job Role
- Education
- Years at Company
- Monthly Salary
- Overtime
- Job Satisfaction
- Attrition

## Key KPIs

- Total Employees: 500
- Total Attrition: 79
- Attrition Rate: 15.80%
- Average Salary: 82.28K
- Average Age: 40.10
- Average Years at Company: 9.45

## Dashboard

### HR Overview
The dashboard includes:
- Employee KPIs
- Attrition by Department
- Attrition by Job Role
- Attrition by Age Group
- Attrition by Gender
- Attrition by Overtime
- Attrition by Tenure

### Detailed Analysis
- Salary vs Age
- Job Satisfaction vs Attrition
- Education vs Attrition
- Tenure Analysis
- Overtime Impact
- Job Role Analysis

## DAX Measures

### Total Employees
```DAX
Total Employees =
DISTINCTCOUNT(HR_Data[EmployeeID])
