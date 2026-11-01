# Customer Churn and Revenue Analysis using Pandas Numpy and Matplotlib



## Business Problem
A subscription company is losing customers every month. This project finds who is churning, why, and how much revenue is at risk, then recommends actions.

## Key Findings
- Overall churn rate: 27.6% (about $174K of monthly revenue lost)
- Month-to-month customers churn far more than two-year customers
- 40% of churners leave within their first 12 months
- Electronic-check payers churn at 33.1% vs 24.7% for other methods
- High-risk customers (rule-based score) churn at 63.6% vs 7.8% for low-risk


## Approach
1. Cleaned data with pandas (duplicates, `TotalCharges` type fix, missing values)
2. Calculated churn rate, revenue lost and customer lifetime value
3. Segmented customers by contract, tenure, payment method and service
4. Built a rule-based risk score with NumPy (`np.where`, `np.select`)
5. Estimated revenue saved from a retention campaign
6. Visualised results with matplotlib


## Data Source
telco_churn.csv
