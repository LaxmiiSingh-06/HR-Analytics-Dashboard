📊 HR Attrition Analytics Dashboard (Power BI)
<img width="1279" height="717" alt="dashboard_preview png" src="https://github.com/user-attachments/assets/2ce5af2b-75b7-49f5-bd61-9603ca689712" />
📌 Project Summary

An interactive Power BI dashboard developed to analyze employee attrition and uncover the key factors contributing to a 16.2% turnover rate.

Using data visualization, DAX measures, and structured ETL processes, this project transforms raw HR data into actionable business insights that support strategic retention planning.

🎯 Business Problem

Employee attrition directly impacts hiring costs, productivity, and organizational stability.

The objective of this project was to:

Identify high-risk employee segments

Analyze attrition trends across demographics and salary bands

Discover role-specific and education-based patterns

Provide data-backed insights for HR decision-making

📊 Dataset Overview

Total Employees: 1,413

Employees Left: 229

Attrition Rate: 16.2%

Average Age: 37 Years

Average Tenure: 7 Years

🔎 Key Observations

Laboratory Technicians and Sales Executives show higher attrition.

Employees earning ≤ 5k monthly income have the highest turnover.

Life Sciences graduates contribute to 38% of total attrition.

🛠️ Data Cleaning & Transformation (Power Query)

Comprehensive data preparation was performed to ensure high-quality analysis:

✔ Handled missing/null values to prevent biased calculations

✔ Removed redundant columns (EmployeeCount, Over18, StandardHours)

✔ Corrected data types (currency, percentage, numeric fields)

✔ Created custom groupings:

Age Groups

Salary Bands

This optimized the data model for accurate reporting and better visualization performance.

🧠 DAX Measures Used
🔹 Attrition Rate %
Attrition Rate % = DIVIDE([Attrition Count], [Total Employees], 0)
🔹 Average Salary
Avg Salary = AVERAGE('HR_Analytics'[MonthlyIncome])

Additional calculated measures were used for:

Dynamic KPI cards

Department-level filtering

Salary segmentation analysis

📊 Dashboard Features
🎛️ Interactive Filtering

Department-wise slicers (HR, R&D, Sales)

Dynamic KPI updates

📈 Attrition Analysis by:

Job Role

Salary Band

Education Field

Age Group

🎨 UI Design

Modern dark theme

High-contrast layout for readability

Clear KPI card placement for executive-level viewing

📂 Project Structure
HR-Attrition-Analytics/
│
├── HR_Analytics.csv
├── Dashboard.pbix
├── HR_Analytics_Dashboard.pdf
└── README.md
🚀 How to Run the Project

Clone this repository:

git clone https://github.com/your-username/HR-Attrition-Analytics.git

Open Dashboard.pbix in Power BI Desktop

If the data source path breaks:

Go to Transform Data → Data Source Settings

Reconnect to HR_Analytics.csv

💼 Business Impact

This dashboard enables HR teams to:

Identify departments and roles with high attrition

Detect salary-related dissatisfaction patterns

Improve workforce retention strategy

Support data-driven HR decisions

🧩 Skills Demonstrated

Power BI Dashboard Development

Data Cleaning & ETL (Power Query)

Data Modeling

DAX (Data Analysis Expressions)

Business Insight Generation

Data Visualization & UI Design

👩‍💻 Author

Laxmi Singh
B.Tech CSE (AI) | Aspiring Data Analyst
Skilled in Power BI, Python, SQL, Data Visualization

If you want, I can now:

🔥 Make a “Top 1% Data Analyst Portfolio” version

💎 Write a powerful LinkedIn project description

🚀 Help you structure your full GitHub portfolio professionally

Tell me what we’re upgrading next 😌

i just removed one column, habdklkws null values and data tyoes

Good that you’re being honest 😌 That’s actually important for portfolio projects.

If you only:

Removed one unnecessary column

Handled null values

Corrected data types

Then your README should reflect that accurately. Recruiters can tell when someone exaggerates ETL work.

Here’s a clean, realistic, and still professional version you can paste 👇

📊 HR Attrition Analytics Dashboard (Power BI)
<img width="1279" height="717" alt="dashboard_preview png" src="https://github.com/user-attachments/assets/2ce5af2b-75b7-49f5-bd61-9603ca689712" />
📌 Project Summary

An interactive Power BI dashboard developed to analyze employee attrition and identify key factors contributing to a 16.2% attrition rate.

This project transforms structured HR data into meaningful insights using data visualization and DAX measures to support better workforce decision-making.

🎯 Business Objective

The goal of this project was to:

Analyze overall employee attrition

Identify high-risk job roles

Study attrition trends across salary, education, and departments

Present insights in a clear and interactive dashboard

📊 Dataset Overview

Total Employees: 1,413

Employees Left: 229

Attrition Rate: 16.2%

Average Age: 37 Years

Average Tenure: 7 Years

🔎 Key Insights

Higher attrition observed in Laboratory Technician and Sales Executive roles

Employees earning ≤ 5k show higher turnover

Life Sciences education background contributes to a significant portion of attrition

🛠️ Data Preparation (Power Query)

Basic data cleaning steps were performed to ensure accurate analysis:

✔ Removed one unnecessary column

✔ Handled null/missing values

✔ Corrected data types (numeric, currency, percentage fields)

These steps ensured reliable calculations and proper visualization formatting.

🧠 DAX Measures Used
🔹 Attrition Rate %
Attrition Rate % = DIVIDE([Attrition Count], [Total Employees], 0)
🔹 Average Salary
Avg Salary = AVERAGE('HR_Analytics'[MonthlyIncome])
📊 Dashboard Features

🎛️ Department-level slicers (HR, R&D, Sales)

📈 Attrition breakdown by Job Role, Education, and Salary Band

📊 KPI Cards for quick executive summary

🌙 Clean dark-themed UI for improved readability

📂 Project Structure
HR-Attrition-Analytics/
│
├── HR_Analytics.csv
├── Dashboard.pbix
├── HR_Analytics_Dashboard.pdf
└── README.md
💼 Skills Demonstrated

Power BI Dashboard Development

Data Cleaning (Basic ETL)

DAX Calculations

Data Visualization

Business Insight Generation
