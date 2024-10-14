# Credit Score Analysis Project

## Overview
This project focuses on analyzing customer credit data, conducting thorough exploratory data analysis (EDA), feature engineering, and developing a hypothetical credit score. The primary goal is to create an insightful credit scoring model that can guide risk assessment and creditworthiness evaluation.

## Project Structure
The project is structured as follows:

- **EDA**: Detailed analysis to understand the distribution and relationships among key variables such as age, income, number of loans, and outstanding debt.
- **Feature Engineering**: Creating additional features like Debt-to-Income Ratio, Credit Age in Months, Monthly Savings Rate, and Credit Utilization Level to better assess creditworthiness.
- **Credit Score Calculation**: A hypothetical credit scoring model inspired by FICO scores is developed. Various features are assigned weights to calculate scores ranging from 0 to 100.
- **Summary and Insights**: Key findings from the analysis are summarized, highlighting factors influencing credit scores and insights useful for risk assessment.

## Features Created
- **Debt-to-Income Ratio**: Represents the proportion of debt to income.
- **Credit Age in Months**: Derived from the credit history age.
- **Monthly Savings Rate**: Represents the proportion of monthly income left after EMI payments.
- **Credit Utilization Level**: A categorical feature indicating how much of the credit limit is being utilized.

## Hypothetical Credit Score
The credit score model considers the following factors:
- **Payment History**: Weighted at 35%.
- **Credit Utilization**: Weighted at 30%.
- **Credit History Length**: Weighted at 15%.
- **Debt-to-Income Ratio**: Weighted at 10%.
- **Monthly Savings Rate**: Weighted at 10%.

The scoring system ranges from 0 to 100, where a higher score indicates better creditworthiness.

## Key Insights
- **Payment History** and **Credit Utilization** were found to be the most important factors.
- Customers with low debt-to-income ratios and high savings rates tended to have better credit scores.
- Identifying risk categories allows for targeted credit risk management strategies.

## Usage
To use this project:
1. Clone the repository.
2. Open the Jupyter notebook and run through each cell to replicate the analysis.
3. Refer to the summary report at the end of the notebook for insights and next steps.

## Requirements
- Python 3.x
- Pandas, NumPy, Matplotlib, Seaborn for data analysis and visualization.

## Conclusion
This project successfully demonstrates the development of a credit scoring model using customer data, offering insights into creditworthiness evaluation. Future work could involve applying machine learning techniques to further refine the scoring model and improve accuracy.

## Next Steps
- Explore machine learning models to improve the credit scoring system.
- Develop strategies for segmenting customers into risk categories and provide personalized credit improvement recommendations.

