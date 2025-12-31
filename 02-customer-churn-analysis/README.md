# Customer Churn & Retention Analysis

## Project Overview
This project analyzes customer churn data for a subscription-based business to identify key drivers of customer attrition and provide actionable insights to improve retention. The analysis focuses on customer behavior, tenure, usage patterns, and plan types to help the business reduce churn and protect recurring revenue.

---

## Business Problem
Customer churn has a direct impact on revenue and growth. Management wants to understand:
- The overall churn rate
- Which customer segments churn the most
- Key factors contributing to churn
- How to identify customers at high risk of leaving

The goal is to use data to support **targeted retention strategies**.

---

## Objectives
- Calculate and monitor churn rates
- Identify churn patterns by customer segment
- Analyze the relationship between churn, tenure, usage, and pricing
- Highlight high-risk customers for proactive intervention

---

## Dataset Description
The dataset includes customer-level information such as:
- Customer ID
- Subscription plan
- Tenure
- Monthly charges
- Usage metrics
- Churn status (Yes/No)

Raw data is stored in the `data/raw` folder, while cleaned data is stored in `data/cleaned`.

---

## Tools Used
- **SQL** – data cleaning, transformation, and analysis  
- **Power BI** – data visualization and dashboards  

---

## Data Cleaning Steps
Key data preparation tasks performed using SQL include:
- Removal of duplicate customer records
- Standardization of churn labels
- Handling missing or invalid values
- Validation of numerical fields such as tenure and charges

SQL scripts can be found in the `sql/01_data_cleaning.sql` file.

---

## Analysis Approach
The analysis was conducted in the following stages:
1. **Exploratory Analysis**
   - Overall churn rate
   - Churn by plan type, tenure group, and usage level
2. **Business Analysis**
   - Cohort analysis based on customer tenure
   - Identification of high-risk customer segments
   - Estimation of revenue impact from churn

Relevant SQL scripts are organized in the `sql` folder.

---

## Power BI Dashboard
The Power BI dashboard provides:
- Churn KPIs and trends
- Churn breakdown by customer segment
- Identification of high-risk customers
- Interactive filters for deeper analysis

Dashboard screenshots are available in the `powerbi/dashboard_screenshots` folder.

---

## Key Insights
- New and low-tenure customers exhibit higher churn rates
- Certain subscription plans have consistently higher churn
- Lower usage levels are strongly associated with churn
- A small segment of customers contributes disproportionately to revenue loss

---

## Business Recommendations
- Improve onboarding experience for new customers
- Review pricing and features of high-churn plans
- Introduce targeted retention campaigns for at-risk customers
- Monitor churn indicators regularly using dashboard
