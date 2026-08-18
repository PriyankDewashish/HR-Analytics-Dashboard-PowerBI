# HR Analytics Dashboard — Power BI

An interactive HR Analytics dashboard built in Power BI to analyze employee attrition, satisfaction, and workforce trends across departments, job roles, age groups, and salary bands.

<img width="677" height="587" alt="HR-Dashboard" src="https://github.com/user-attachments/assets/72a0e0dd-2d0c-44c2-abcf-72d4876331ff" />



## Problem Statement
HR teams need a quick way to see where and why employees are leaving. This dashboard turns a raw 1,480-row employee dataset into a single view covering attrition by department, age, salary, and job satisfaction.

## Dataset
- 1,480 employee records, 38 columns
- Key fields: Age, Department, JobRole, EducationField, Gender, MonthlyIncome, SalarySlab, JobSatisfaction, YearsAtCompany
- File: `HR_project_Power_BI.xlsx`

## Tools Used
- Power BI Desktop (data modeling, DAX, dashboard design)
- Excel (source dataset)

## Key DAX Measures
| Measure | Definition |
|---|---|
| Total Employees | Count of all employees |
| Employees Left | Count where Attrition = Yes |
| Attrition Rate | Employees Left ÷ Total Employees |
| Avg Monthly Income | Average of MonthlyIncome |
| Employees Average Age | Average of Age |
| Avg Emp Years | Average of YearsAtCompany |

## Dashboard KPIs
| Metric | Value |
|---|---|
| Total Employees | 1,480 |
| Employees Left | 238 |
| Attrition Rate | 16.1% |
| Employees Average Age | 36.9 |
| Avg Years at Company | 7.01 |
| Avg Monthly Income | ₹6,505 |

## Visualizations Used
- Cards for headline KPIs
- Donut chart — Attrition by Education Field
- Bar charts — Attrition by Salary Slab, Attrition by Age Group, Employees Left by Department
- Matrix table — Job Role vs Job Satisfaction Level
- Line chart — Years at Company vs Attrition Count
- Slicers — Department and Gender

## Key Insights
- Sales has the highest attrition rate (20.7%), followed by HR (19.0%) and R&D (13.8%). R&D has the most total exits (133) due to its larger headcount.
- The 18–25 age group has the highest attrition at 35.8%, nearly double the 26–35 group (19.0%) and over 3x the 36–45 group (9.1%).
- Attrition drops sharply with pay: 21.6% for employees earning up to ₹5k, vs just 3.8% for those earning ₹15k+.
- Overall, early-career, lower-paid employees in Sales and HR are the highest-risk group for attrition.

## Repository Contents
- `HR_Analytics_Dashboard_Project.pbix` — Power BI report file
- `HR_project_Power_BI.xlsx` — source dataset


## How to View
1. Download `HR_Analytics_Dashboard_Project.pbix`
2. Open it in Power BI Desktop (free)
3. Or view the screenshot in this repo for a quick preview
