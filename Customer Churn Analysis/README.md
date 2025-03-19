# Telecom Customer Churn Analysis

## Overview
This project focuses on analyzing customer churn in a telecom company. Churn refers to customers who have discontinued their service, and understanding the reasons behind it can help the company improve retention strategies. The dataset used contains customer details such as tenure, internet service type, phone service, security features, and whether they have churned or not.

## Objectives
- Identify key factors influencing customer churn.
- Visualize patterns in customer behavior.
- Compare service usage between churned and retained customers.
- Provide actionable insights for improving customer retention.

## Data Analysis and Insights
1. **Tenure Analysis:** Customers with very short tenure (1-2 months) have the highest churn rate, whereas long-term users tend to stay.
2. **Service Type Analysis:** Customers using fiber optic internet have a higher churn rate compared to DSL users.
3. **Security Features:** Customers without online security, backup, or device protection services are more likely to churn.
4. **Streaming Services:** Customers who subscribe to streaming services (TV & Movies) have lower churn rates.
5. **Phone and Multiple Lines:** Customers with phone services and multiple lines show a mixed trend in churn rates.
6. **Tech Support:** Customers who opt for tech support services are more likely to stay.

## Tools and Technologies Used
- **Python** for data processing and analysis.
- **Pandas & NumPy** for data manipulation.
- **Matplotlib & Seaborn** for data visualization.
- **Jupyter Notebook** for interactive exploration.

## Key Visualizations
- **Histograms & Count Plots:** Used to analyze tenure distribution and compare churn vs. non-churn.
- **Stacked Bar Charts:** Show service preferences among churned and non-churned customers.
- **Correlation Heatmaps:** Identify relationships between different customer attributes.

## Conclusion
From the analysis, it is evident that new customers (tenure < 2 months) are more likely to churn. Providing better onboarding experiences, offering discounts, and ensuring high-quality service can help reduce churn rates. Security services and technical support also play a significant role in customer retention. Further analysis could involve building predictive models to identify customers at high risk of churn.

## Future Work
- Implement a predictive model to classify high-risk churn customers.
- Perform deeper segmentation to identify customer personas.
- Investigate customer feedback data for sentiment analysis.