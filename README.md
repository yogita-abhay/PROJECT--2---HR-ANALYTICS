<img width="1888" height="930" alt="image" src="https://github.com/user-attachments/assets/20c14a3c-df0c-4340-94cc-102b3e926542" />📊 HR Analytics Project: Employee Retention
This project leverages HR data to analyze workforce behavior and identify the primary drivers of employee attrition, with the goal of providing actionable insights for strengthening retention strategies. 

🚀 Project Goal
To analyze key HR metrics—such as attrition, demographics, salary, and job satisfaction—to understand who is leaving, why they are leaving, and how to improve employee retention. 

🛠️ Tools & Technologies
The analysis and visualization for this project were performed using the following tools:

Data Cleaning & Manipulation: MS-Excel 

Data Merging & Querying: SQL (MySQL) 

Data Visualization & Dashboards: Power BI and Tableau 

📁 Dataset Overview
The project uses two Microsoft Excel datasets, HR_1 and HR_2, each containing 50,000 records. 

File Name	Key Content	Merging Key (Implicit)
HR_1	
General attributes (Age, Department, Attrition, Business Travel) 

Employee Number 

HR_2	
Compensation & history (Monthly Income, Over Time, Performance Rating, Total Working Years) 

Employee ID 

The two files were combined into a single, comprehensive table using a Full Outer Join on the employee identifier columns to unify data fields for KPI calculation. 

📈 Key Performance Indicators (KPIs)
The following metrics were calculated to drive insights: 


Attrition Rate (%): (Employees Left / Total Employees) × 100 


Attrition Rate vs. Year Since Last Promotion 


Avg Monthly Income By Job Role 

Job Satisfaction Rating - Department Wise 


High-Performer Churn Rate 


The Risk Score Calculation 


Near Retirement Employees 

EXCEL DASHBOARD

<img width="1888" height="930" alt="image" src="https://github.com/user-attachments/assets/e9d2e294-9bd0-4996-9403-2709c0601e18" />

POWER BI DASHBOARD
<img width="1884" height="996" alt="image" src="https://github.com/user-attachments/assets/18dbd2d2-0f5a-4581-a1e0-b1436d3a86b4" />

TABLEAU DASHBOARD
<img width="2000" height="997" alt="image" src="https://github.com/user-attachments/assets/59b7e7cd-85c6-461e-9ed2-1fa941a2f9e5" />

SQL QUERIES
<img width="1448" height="675" alt="image" src="https://github.com/user-attachments/assets/59ffca8d-ba75-4f1c-9f7d-24383f9f202f" />
<img width="1345" height="758" alt="image" src="https://github.com/user-attachments/assets/0e314c05-5f78-4c4a-9188-0c2822006f56" />



🔍 Core Insights & Findings
The analysis reveals that employee attrition is primarily driven by a lack of career growth, poor work-life balance, and low compensation in high-pressure roles. 


Promotion Impact: 75–82% of attrition comes from employees who were not recently promoted. 

Work-Life Balance: Poor or Very Poor work-life balance is linked to lower satisfaction and higher attrition, which even competitive salaries fail to counter. 
Risk Groups: Attrition is highest in the 0–10 years since last promotion bracket, indicating early and mid-career employees are at the highest risk. 
Department Hotspots: Software, Sales, and Support departments have the highest attrition, suggesting burnout in high-pressure and customer-facing roles. 
Compensation: Employees in Very Low and Low income ranges show the highest exit rates. 
Gender: There is no noticeable gender-based attrition imbalance, as average hourly wages are nearly identical for male and female employees. 

🎯 Recommendations
Based on the insights, the following actions are recommended: 

Implement regular promotion and career path planning to address the primary driver of turnover. 

Improve work-life balance policies specifically in high-attrition departments (Sales, Software, Support). 


Revise the pay structure for job roles in the low-income bands. 


Track job satisfaction scores to use them as an early-warning signal for attrition. 

Launch targeted early-career retention programs to focus on the highest-risk group. 




