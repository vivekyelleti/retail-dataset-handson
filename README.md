# RetailMax
A guided Python exercise on identifying, analysing, and treating missing values in a retail customer dataset. 

## Business Question

RetailMax is a multi-channel retail company serving customers through online, store, and omnichannel channels. The company has invested heavily in customer acquisition, loyalty programs, and category expansion to drive growth. Management is concerned that while customer activity and spending appear healthy, overall profitability is not meeting expectations. The executive team wants to identify the key factors influencing profitability and determine what actions should be prioritized.

# RetailMax Customer Data: Feature Metadata

## Dataset Overview

- **Dataset:** `RetailMax_Customer_Data.csv`
- **Domain:** Retail customer analytics
- **Unit of analysis:** One customer per row
- **Purpose:** Teaching data quality, missing-value handling, KPI analysis, and business interpretation
- **Currency:** Indian Rupees (INR)

## Feature Dictionary

| Feature | Data Type | Description | Unit / Values | Analytical Role |
|---|---|---|---|---|
| `Customer_ID` | String | Unique customer identifier | `RM0001`, `RM0002`, etc. | Identifier; exclude from numerical modelling |
| `Age` | Numeric | Customer age | Years | Customer profile and segmentation |
| `Annual_Income_INR` | Numeric | Estimated annual income | INR | Affluence and purchasing-power analysis |
| `Region` | Categorical | Customer's geographic region | North, South, East, West, Central | Regional comparison |
| `Preferred_Channel` | Categorical | Customer's primary buying channel | Store, Online, Omnichannel | Channel-behaviour analysis |
| `Loyalty_Status` | Categorical | Customer loyalty-program tier | None, Silver, Gold, Platinum | Loyalty and retention analysis |
| `Primary_Category` | Categorical | Customer's main purchase category | Grocery, Fashion, Electronics, Home, Beauty | Category preference analysis |
| `Purchase_Frequency` | Numeric | Number of purchases during the year | Count | Engagement and purchase-intensity analysis |
| `Average_Basket_Value_INR` | Numeric | Average value of a customer transaction | INR | Transaction-value analysis |
| `Annual_Spend_INR` | Numeric | Estimated annual customer spending | INR | Revenue and customer-value analysis |
| `Average_Discount_Rate` | Numeric | Average discount received by the customer | Percentage | Promotion and discount analysis |
| `Return_Rate` | Numeric | Proportion of purchases returned | Percentage | Return behaviour and profitability risk |
| `Customer_Satisfaction_10` | Numeric | Customer satisfaction rating | 1-10 scale | Customer-experience analysis |
| `Estimated_Gross_Profit_INR` | Numeric | Estimated annual gross-profit contribution | INR | Customer profitability analysis |
| `Estimated_Profit_Margin` | Numeric | Estimated gross profit relative to annual spend | Percentage | Margin and profitability analysis |

## Feature Groups

### Customer Profile

- `Customer_ID`
- `Age`
- `Annual_Income_INR`
- `Region`

### Customer Engagement

- `Preferred_Channel`
- `Loyalty_Status`
- `Purchase_Frequency`

### Purchase Behaviour

- `Primary_Category`
- `Average_Basket_Value_INR`
- `Annual_Spend_INR`
- `Average_Discount_Rate`

### Customer Experience

- `Return_Rate`
- `Customer_Satisfaction_10`

### Financial Performance

- `Estimated_Gross_Profit_INR`
- `Estimated_Profit_Margin`

## Missing-Value Exercise

The teaching dataset contains incomplete observations in selected fields, including:

- `Age`
- `Annual_Income_INR`
- `Loyalty_Status`
- `Return_Rate`
- `Customer_Satisfaction_10`

These fields support exercises involving missing-value audits, pattern analysis, complete-case deletion, simple imputation, sensitivity checks, and assessment of KPI consequences.


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
