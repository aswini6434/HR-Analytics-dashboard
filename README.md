📊 **HR Analytics Dashboard – Portfolio Project**

This project showcases a complete end-to-end HR Analytics solution built using SQL, Power BI, Tableau, and Excel.
The goal of this dashboard is to help organizations understand attrition trends, employee demographics, and job satisfaction patterns through interactive visual analytics.

🔍 **Project Overview**

Employee attrition is one of the major challenges HR teams face. This project analyzes employee data to uncover trends in:

- Attrition count & rate

- Department-wise attrition

- Age-wise and gender-wise attrition

- Job satisfaction analysis

- Education field impact

- Workforce distribution

- Employee count, active employees, average age

The project helps HR teams make data-driven decisions such as improving retention strategies, understanding workforce pain points, and optimizing recruitment.

| Tool                         | Purpose                                                                  |
| ---------------------------- | ------------------------------------------------------------------------ |
| **SQL (MySQL / PostgreSQL)** | Data cleaning, validation, KPI computation, generating aggregated tables |
| **Power BI**                 | Interactive dashboard creation, DAX formulas, modeling                   |
| **Tableau**                  | Additional visualization experiments                                     |
| **Excel**                    | Data preprocessing, exploration, format adjustments                      |
| **Power Query**              | Data transformations inside Power BI                                     |

📈 **Key Metrics (KPIs)
**

The dashboard highlights the following HR performance indicators:

- Overall Employees

- Attrition Count

- Attrition Rate (%)

- Active Employees

- Average Employee Age

These KPIs provide a quick overview of workforce health.

🖼️** Dashboard Snapshots
**

<img width="941" height="531" alt="image" src="https://github.com/user-attachments/assets/acd82b77-89e1-4257-8077-41afb7256982" />

<img width="832" height="512" alt="image" src="https://github.com/user-attachments/assets/b6e19622-96c5-4a50-8afe-c7cdc90254a1" />


📊 **Dashboard Features**

1️⃣ **Department-Wise Attrition**

A pie chart showing attrition distribution across HR, Sales, R&D, etc.

2️⃣ **Employee Distribution by Age Group**

Bar chart and gender breakdown showing how workforce is spread across age bands.

3️⃣ **Job Satisfaction Rating Matrix**

Heatmap displaying satisfaction levels (1 to 4) by job role.

4️⃣ Education Field Wise Attrition

Bar chart comparing which education background has higher attrition.

5️⃣ **Attrition by Age & Gender
**
Donut charts highlighting which age groups and genders show higher turnover.

6️⃣** Dynamic Filters**

- Education level

- Gender

- Age group

- Job role

- Department
  
 🛠️** Data Cleaning & Transformation
  **

**SQL Tasks Performed**

- Handling NULL values

- Creating age bands

- Calculating attrition percentage

- Using CASE WHEN for pivot tables

- Running aggregation queries (GROUP BY, COUNT, SUM)

- Creating validated data outputs for visualization




**Power BI Tasks Performed**



- Data modeling using relationships

- Calculated columns & DAX measures

- Creating custom tooltips

- Designing interactive visuals

- Implementing slicers & filters

- Formatting dashboard with UX best practices


📚 Important DAX Measures

- Attrition Rate = DIVIDE([Attrition Count],[Total Employees],0)

- Active Employees = [Total Employees] - [Attrition Count]

- Age Group =
SWITCH(
    TRUE(),
    [Age] < 25, "Under 25",
    [Age] >= 25 && [Age] < 35, "25 - 34",
    [Age] >= 35 && [Age] < 45, "35 - 44",
    [Age] >= 45 && [Age] < 55, "45 - 54",
    "Over 55"
)


🧾 **Project Objectives**

- Build a full HR Analytics workflow from raw data → cleaned data → KPIs → Dashboard

- Demonstrate proficiency in SQL, Power BI, Tableau & Excel

- Present insights that support HR decision-making

- Showcase end-to-end data analysis capability for portfolio purposes


🎯 **Insights & Recommendations**

Sales department shows highest attrition → training & retention strategy needed

Younger employees (< 35) show higher turnover → onboarding improvements recommended

Job roles with low satisfaction scores correlate with higher attrition

Education fields like Life Sciences & Technical Degrees show significant exits


📁** **Repository Structure****

📂 HR_Analytics_Dashboard

│── 📁 Data

│── 📁 SQL Scripts

│── 📁 Power BI File (.pbix)

│── 📁 Tableau Workbook (optional)

│── 📁 Images (dashboard screenshots)

│── README.md



A complete HR analytics solution that transforms employee data into meaningful insights for improving retention and workforce planning.



