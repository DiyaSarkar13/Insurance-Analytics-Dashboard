# Insurance Analytics Dashboard – Power BI & SQL Server

## Project Overview

This project is an interactive Insurance Analytics Dashboard built using Microsoft SQL Server and Power BI to analyze insurance policy, customer, premium, and claim-related data.

The objective of the project is to transform raw insurance data into meaningful business insights through data cleaning, transformation, visualization, and KPI reporting.

The dashboard provides insights into:
- Premium distribution across policy types
- Claim amount analysis
- Active vs inactive policy analysis
- Claim status trends
- Customer segmentation based on age groups
- Policy-wise performance metrics

---

# Project Workflow

```text
Raw Insurance Dataset (CSV)
        ↓
Imported into Microsoft SQL Server
        ↓
Connected SQL Server with Power BI
        ↓
Data Cleaning & Transformation using Power Query
        ↓
Created Conditional Columns and KPIs
        ↓
Built Interactive Dashboard & Visual Reports
```

---

# Technologies Used

- Microsoft SQL Server
- Power BI
- Power Query
- DAX (Data Analysis Expressions)
- SQL
- CSV Dataset

---

# Data Import & Database Handling

The raw insurance dataset was first imported into Microsoft SQL Server to simulate a real-world business intelligence workflow where data is stored and managed in a relational database system.

Power BI was then connected to SQL Server for data retrieval and dashboard creation.

---

# Data Cleaning & Transformation

Data transformation and preprocessing were performed using Power Query.

The following operations were carried out:
- Data validation and formatting
- Handling categorical data
- Creating conditional columns
- Structuring fields for analysis and visualization

## Conditional Columns Created

### 1. Age Group
Customers were categorized into:
- Young Adult
- Adult
- Elder

based on age ranges.

### 2. Active/Inactive Policy Status
Policies were classified as:
- Active
- Inactive

based on policy-related conditions.

---

# Dashboard Features

## KPI Cards
The dashboard includes KPI cards for:
- Premium Amount
- Coverage Amount
- Claim Amount

These KPIs provide quick high-level business insights.

---

## Interactive Filters / Slicers

The dashboard contains interactive slicers for:
- Policy Number
- Claim Number
- Customer ID

These slicers allow dynamic filtering and report interaction.

---

# Visualizations Included

## 1. Premium Amount by Policy Type
A bar chart showing premium contribution across different insurance policy categories:
- Travel
- Health
- Auto
- Life
- Home

---

## 2. Active vs Inactive Policies
A donut chart comparing the number of active and inactive policies.

---

## 3. Claim Amount by Age Group
A trend visualization showing claim amount distribution among different customer age groups.

---

## 4. Number of Claims by Claim Status
Analysis of claims categorized as:
- Rejected
- Settled
- Pending

---

## 5. Policy Type Claim Summary
A matrix report displaying claim status totals across different policy types.

---

# DAX & Analytical Operations

The dashboard uses DAX calculations and aggregation techniques for:
- KPI calculations
- Sum aggregations
- Count analysis
- Interactive filtering
- Business metric reporting

---

# Key Insights

Some business insights observed from the dashboard include:

- Travel insurance generated the highest premium amount among all policy types.
- Active policies represented a larger share compared to inactive policies.
- Adult customers contributed the highest claim amounts.
- Claim distribution varied significantly across policy categories and claim statuses.
- Rejected and settled claims formed a major portion of total claims.

---

# Business Value

This dashboard helps in:
- Monitoring insurance business performance
- Understanding customer and claim trends
- Identifying policy performance
- Supporting business decision-making through data visualization
- Improving reporting efficiency through interactive analytics

---

# Files Included

- `InsuranceDashboard.pbix` – Power BI dashboard file
- `InsuranceData.csv` – Dataset used in the project
- `README.md` – Project documentation
- `DashboardScreenshot.png` – Dashboard preview image

---

# Future Improvements

Potential future enhancements:
- Advanced DAX measures
- Time-series trend analysis
- Forecasting and predictive analytics
- Drill-through reports
- SQL query optimization
- Deployment to Power BI Service

---

# Conclusion

This project demonstrates the complete workflow of:
- Data storage using SQL Server
- Data transformation using Power Query
- Business analysis using Power BI
- Dashboard development using interactive visualizations and DAX

The dashboard was designed to simulate a practical business intelligence and reporting solution for insurance analytics.
