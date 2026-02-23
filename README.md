📊 HR Attrition Analytics Dashboard
<img width="1279" height="717" alt="dashboard_preview png" src="https://github.com/user-attachments/assets/2ce5af2b-75b7-49f5-bd61-9603ca689712" />


An interactive Power BI dashboard designed to analyze employee turnover and identify key factors contributing to a 16.2% attrition rate.

This project provides data-driven HR insights by visualizing attrition trends across demographics, salary bands, education background, and job roles to help improve employee retention strategies.

🎯 Project Overview

This project analyzes a dataset of 1,413 employees to understand why employees are leaving the organization.

Out of 1,413 employees:

229 employees left

Overall Attrition Rate: 16.2%

The analysis identifies high-risk job roles such as:

Laboratory Technician

Sales Executive

📌 Key KPIs

👥 Total Employees: 1,413

❌ Total Attrition: 229

📉 Attrition Rate: 16.2%

🎂 Average Age: 37 Years

🏢 Average Tenure: 7.0 Years

🛠️ Data Cleaning & ETL (Power Query)

Data preprocessing was performed in Power Query to ensure accuracy and reliability:

✔️ Null Value Treatment: Removed / handled missing records to avoid distorted insights

✔️ Column Optimization: Removed irrelevant columns such as:

EmployeeCount

Over18

StandardHours

✔️ Data Type Formatting: Corrected numerical, percentage, and currency formats

✔️ Custom Grouping: Created:

Age Groups

Salary Bands

🧠 Technical Highlights (DAX Measures)
1️⃣ Attrition Rate %
Attrition Rate % = DIVIDE([Attrition Count], [Total Employees], 0)
2️⃣ Average Salary
Avg Salary = AVERAGE('HR_Analytics'[MonthlyIncome])
📊 Dashboard Features

🎛️ Interactive Slicers

Filter by Department (HR, R&D, Sales)

🎓 Attrition by Education

Life Sciences (38%) shows highest turnover

💰 Salary Band Analysis

Employees earning ≤ 5k show highest attrition

🌙 Modern Dark Theme UI

High contrast design for improved readability

📂 Project Structure
📁 HR-Attrition-Analytics
│
├── HR_Analytics.csv
├── Dashboard.pbix
├── HR_Analytics_Dashboard.pdf
└── README.md
🚀 How to Use

Clone this repository:

git clone https://github.com/your-username/HR-Attrition-Analytics.git

Open Dashboard.pbix in Power BI Desktop

If the data source path breaks:

Go to Transform Data → Data Source Settings

Reconnect to HR_Analytics.csv

💡 Business Impact

This dashboard helps HR teams:

Identify high-risk employee segments

Understand salary-based attrition patterns

Improve retention strategies

Make data-driven workforce decisions
