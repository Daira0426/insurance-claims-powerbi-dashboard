# Insurance Claims & Policyholder Risk Analysis Dashboard

## 📊 Project Overview

This project presents an interactive Power BI dashboard designed to analyze insurance claims and policyholder risk. The dashboard transforms raw insurance data into meaningful insights by tracking claim trends, customer demographics, regional distribution, and policy information.

The goal is to help stakeholders identify risk patterns, monitor key performance indicators (KPIs), and support data-driven decision-making.

---

## Dashboard Preview

<img width="1111" height="617" alt="Screenshot 2026-07-30 201043" src="https://github.com/user-attachments/assets/621dda44-568f-48a1-8b62-b6582c51911e" />


---

## Business Problem

Insurance companies need to understand claim behavior and customer risk profiles to improve decision-making, optimize pricing strategies, and identify high-risk segments.

This dashboard provides an easy-to-use analytical tool that enables users to:

- Monitor insurance claim activity.
- Compare claims across different regions.
- Analyze customer demographics.
- Evaluate claim severity.
- Explore the relationship between claim frequency and premium amount.

---

## Key Performance Indicators (KPIs)

- **Total Claims:** 4,972
- **Average Claims:** 0.50
- **Total Claims Adjustment:** 368K
- **Average Claim Amount:** 73.97
- **Total Records:** 10K

---

## Dashboard Features

### Interactive Filters

- Policy Type
- Region
- Source of Lead
- Marital Status

### Visualizations

- Claims Severity Distribution
- Claims by Region
- Claims Frequency vs Premium Amount
- Age Distribution by Claims Severity
- Claim Severity by Region

---

## Key Insights

- Low-severity claims represent the largest proportion of all insurance claims.
- Urban customers account for nearly half of all policyholders.
- Premium amounts generally increase as claim frequency rises.
- Most claims come from policyholders between 30 and 45 years old.
- Urban regions generate more claims than suburban and rural areas.

---

## Tools & Technologies

- **Power BI**
- **Power Query**
- **DAX**
- **Data Modeling**
- **Data Visualization**

---

## DAX Measures

Some of the measures created for this dashboard include:

```DAX
Total Claims = SUM(Table1[Claims_Frequency])

Average Claims = AVERAGE(Table1[Claims_Frequency])

Total Claims Adjustment = SUM(Table1[Claims_Adjustment])

Average Claim Amount =
DIVIDE(
    SUM(Table1[Claims_Adjustment]),
    SUM(Table1[Claims_Frequency]),
    0
)

Count of Records = COUNTROWS(Table1)
```

---

## Skills Demonstrated

- Data Cleaning
- Data Transformation with Power Query
- Data Modeling
- DAX Calculations
- KPI Development
- Interactive Dashboard Design
- Business Intelligence Reporting
- Data Storytelling

---

## Repository Structure

```
insurance-claims-powerbi-dashboard/
│
├── powerbi/
│   └── Insurance_Claims_Dashboard.pbix
│
├── dataset/
│   └── Insurance_Claims.csv
│
├── screenshots/
│   └── insurance-dashboard.png
│
└── README.md
```

---

## Project Outcome

This dashboard demonstrates the use of Power BI to transform insurance data into actionable business insights through interactive visualizations, dynamic filtering, and KPI reporting.

---

## Author

**Daira Chala Castillo**

Industrial Engineer | Marketing | Data Analyst

### Skills

- Power BI
- SQL
- Python (Pandas, NumPy)
- Excel
- Tableau
- Data Visualization
- Business Intelligence

---

## Contact

Feel free to connect with me on LinkedIn or explore my other data analytics projects on GitHub.
