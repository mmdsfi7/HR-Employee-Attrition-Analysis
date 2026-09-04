# HR Employee Attrition Analysis

## Project Overview

An end-to-end HR analytics project focused on understanding employee attrition, identifying key risk factors, and developing a practical employee risk framework to support proactive retention decisions.

The project analyzes employee-level HR data using Microsoft Excel and presents the findings through an interactive analytical dashboard, risk analysis tables, and business recommendations.

---

## Business Problem

Employee attrition can create significant costs through recruitment, onboarding, lost experience, and reduced productivity.

The objective of this project is to identify patterns associated with employee turnover and determine which employees may require greater retention attention.

Rather than focusing on a single variable, the analysis examines multiple employee and workplace characteristics and combines selected risk indicators into a Risk Score.

---

## Project Objectives

- Analyze overall employee attrition.
- Identify factors associated with higher attrition rates.
- Examine attrition across employee demographics, job characteristics, satisfaction, workload, and tenure.
- Develop an employee Risk Score based on multiple risk indicators.
- Identify high-risk employees using a Risk Score threshold of 4 or above.
- Build an interactive HR attrition dashboard.
- Translate analytical findings into actionable business recommendations.

---

## Dataset

The project uses an HR employee dataset containing information related to:

- Employee demographics
- Department and job role
- Job level
- Monthly income
- Job satisfaction
- Environment satisfaction
- Job involvement
- Overtime
- Work-life balance
- Tenure and years at company
- Attrition status

The dataset contains **1,470 employees**.

---

## Data Preparation

The data preparation process included:

- Reviewing the dataset structure
- Organizing employee-level variables
- Creating analytical groups such as Age Group and Tenure Group
- Reviewing attrition-related variables
- Developing risk indicators
- Creating a Risk Factor field
- Developing a Risk Score
- Separating high-risk employees for focused analysis
- Building summary tables and PivotTables for dashboard reporting

---

## Risk Framework

A Risk Score was developed by combining multiple employee-level risk indicators.

The framework considers factors including:

- Low Job Level
- Short Tenure
- Overtime
- Low Job Involvement
- Low Job Satisfaction
- Low Environment Satisfaction
- Poor Work-Life Balance

Employees with a **Risk Score ≥4** are classified as high-risk within this project.

This framework is intended as an analytical prioritization tool rather than a prediction model.

---

## Key Findings

### Attrition and Overtime

Employees working overtime show substantially higher attrition than employees who do not work overtime.

- Overtime: **30.53% attrition**
- No Overtime: **10.44% attrition**

### Job Involvement

Lower job involvement is associated with higher attrition.

- Job Involvement Level 1: **33.73%**
- Job Involvement Level 4: **9.03%**

### Job Satisfaction

Lower job satisfaction is associated with higher attrition.

- Job Satisfaction Level 1: **22.84%**
- Job Satisfaction Level 4: **11.33%**

### Job Role

Sales Representatives have the highest attrition rate among the analyzed job roles.

- Sales Representative: **39.76%**

### Risk Score

Attrition increases substantially at higher Risk Scores.

- Risk Score 4: **27.17%**
- Risk Score 5: **59.76%**
- Risk Score 6: **68.18%**
- Risk Score 7: **66.67%**

The slight decrease between Scores 6 and 7 indicates that the relationship is strong overall but is not perfectly monotonic at every score.

### High-Risk Employee Population

Using Risk Score ≥4 as the high-risk threshold:

- High-risk employees: **280**
- Share of workforce: **19.0%**

Within the high-risk population, the most prevalent risk factors include:

- Low Job Level: **77.5%**
- Low Environment Satisfaction: **61.4%**
- Short Tenure: **60.4%**

---

## Business Recommendations

Based on the analysis, the following actions are recommended:

1. **Prioritize high-risk employees**

   Use Risk Score ≥4 as a screening mechanism for proactive retention programs.

2. **Review overtime and workload**

   Monitor excessive overtime and workload pressure, particularly among employees with multiple concurrent risk factors.

3. **Strengthen career development**

   Create clearer career-development and promotion pathways for employees in lower job levels.

4. **Improve early-tenure support**

   Strengthen onboarding, manager support, and early-career engagement for employees with short tenure.

5. **Investigate Sales Representative attrition**

   Conduct role-specific analysis to better understand the retention challenges within Sales Representative positions.

6. **Improve employee involvement**

   Strengthen manager support, recognition, communication, and employee participation initiatives.

7. **Use satisfaction indicators as supporting signals**

   Job satisfaction and environment satisfaction should be used as supporting indicators within the broader risk framework rather than treated as standalone predictors.

---

## Dashboard

The Excel dashboard provides an interactive view of employee attrition and risk patterns.

The dashboard includes:

- Total Employees
- Attrition Rate
- Average Monthly Income
- Employees Left
- Overtime Rate
- High-Risk Employees
- Attrition Rate by Overtime
- Attrition Rate by Job Role
- Attrition Rate by Job Involvement
- Attrition Rate by Work-Life Balance
- Employees by Risk Score
- Attrition Rate by Risk Score
- Interactive slicers for filtering the analysis

---

## Tools & Skills

### Tools

- Microsoft Excel
- PivotTables
- PivotCharts
- Slicers
- Excel formulas
- Data cleaning and preparation
- Dashboard design

### Analytical Skills

- Exploratory Data Analysis
- Descriptive Analytics
- Employee Attrition Analysis
- Risk Segmentation
- KPI Development
- Data Visualization
- Business Insight Generation
- Business Recommendations

---

## Project Structure

```text
HR-Employee-Attrition-Analysis/
│
├── excel/
│   └── HR_Employee_Attrition_Analysis.xlsx
│
├── screenshots/
│   └── dashboard.png
│
├── documentation/
│   └── project_documentation.md
│
└── README.md
```
## Limitations

This analysis identifies associations between employee characteristics and attrition but does not establish causation. The Risk Score is a business-oriented analytical framework and has not been statistically validated as a predictive model.

## Future Improvements

Future improvements could include building a predictive attrition model using Python, applying logistic regression and machine-learning techniques, evaluating model performance using appropriate classification metrics, adding statistical significance testing, developing a more formally validated employee risk model, and automating the analysis and dashboard using Power BI.

## Conclusion

This project demonstrates how HR data can be transformed into actionable insights using Excel. The analysis combines descriptive analytics, risk segmentation, and interactive visualization to identify potential retention priorities and support data-informed HR decisions.
