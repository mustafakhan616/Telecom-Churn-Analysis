# Telecom Customer Churn Analysis

This project analyzes customer churn in a telecom company using a dataset of 7043 customers with 33 variables. The goal is to understand **who is leaving, why, and how it impacts revenue**, and to provide **retention strategies**.

## Key Highlights

- **Overall Churn Rate:** 26% of customers churned.
- **Churn Drivers:** Month-to-month contracts, Fiber Internet, Senior Citizens, and Tenure.
- **Revenue Impact:** Mid-tenure non-senior customers using Fiber on month-to-month contracts cause the largest revenue loss, even if churn rate is lower than early churners.
- **Churn Reasons:** Poor support experience, competitor offers, higher download speeds; price was not the main driver.
- **Analysis Techniques:** Data exploration, segmentation analysis (Contract × Tenure × Internet Service × Senior Citizen), correlation analysis, revenue impact, churn reason analysis.
- **Visualizations:** Bar charts, pie charts, heatmaps, annotated tables to highlight churn and revenue loss patterns.
- **Retention Strategies:** Segment-based recommendations:
  - Mid-tenure non-senior Fiber users → proactive loyalty offers, add-ons, premium support
  - Early-tenure senior Fiber users → simplified onboarding and personalized guides

## Tools & Technologies

- Python: pandas, NumPy, matplotlib, seaborn
- Power BI: KPIs, segmented dashboards, revenue heatmaps
- Data analysis, visualization, and business insight generation

## Insights

- Early churn is high but revenue impact is largest in mid-tenure customers.
- Senior customers have higher churn rate but less revenue loss.
- Non-senior Fiber month-to-month users are the **highest-value churn risk segment**.
- Churn is mostly driven by **support quality and competitor offers**, not price.

## Usage

- Clone the repository.
- Use the Python notebooks to explore the dataset.
- Visualizations saved in `/output` folder.
- Apply segment-based retention strategies based on analysis.
