# [Project Title]
> HR Dashboard Analysis



## ⚙️ Project Type Flags

- [ ] SQL Analysis / Querying
- [ ] Dashboard / Data Visualization
- [ ] Data Cleaning
- [ ] End-to-End Project



## Table of Contents
1. [Project Overview](#1-project-overview)
2. [Objectives](#2-objectives)
3. [Dataset info & Tools](#3-Dataset-info-tools)
4. [Repository Structure](#4-Repository-Structure)
5. [project Workflow](#5-project-workflow)
6. [Data Model & Schema](#6-data-model--schema)
7. [Analysis & Metrics](#7-analysis--metrics)
8. [Key Insights](#8-key-insights)
9. [Recommendations](#9recommendations)
10. [Future Enhancements](#10-future-enhancements)
11. [Conclusions](#11-Conclusions)
12. [Author](#12-author)

---

## 1. Project Overview

 This HR Analytics Project Analyzes Employee Performance, Attendance, Productivity, Training, and Promotion Readiness using SQL and Power BI. The data was cleaned    and Analyzed to Evaluate key HR Metrics, Identify Performance trends, and Compare Department-Wise Performance and Interactive Power BI Dashboard was Developed to    Visualize KIPS and generate actionable Insights, Enabling HR teams to Make Data-Driven Decisions for Employee Development, Performance Management, and Promotion     Planning.


Problem Statement: [The Organization has Employee Data but lacks Clear insights into Employee Productivity, training, and Promotion Eligibility. The business needs to analyze Performance patterns, Recognize areas for Improvement, and Support better HR decision-Making.]

---
## 2. Objectives

To Analyze Employee Performance, Productivity, Attendance, Training Data to Identify high performing Employees Driven HR Decision on Promotion and Employee Development.
 
---
## 3. Dataset Info & Tools
Name: Employee performance Dataset.
Source: Kaggle.
No. of Rows: 5000
No. of Columns: 13
Types: HR Data Contains Employee Demographics Details Department Info, job roles, Attendance Records, Perform Score, KPIS Score, Task Completion, Peer ratings, and Promotion Eligibility.

### Tools & Technologies
Tool(s) Used 
Excel, SQL, Power BI

Excel: Conducted initial Data inspection and verified the dataset before analysis, also I changed some column names.
SQL: Queried the Dataset, performed aggregations, analyzed attendance records, performed PIS Score, task Completion, peer rating, promotion Eligibility.
Power BI: Developed HR Analytics Dashboard, Created KPI Card for Average Attendance, Total Employee and Promotion Eligibility.

---
## 4.Repository structure

[project-root]/
 |
 |__data/
 |    |__raw/                  # original, unmodified sources data - never edited
 |    |__processed/            # cleaned and transformed data
 |
 |__queries/ 
 |   |__transformation/        # presentation of queries 
 |
 |__ reports/                  # final outputs: PDFS, Word docs
 |
 |__visuals/                   # Exported charts, dashboard screenshots
 |
 |__README.md                  # project

 
---
## 5. Project Workflow

  1. Source: "Collected the Employee Performance Dataset from Kaggle."
  2. Ingestion: "Loaded into Excel Performed Detail inspection before Analysis and also changed column names."
  3. Cleaning: "Performed Data cleaning and Analysis Business Insights Using SQL."
  4. Transformation: "Created aggregation Queries, Group by queries ."
  5. Analysis: "Developed Interactive Dashboard and KPIS using Power BI."
  6. Output: "Summary report (PDF), processed CSV."

---
## 6. Data Model & Schema

### Dataset / Table: `[name]`

| Field Name | Data Type | Description | Example Value |
|------------|-----------|-------------|---------------|
|[Employee id] | [String / Integer] | [Unique Identifier assigned to each employee.] | [1001] |
|[Name] |[string] | [Full name of the employee.] | [Rahul Sharma] |
|[Department] | [String] | [Department in which the employee works.] | [Finance] |
|[Job Role] | [string] |[Job Role or role of the employee.] | [Data Analyst]|
|[Performance score] | [Float / Decimal] | [Overall Performance score assigned to be employee.] |[4.5]|
|[KPI Score_] | [Float / Decimal] | [Employee's KPI(key performance indicator)Score used to measure performance against targets.] | [87.5]|
|[Attendance] | [Float / Decimal] | [Percentage of Working days attended by the employee.] |[92.5]|
|[Peer Rating] | [ Float / Decimal] | [Rating given to the employee by colleagues or peers.] | [4.2]|
|[Task Completion]| [Float / Decimal] | [Percentage of assigned tasks completed by the employee.] | [95.0]|
|[Work Hours Logged] | [Float / Decimal] | [Total number of working hours logged by the employee.] | [168.5]|
|[Manage Feedback] | [string / Text] | [Feedback or evaluation provided by the employee's manager.] | [Excellent Performance] |
|[Training Hours]| [Integer / Float] | [Number of hours the employee spent in training or professional development.] | [24]|
|[Promotion Eligibility]| [string / Boolean] |[indicates whether the employee is eligible for promotions and other criteria.] | [Yes]

--- 
## 7. Analysis & Metrics

### Analytical Approacch

1.Analyzed Employee Performance across Different Departments.
2.Evaluated Attendance trends and Workforce Productivityy.
3.Analyzed Training Hours and Workforce Logged to Identify Productivity patterns.
4.Identified Employees Eligibility for Promotional Based on Performance.
5.Generated Actionable Insights to Support employees Development and performance Management.
6.Enabled Data-Driven HR Decisions Making it through Interactive Visualizations and Reports.

### Key Metrics Defined
[No. of Employees.] [No. of Employees from Different Job Roles.] [No. of Highest Employees.] [Average Attendance rate.] [Average Performance rate.] 
[Average Task Completion.] [Average Peer Ratings._] [Total Highest Attendance.] [Which Department has Highest Task Completion rate.] 
[Total Work Hours logged.] [Total Training Hours_][Total Performing score.] [Low Attendance rate.] [No. of Employees Eligible for promotions.]
[No. of Highest and Lowest Departments Eligible for Promotions.]

---
## 8. Key Insights

Insight 1:[Identified the Distribution of Employees across Different Departments.]

Insight 2:[Analyzed the distribution of Employees by Job Role.]

Insight 3:[Evaluated the Average Attendance of Employees across the Organization.]

Insight 4:[Compared Department-Wise Attendance to Identify Departments with the Highest and lowest attendance.]

Insight 5:[Analyzed the Average Task completion Rate, Peer Rating, and Performance.]

Insight 6:[Evaluated Department-Wise Task Completion to Identify High Performing Departments.]

Insight 7:[Analyzed Total Training Hours and Work Hours Logged across Department.]

Insight 8:[Identified employee Eligible for promotion to Support HR Decision Making.]

---
## 9. Recommendations

  1.Provide Additional Training and Skill Development Programs for Low-performing Employees.
  2.Recognized and Reward High-Performing Employees to Improve motivation and Retention.
  3.Use Promotion Eligibility Metrics to Ensure Fair and Transparent Promotion Decisions.
  4.Track Employee performance Continuously using Interactive HR Dashboards.
  5.Use Data-Driven Insights to Improve Workforce Planning, Performance Management, and Talent Development.

---
## 10. Future Enhancements

- [ ] [Enhancement 1 - Integrate Real-time HR Data From HRMS or ERP Systems for live performance monitoring.]
- [ ] [Enhancement 2- Build a Promotion Recommendation System Using Employee Performance and KPI Data.]
- [ ] [Enhancement 3- Implemented Employee Segmentation Based on Performance, Skills, and Productivity.]
- [ ] [Enhancement 4 - Develop Predictive Models to Identify Employees at Risk of Low performance or attrition.]
- [ ] [Enhancement 5 - Perform Sentimental Analysis on Employee Feedback and Survey Responses to Measure job Satisfaction.]

---
## 11. Conclusions

This HR analytics Project Successfully analyzed Employee Performance, Attendance, Productivity, Training and Promotion Readiness Using SQL and Analyzed to identify Work forced trends and Key HR Metrics.
An Interactive Dashboard was Developed to Visualize Employee and Department Performance, Enabling Data-Driven HR Decision-Making. The Insights and Recommendations from this Project Can Help Improve Employee Performance, Optimize Training Programs, Support Fair Promotion Decisions, and Enhance Overall Workforce Efficiency.

---
## 12. Author

 [Zeba Hajera] 
   [Data Analyst]

- 🔗 [https://www.linkedin.com/in/zeba-hajera-3a437a366?utm_source=share_via&utm_content=profile&utm_medium=member_android]
- 💼 [https://github.com/zeba318]
- 📧 [zebahajera715@gmail.com]

---
