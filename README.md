
# 📊 HR Attrition Analytics Dashboard (Power BI)

<img width="1279" height="717" alt="dashboard_preview png" src="https://github.com/user-attachments/assets/2ce5af2b-75b7-49f5-bd61-9603ca689712" />

## 📌 Overview

This project presents an interactive **Power BI dashboard** built to analyze employee attrition and understand factors contributing to a **16.2% attrition rate**.

The dashboard provides insights into employee turnover trends across job roles, salary bands, education background, and departments.

---

## 📊 Dataset Summary

* **Total Employees:** 1,413
* **Employees Left:** 229
* **Attrition Rate:** 16.2%
* **Average Age:** 37 Years
* **Average Tenure:** 7 Years

---

## 🎯 Key Insights

* Higher attrition observed in **Laboratory Technician** and **Sales Executive** roles
* Employees earning **≤ 5k monthly income** show higher attrition
* Life Sciences education background shows higher turnover

---

## 🛠️ Data Preparation (Power Query)

* Removed one unnecessary column
* Handled null values
* Corrected data types for accurate calculations and reporting

---

## 🧠 DAX Measures

### Attrition Rate %

```DAX
Attrition Rate % = DIVIDE([Attrition Count], [Total Employees], 0)
```

### Average Salary

```DAX
Avg Salary = AVERAGE('HR_Analytics'[MonthlyIncome])
```

---

## 📊 Dashboard Features

* Department-wise slicers (HR, R&D, Sales)
* Attrition analysis by Job Role, Education, and Salary
* KPI cards for quick summary
* Clean dark-themed layout

---

## 📂 Project Files (Root Level)

```
HR_Analytics.csv
Dashboard.pbix
HR_Analytics_Dashboard.pdf
README.md
```

---

## 🚀 Tools Used

* Power BI
* Power Query
* DAX

---

## 💼 Skills Demonstrated

* Data Cleaning
* Data Visualization
* KPI Reporting
* Business Insight Generation

---

