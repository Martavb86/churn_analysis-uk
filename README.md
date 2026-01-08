# Telecom Customer Churn Analysis - UK

## Project Overview
This project analyzes customer churn in a UK-based telecommunications company. The goal is to identify patterns and factors that contribute to customer churn and provide actionable recommendations to reduce it.

## Dataset
- Source: [Telco Customer Churn Dataset](https://www.kaggle.com/blastchar/telco-customer-churn)
- Rows: 7043
- Columns: 21
- Features include contract type, internet service, payment method, tenure, monthly charges, and whether the customer churned.

## Tools and Technologies
- Python (pandas, numpy, matplotlib, seaborn, plotly)
- SQL (SQLite)
- GitHub for version control and project documentation

## Project Steps

1. **Data Cleaning**
   - Handled missing values in `TotalCharges`.
   - Converted data types and standardized columns.

2. **Exploratory Data Analysis (EDA)**
   - Visualized churn distribution.
   - Analyzed churn by contract type, internet service, payment method, and gender.
   - Created correlation matrix for numerical variables.
   - Saved all visualizations to `visuals/` folder.

3. **Insights**
- Customers on month-to-month contracts have a higher risk of churn compared to annual contracts.
- Customers using Fiber optic internet service are more likely to churn than those with DSL.
- Customers paying with electronic check tend to churn more frequently than other payment methods.
- Gender does not show a significant impact on churn.

4. **High-Risk Customer Segmentation**
   - Identified high-risk customers: month-to-month contracts with Fiber optic internet.
   - Saved high-risk customer list for further analysis: `data/processed/high_risk_customers_uk.csv`.

5. **Business Recommendations**
- Offer retention incentives for customers on month-to-month contracts.
- Provide proactive support and personalized offers for customers with Fiber optic internet.
- Review payment methods and consider strategies to reduce churn among electronic check users.
- Focus retention strategies on service and contract type rather than demographics like gender.

## Folder Structure

churn-analysis-uk/
│── data/
│ ├── # Original dataset
│ └── processed/ # Cleaned dataset & high-risk customers
│── notebooks/ # Step-by-step Jupyter notebooks
│── visuals/ # Visualizations and charts
│── README.md # Project overview and insights


## Outcome
This project demonstrates end-to-end data analysis skills: cleaning messy data, exploring patterns, generating actionable insights, segmenting high-risk customers, and producing professional visualizations. It is aimed at a UK audience and is suitable for showcasing in a data analyst portfolio.
