📊 HR Attrition Analytics Dashboard
<img width="1279" height="717" alt="dashboard_preview png" src="https://github.com/user-attachments/assets/cb48780c-c56a-4920-acc9-8a30bfddc46b" />

An interactive Power BI project designed to analyze employee turnover and identify key factors contributing to a 16.2% attrition rate. This dashboard provides data-driven insights to help HR teams improve retention strategies by visualizing trends across demographics, salary, and job roles.

🎯 Project Overview
This project focuses on identifying why employees are leaving the organization. By analyzing a dataset of 1,413 employees, I uncovered that 229 individuals have left, with specific high-risk groups in Laboratory Technician and Sales Executive roles.

Key KPIs:
Total Employees: 1,413

Total Attrition: 229

Attrition Rate: 16.2%

Average Age: 37 Years

Average Tenure: 7.0 Years

🛠️ Data Cleaning & ETL (Power Query)
To ensure data integrity, I performed extensive data preparation in Power Query:

Null Value Treatment: Identified and removed/imputed missing records to prevent skewed averages.

Column Optimization: Removed irrelevant or static columns (e.g., EmployeeCount, Over18, StandardHours) to streamline the data model.

Data Typing: Ensured all numerical values, percentages, and currencies were correctly formatted for accurate calculations.

Conditional Columns: Created custom groupings for Age and Salary to enable better categorization in bar charts.

🧠 Technical Highlights (DAX)
I used DAX (Data Analysis Expressions) to create dynamic measures:

1. Attrition Rate %

Code snippet
Attrition Rate % = DIVIDE([Attrition Count], [Total Employees], 0)
2. Average Salary

Code snippet
Avg Salary = AVERAGE('HR_Analytics'[MonthlyIncome])
🎨 Dashboard Features
Interactive Slicers: Filter by Department (HR, R&D, Sales) for granular analysis.

Attrition by Education: A donut chart showing that Life Sciences (38%) backgrounds have the highest turnover.

Salary Distribution: A bar chart highlighting that employees earning up to 5k are most likely to leave.

Dark Theme UI: Designed for a modern, high-contrast look to improve data readability.

📂 Project Structure
HR_Analytics.csv: The raw dataset used for analysis.

Dashboard.pbix: The full Power BI file with the data model and visuals.

HR_Analytics_Dashboard.pdf: A static snapshot of the final report.

🚀 How to Use
Clone this repository or download the files.

Open Dashboard.pbix in Power BI Desktop.

If the data source path breaks, point it to the included HR_Analytics.csv file.
