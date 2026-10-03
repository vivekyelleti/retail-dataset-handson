# RetailMax: Mi
A guided Python exercise on identifying, analysing, and treating missing values in a retail customer dataset. 

## Business Question

**Can RetailMax trust its customer data when profitability decisions depend on incomplete records?**

## Learning Outcomes

Participants will learn to:

- Identify and quantify missing values
- Visualize missingness
- Examine missing-data patterns across customer channels
- Compare complete-case deletion and simple imputation
- Assess changes in business KPIs
- Develop a transparent managerial recommendation

## Repository Files

- `retailmax_missing_data_handling.py` — guided analysis code
- `RetailMax_Customer_Data.csv` — customer-level teaching dataset
- `RetailMax_Customer_Analytics_Cleaned.csv` — generated cleaned dataset

## Analysis Workflow

1. Load and inspect the dataset
2. Audit missing values
3. Examine missingness patterns
4. Establish baseline KPIs
5. Apply complete-case deletion
6. Apply median and `Unknown` imputation
7. Compare KPI consequences
8. Test mean versus median income imputation
9. Export the cleaned dataset

## Requirements

```bash
pip install pandas numpy matplotlib seaborn scikit-learn openpyxl
```

## Run

Keep the CSV and Python file in the same folder, then run:

```bash
python retailmax_missing_data_handling.py
```

## Key Message

> Data quality is a business issue, not merely a technical issue. Missing-data treatments should be selected based on the variable, likely cause of missingness, intended analysis, and cost of a wrong decision.

## Disclaimer

This dataset is intended for teaching and demonstration. Results should not be treated as evidence about an actual retail company or customer population.

## Topics

`python` `pandas` `missing-data` `data-cleaning` `customer-analytics` `retail-analytics` `business-analytics` `executive-education`
