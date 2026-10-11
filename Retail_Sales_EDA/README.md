# Retail Sales & Customer Behaviour Analysis

### Oasis Infobyte | Data Analytics Internship Project

**Analyst:** Opeyemi Obikoya  
**Tools:** Python, Pandas, Matplotlib, Google Colab  
**Project Type:** Exploratory Data Analysis (EDA)

## Project Overview

This project explores retail sales transactions and e-commerce customer behaviour to identify revenue trends, high-performing product categories, customer purchasing patterns, and opportunities for business improvement.

The analysis uses a dataset containing **5,000 transactions and 18 attributes**, covering January 2023 to March 2024.

## Project Objectives

- Analyse monthly and quarterly revenue trends.
- Identify the highest- and lowest-performing product categories.
- Examine revenue across customer demographics.
- Compare new and returning customers.
- Evaluate payment methods and shopping devices.
- Investigate relationships between customer engagement, satisfaction, and spending.
- Develop actionable business recommendations.

## Data Preparation

The dataset was inspected for missing values, duplicate records, data types, and invalid dates.

Initial checks identified:
- 5,000 records and 18 columns.
- No missing values.
- No duplicate rows.
- No invalid dates after conversion.

## Key Findings

### Product Performance

Electronics generated approximately **2.33 million** in revenue, making it the strongest-performing product category. Books generated approximately **72.7 thousand**, the lowest among the eight categories.

### Customer Behaviour

Returning customers generated approximately **2.95 million** in revenue, compared with **1.97 million** from new customers.

### Shopping Channels

Mobile devices generated approximately **2.81 million** in revenue, exceeding desktop and tablet transactions.

### Payment Preferences

Credit cards generated approximately **1.92 million** in revenue, followed by debit cards at approximately **1.25 million**.

### Customer Engagement

The correlation analysis revealed very weak linear relationships between session duration, pages viewed, delivery time, customer ratings, and transaction amounts. These results do not establish causal relationships.

## Business Recommendations

1. Maintain strong product availability in Electronics while investigating opportunities in lower-performing categories.
2. Strengthen customer retention through targeted offers and loyalty initiatives.
3. Prioritise mobile shopping experience and checkout usability.
4. Maintain reliable card-payment options while supporting digital wallets.
5. Test engagement and delivery improvements through controlled experiments.

## Project Notebook

[View the Python analysis notebook](OIBSIP_Retail_Sales_EDA.ipynb)

## Dataset Note

The analysis uses an e-commerce customer behaviour dataset sourced from Kaggle. Monetary values are presented without an assumed currency because the dataset does not specify one.

## Conclusion

This project demonstrates practical skills in data preparation, exploratory analysis, customer segmentation, data visualisation, and translating analytical findings into business recommendations.
