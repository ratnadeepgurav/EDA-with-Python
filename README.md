# Telecom Churn Analysis

This project presents an analysis of customer churn in a telecom service provider, focusing on identifying factors that contribute to customers leaving the service. It involves Exploratory Data Analysis (EDA) using **Python**, leveraging **Seaborn**, **Matplotlib**, and **Pandas** for data visualization and insights.

## Executive Summary

The analysis explores the behavior and characteristics of telecom customers to identify patterns linked to churn. A series of visualizations have been created to better understand the distribution of churn across various customer attributes.

### Key Insights

1. **Churn Distribution**:
   - Approximately **26.58%** of the customers in the dataset have churned, as shown by the pie chart in the analysis.

2. **Churn by Gender**:
   - Churn rates appear to be fairly similar across **male** and **female** customers, suggesting that gender does not significantly impact churn.

3. **Churn by Senior Citizen Status**:
   - **Senior Citizens** tend to have a higher churn rate compared to non-senior citizens, as highlighted in the comparison plot.

4. **Tenure vs. Churn**:
   - Customers with shorter tenures (1–2 months) are more likely to churn, while those who have been with the company for a longer time are less likely to churn. A histogram visualization illustrates this trend.

5. **Contract Type**:
   - Customers with **month-to-month contracts** are far more likely to churn than those with **1-year** or **2-year contracts**, suggesting that longer contracts reduce churn.

6. **Payment Method**:
   - Customers who use **Electronic Check** as their payment method are more likely to churn compared to other payment methods (such as credit cards or bank transfers).

7. **Services and Churn**:
   - Additional insights show that customers without **internet-related services** or **technical support** are more prone to churn, indicating that bundled services could play a role in retaining customers.

## Visualizations

The analysis is supported by several insightful visualizations, including:
- **Churn Count and Percentage**: Bar and pie charts visualizing overall churn distribution.
- **Churn by Gender and Senior Citizen Status**: Grouped bar charts showing the churn rates across these demographics.
- **Tenure and Contract Type**: Histograms and count plots that display the impact of customer tenure and contract length on churn.
- **Payment Method and Services**: Visual representations of how payment methods and services like **Phone Service**, **Multiple Lines**, **Internet Service**, and **Tech Support** influence churn.

## Technologies Used

- **Python**
- **Pandas**
- **Seaborn**
- **Matplotlib**

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/telecom-churn-analysis.git
