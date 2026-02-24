**📊 HR Employee Attrition Analysis (Power BI)**

📌 Project Overview
Employee attrition is a major challenge for organizations.
This project uses Power BI to analyze an HR Employee Attrition dataset and understand why employees leave the company.

An interactive dashboard is created to help HR teams identify key factors influencing attrition such as department, age group, income, job role, and job satisfaction.

🎯 Objectives
Analyze employee attrition trends

Identify departments and roles with high attrition

Understand the impact of age, income, and job satisfaction

Build an interactive dashboard with filters (slicers)

🧰 Tools & Technologies
Power BI Desktop

CSV Dataset (HR Employee Attrition)

DAX (for measures & calculated columns)

📂 Dataset Information
The dataset contains employee details such as:
Age

Gender

Department

Job Role

Monthly Income

Job Satisfaction

Attrition (Yes / No)

📐 Dashboard Features
🔹 KPIs
Total Employees

Employees Left

Attrition Rate (%)

🔹 Visualizations
Attrition by Department

Attrition by Age Group

Attrition by Income Group

Attrition by Job Role

Job Satisfaction vs Attrition

🔹 Slicers (Filters)
Department

Age Group

Gender

Job Role

Income Group

All visuals update dynamically when filters are applied.

🧮 Key Calculations (DAX)
Total Employees
Total Employees = COUNTROWS(HR-Employee-Attrition-Dataset)
Employees Left
Employees Left =
CALCULATE(
    COUNTROWS(HR-Employee-Attrition-Dataset),
    HR-Employee-Attrition-Dataset[Attrition] = "Yes"
)
Attrition Rate
Attrition Rate % =
DIVIDE([Employees Left], [Total Employees]) * 100
📊 Monthly Income vs Attrition

Employees are grouped into income categories:
Low Income

Medium Income

High Income

Very High Income

This helps in understanding how salary impacts attrition.

🔍 Insights
Certain departments show higher attrition rates

Younger and low-income employees tend to leave more

Employees with lower job satisfaction have higher attrition

These insights can help HR teams take preventive actions.

📌 Conclusion
This project demonstrates how data visualization and interactive dashboards can help organizations understand employee behavior and reduce attrition.

👩‍🎓 Author
Shreya Surve
