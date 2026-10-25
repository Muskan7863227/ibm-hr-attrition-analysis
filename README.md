# IBM HR Attrition Analysis | Excel

## Business Problem
The Purpose of this project is to analyze employee attrition and identify workforce groups with higher
turnover rates.

The analysis focuses on these questions:
* Which departments and job roles have the highest attrition rates?
* Is attrition higher among employees who work overtime?
* How does attrition vary by age group and years at the company?
* Is job satisfaction associated with employee attrition?
* Does attrition differ by gender and distance from home?

The goal is to provide HR with useful insights that can guide further investigation and employee-retention planning.

## Dataset and Data Preparation
## Dataset: IBM HR Analytics Employee Attrition & Performance

## Tool: Microsoft Excel
## Data Preparation
The IBM HR dataset contained 1,470 employee records. I checked the data for duplicate employee numbers, missing values, data types and category 
consistency before beginning the analysis.

The dataset had no duplicate employee records, so no duplicate removal was required. I then prepared the data for analysis by creating additional
columns for age groups, tenure groups, income bands, job satisfaction category, education labels, distance band and a numeric attrition flag.

I used excel Tables and formulas to organize the data and support the PivotTables and Dashboard.

## Excel Technique Used
* Excel Tables and structured references
* IF,COUNTIF,COUNTIFS and AVERAGE formulas
* PivotTables and PivotCharts
* Multi-dimensional analysis using Department and OverTime
* Slicers and an interactive dashboard

## Analysis and key Findings
I used PivotTables, formulas and charts to compare attrition across different employee groups. The results were presented in an Excel dashboard with
KPI cards and slicers.

## Key Metrics

| Metric | Result |
| :--- | :---: |
| Total Employees | 1,470 |
| Employees who left | 237 |
| Overall Attrition Rate | 16.12% |

## Key Findings
* Overtime: Employees working overtime had a 30.53% attrition rate, compared with 10.44% among employees who did not work overtime.
* Department: Sales had the highest attrition rate 20.63% followed by Human Resources at 19.05% and Research & Development at 13.84%.
* Age Group: Employee under 25 had the highest attrition rate among the age groups analyzed, at 35.77%.
* Job satisfaction: Employees with low job satisfaction had the highest attrition rate among the four satisfaction levels shown in the analysis.
* Distance from Home: Employees living 15 km or far away showed a higher attrition rate than the other distance groups in the analysis.

## Dashboard
The dashboard summarizes workforce metrics and allows users to explore attrition patterns using slicers for department , job role, gender, job level and overtime

## Recommendations
* 1.Review overtime workload:
    Investigate staffing levels and workload distribution in teams with higher attrition among employees working overtime.
* 2.Support early-career employees:
    Review onboarding , training, career development and manager support for employees under 25.
* 3.Improve job satisfaction:
    Investigate the concerns of employees reporting low satisfaction and consider targeted engagement initiatives.
* 4.Explore commuting challenges:
    Examine whether commuting distance is associated with attrition and assess whether flexible working arrangements are practical.

## Limitations
* The findings show associations, not proven causes of employee attrition.
* The analysis does not establish whether the identified factors directly cause employees to leave.
* Recommendations require further investigation before implementation.

## Project Files 
* IBM_HR_Attrition_Analysis.xlsx  --
  Workbook containing the original data, cleaned data, calculations, PivotTables, dashboard and insights
* dashboard.png --
  Screenshot of the final Excel dashboard.

  ## dataset
  Dataset link:
  https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset
