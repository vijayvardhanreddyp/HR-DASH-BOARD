# HR Analytics Dashboard
This project focuses on analyzing HR data to help an organization improve employee management, retention, and performance. The analysis includes insights into employee demographics, attrition rates, performance metrics, and factors influencing employee turnover.

Live Interactive Dashboard: [https://lpuin-my.sharepoint.com/:u:/g/personal/satish_ganesh23_lpu_in/EQmmsl_FQDtJp5D2PNU9naIBvr-o0Xp0yDAFW01u8x2XEw?e=QltieJ]

## 1. Overview
This project focuses on analyzing HR data to help an organization improve employee management, retention, and performance. The analysis includes insights into employee demographics, attrition rates, performance metrics, and factors influencing employee turnover.

The goal of the project is to provide actionable insights that can assist HR teams in making data-driven decisions to enhance employee satisfaction, retention, and overall performance.

## 2. Project Goals
- Develop key HR metrics based on the provided dataset.
- Construct a dashboard aligned with stakeholder requirements.
- Generate insights that go beyond predefined metrics and offer actionable recommendations for HR management.

## 3. Import & Explore Data

### A. Importing Data into Power BI
The HR dataset was imported into Power BI, which includes employee demographic data, performance reviews, compensation details, and attrition status.

### B. Using SQL to Explore Data
Data exploration was performed to understand employee trends, key factors affecting attrition, and patterns related to employee performance and demographics.

**Dataset Overview:**
- **dim_employees**: Contains employee information such as ID, age, gender, department, and years of experience.
- **dim_department**: Provides details about departments and job roles.
- **fact_performance**: Includes performance review scores and feedback metrics.
- **fact_compensation**: Contains salary, bonuses, and benefits information.
- **fact_attrition**: Tracks employee attrition status, exit dates, and reasons for leaving.

## 4. Data Modeling
The HR data was modeled using Power BI’s Power Query. The following steps were undertaken:
- Data cleaning, transformation, and formatting using Power Query.
- Establishing relationships between fact and dimension tables, following the **Star Schema** methodology.
- Ensuring data consistency and validating it against the predefined metrics.

## 5. Dashboard Designing
Based on stakeholder mockups and requirements, the following views were designed:

| **Views**         | **Description**                                          |
|-------------------|----------------------------------------------------------|
| **Employee Overview** | Provides a summary of employee demographics, performance, and attrition. |
| **Attrition Analysis** | Analyzes employee turnover rates, reasons for attrition, and risk factors. |
| **Performance Metrics** | Highlights performance scores and comparisons across departments. |
| **Compensation Insights** | Breaks down employee compensation, benefits, and salary ranges. |

### Basic Metrics:
- **Employee Count**: Total number of employees in the organization.
- **Attrition Rate**: Percentage of employees who have left the company.
- **Average Tenure**: The average duration employees have stayed in the company.
- **Performance Score**: Average employee performance review scores.
- **Salary Distribution**: Breakdown of salary ranges across departments.
- **Job Roles**: Count and analysis of different job roles.

### Measures:
| **Measures**         | **Description**                                         |
|----------------------|---------------------------------------------------------|
| **Total Employees**   | Total number of employees across all departments.       |
| **Total Attrition**   | Number of employees who have left the company.          |
| **Average Salary**    | Average salary of employees in different departments.   |
| **Attrition by Gender** | Percentage of attrition by gender.                    |
| **Performance Score by Department** | Average performance score across departments. |
| **Attrition Rate**    | Percentage of employees who have left over the total headcount. |

## 6. Filters Used
- **Department**: To analyze HR metrics by different departments.
- **Job Role**: To filter performance and attrition data by job roles.
- **Gender**: To analyze gender-specific trends in performance, salary, and attrition.
- **Years of Experience**: To filter data based on employee experience levels.
- **Attrition Reason**: To filter and explore reasons for employee attrition.

## 7. Dashboard Created
A comprehensive HR dashboard was built to offer insights into employee demographics, performance, attrition rates, and compensation. This helps HR teams better understand the organization's workforce and optimize retention strategies.

## 8. Project Outcomes
### Learnings:
- Enhanced ability to create custom visuals for HR data analysis using Power BI.
- Identified key factors contributing to employee attrition, such as performance and compensation disparities.
- Developed insights to improve employee engagement, retention, and satisfaction.

### Key Metrics:
- **Attrition Rate**: The overall percentage of employees who have left the company.
- **Average Performance Score**: The average score for employee performance reviews.
- **Average Tenure**: The average number of years employees have stayed in the company.
- **Salary Range by Department**: Insights into compensation trends across different departments.
- **Attrition by Department**: Percentage of attrition across departments and job roles.

## 9. Insights from the Dashboard:
- **Attrition Rate** is higher in the sales and marketing departments, contributing to 25% of total turnover.
- **Female employees** have a slightly higher attrition rate, accounting for 60% of total exits.
- Employees with **less than 2 years of experience** show the highest attrition, indicating potential onboarding or retention issues.
- **Compensation discrepancies** were found to be a contributing factor to employee turnover in certain departments.
- **Performance scores** were highest in the IT and R&D departments, while sales showed below-average performance.

