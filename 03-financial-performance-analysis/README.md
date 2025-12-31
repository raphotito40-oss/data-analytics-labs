# Financial Performance & Cost Optimization Analysis

## Project Overview
This project analyzes company financial data to evaluate overall financial performance, identify cost drivers, and uncover opportunities for cost optimization. The analysis supports management in improving profitability through better expense control and data-driven budget decisions.

---

## Business Problem
Despite stable revenue, management observed declining profit margins and increasing operational costs. The leadership team needs clear insights into:
- Revenue and expense trends over time
- Departmental spending patterns
- Budget vs actual performance
- Areas where costs can be optimized without harming operations

The objective is to enable **financial discipline and sustainable profitability**.

---

## Objectives
- Assess overall financial performance
- Identify departments with high or inefficient spending
- Compare budgeted vs actual expenses
- Highlight cost-saving opportunities and financial risks

---

## Dataset Description
The dataset contains financial and operational information such as:
- Revenue
- Operating expenses
- Departments
- Budgeted amounts
- Actual spending
- Time periods (monthly/quarterly)

Raw and cleaned datasets are stored in the `data` directory.

---

## Tools Used
- **SQL** – data cleaning, aggregation, and financial analysis  
- **Power BI** – interactive dashboards and financial reporting  

---

## Data Cleaning Steps
Data preparation tasks performed using SQL include:
- Handling missing or inconsistent financial values
- Standardizing department and cost category names
- Validating numeric fields for revenue and expenses
- Ensuring correct time period formatting

Cleaning logic is documented in `sql/01_data_cleaning.sql`.

---

## Analysis Approach
The analysis was structured into the following phases:

1. **Exploratory Financial Analysis**
   - Revenue, expense, and profit trends
   - Profit margin analysis
   - Expense distribution by department

2. **Business & Cost Analysis**
   - Budget vs actual variance analysis
   - Departmental cost efficiency ranking
   - Identification of high-growth cost categories

SQL scripts for each stage are organized in the `sql` folder.

---

## Power BI Dashboard
The Power BI dashboard provides:
- Financial performance overview (KPIs)
- Revenue vs expense trends
- Department-level cost breakdown
- Budget variance analysis with drill-down capabilities

Dashboard screenshots are available in the `powerbi/dashboard_screenshots` folder.

---

## Key Insights
- Certain departments consistently exceed budget allocations
- Operating expenses are growing faster than revenue in specific periods
- A small number of cost categories account for most overspending
- Profit margins can be improved through targeted cost controls

---

## Business Recommendations
- Introduce stricter budget monitoring for high-variance departments
- Reallocate spending toward high-ROI activities
- Review and renegotiate high-cost vendor contracts
- Establish periodic financial performance reviews using dashboards

---

## Project Structure
03-financial-performance-analysis/
├── data/
│ ├── raw/
│ └── cleaned/
├── sql/
├── powerbi/
├── docs/
└── README.md
