# HR Analytics Dashboard

A 4-page Power BI dashboard analyzing 10 years of workforce data — covering headcount growth, attrition vs. turnover, and salary/compensation trends across departments.

## 📊 Overview

This project explores employee lifecycle data from **2016 to 2026**, simulating a company that grows from roughly 150–200 employees to over 1,100. It's designed to surface realistic HR insights such as voluntary vs. involuntary attrition patterns, tenure-based termination risk, and compensation trends across roles and departments.

## 📁 Report Pages

- **Overview** — high-level KPIs and headcount trends
- **Employees Overview** — workforce composition by department, education, and demographics
- **Attrition & Turnover** — voluntary vs. involuntary termination analysis, tenure risk, and exit reason trends
- **Salary & Compensation** — pay bands by role tier, department, and compensation trends over time

## 🛠️ Tools Used

- **Power BI Desktop** — data modeling, DAX measures, report design
- **DAX** — custom measures for attrition rate, turnover rate, and headcount growth calculations

## 🔍 Key Design Decisions

- **Attrition Rate** is calculated from voluntary terminations only, while **Turnover Rate** combines voluntary and involuntary terminations — giving a clearer picture of controllable vs. total employee loss
- Involuntary terminations were modeled to skew toward employees with less than 1 year of tenure, reflecting realistic early-hire mismatches
- A full year-over-year headcount arc was built in, including a deliberate slowdown and increase in involuntary terminations during 2020–2021
- Education level is strictly correlated with job level — all Director and C-suite roles require a Master's degree, while frontline roles reflect a more realistic mix of education backgrounds

## 📷 Screenshots

**Overview Page**
<img width="1768" height="1108" alt="image" src="https://github.com/user-attachments/assets/a36cf050-94ab-4851-ac45-92c9fc81aca3" />

**Employees Page**
<img width="1770" height="1106" alt="image" src="https://github.com/user-attachments/assets/4889fe40-59af-451f-bb86-fcba3035e303" />

**Attrition & Turnover Page**
<img width="1768" height="1106" alt="image" src="https://github.com/user-attachments/assets/d3eb9704-c1ab-4917-bbb7-a4b70a6bceeb" />

**Salary & Compensation Page**
<img width="1768" height="1106" alt="image" src="https://github.com/user-attachments/assets/76285968-22e3-41f8-b16c-771a5c602a0a" />


## 📂 Files
[HR Analytics Dashboard.pbix](HR%20Analytics%20Dashboard.pbix)  — the full Power BI report file

