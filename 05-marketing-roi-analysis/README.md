# Marketing Campaign ROI Analysis

## Project Overview
This project analyzes marketing campaign data to evaluate the effectiveness of marketing spend across different channels and campaigns. The goal is to measure return on investment (ROI), identify high-performing marketing channels, and provide insights to optimize future marketing budgets.

---

## Business Problem
Marketing teams invest heavily across multiple channels, but not all campaigns deliver equal value. Management needs clear answers to:
- Which marketing campaigns generate the highest ROI?
- Which channels drive the most conversions and revenue?
- Where is marketing spend being wasted?
- How should budgets be reallocated to maximize impact?

This analysis supports **data-driven marketing decisions**.

---

## Objectives
- Measure marketing performance using ROI and efficiency metrics
- Compare campaign and channel effectiveness
- Identify underperforming and high-performing campaigns
- Recommend budget optimization strategies

---

## Dataset Description
The dataset contains marketing campaign data including:
- Campaign name
- Marketing channel (e.g., email, social, search)
- Advertising spend
- Impressions and conversions
- Revenue generated

Raw and cleaned datasets are stored in the `data` directory.

---

## Tools Used
- **SQL** – data cleaning, aggregation, and performance analysis  
- **Power BI** – dashboard creation and visualization  

---

## Data Cleaning Steps
Data preparation tasks performed using SQL include:
- Handling missing or invalid spend and revenue values
- Standardizing marketing channel names
- Validating conversion metrics
- Ensuring consistent campaign identifiers

Data cleaning logic is documented in `sql/01_data_cleaning.sql`.

---

## Analysis Approach
The analysis was conducted in the following stages:

1. **Exploratory Marketing Analysis**
   - Total spend and revenue by campaign
   - Conversion rates and cost per acquisition (CPA)
   - Channel-level performance comparison

2. **Business Performance Analysis**
   - ROI calculation by campaign and channel
   - Marketing efficiency ranking
   - Conversion funnel analysis

SQL scripts supporting the analysis are organized in the `sql` folder.

---

## Power BI Dashboard
The Power BI dashboard includes:
- Marketing performance KPIs
- Campaign ROI comparison
- Channel efficiency analysis
- Conversion funnel visualization
- Interactive filters for deeper insights

Dashboard screenshots are available in the `powerbi/dashboard_screenshots` folder.

---

## Key Insights
- A small number of campaigns generate the majority of marketing ROI
- Certain channels consistently outperform others in cost efficiency
- Some campaigns have high spend but low conversion impact
- Optimizing channel mix can significantly improve overall ROI

---

## Business Recommendations
- Increase budget allocation to high-ROI channels
- Reduce or pause underperforming campaigns
- Test and refine messaging in low-conversion campaigns
- Continuously monitor campaign performance using dashboard
