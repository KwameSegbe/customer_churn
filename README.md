# Customer Analytics: Understanding and Predicting Churn
Francis Kwame Segbe
# Project 4: Customer Analytics
This project delves into customer churn analysis, aiming to uncover patterns among various customer groups and their impact on business growth. By identifying behaviors and attributes that distinguish struggling customers from loyal ones, we aim to boost retention rates, optimize product-market fit, manage competition effectively, and increase overall revenue through strategic customer service and product improvements.

# Project Overview
Customer churn analysis stands at the core of enhancing customer retention and maximizing revenue. It involves a deep dive into the data to identify the driving factors behind customers' decisions to leave a service. This analysis leverages churn analytics to pinpoint issues leading to customer cancellations, enabling the development of targeted solutions to recapture lost revenue. Key strategies include evaluating pricing models, refining underperforming features, and realigning customer service approaches.

# Data Exploration and Preprocessing
The analysis begins with an exploratory data analysis (EDA) and data cleaning phase, utilizing a comprehensive dataset (Customer_Churn_Dataset.csv) encompassing various customer attributes and their churn status. Key steps in the data preprocessing include:
Binarization of the churn column for model compatibility, converting "Yes" to 1 and "No" to 0.
Conversion of categorical variables to numeric form using label encoding, facilitating their use in predictive modeling.
Application of MinMaxScaler to normalize selected features (tenure, MonthlyCharges, TotalCharges), enhancing model performance.

# Data Visualization & Insights
Through meticulous data visualization, we uncover the churn rates across different customer segments and services. Insights include:
A significant churn rate of 26% within the dataset, indicating a crucial area for improvement in customer retention strategies.
Gender-based churn analysis reveals men are slightly more likely to churn than women.

Customers lacking tech support show a higher propensity to churn, emphasizing the importance of quality customer support.

An exploration by internet service type found customers with fiber optic services more likely to churn than those with DSL or no internet service, highlighting potential dissatisfaction with certain service types.

Payment method analysis shows customers using electronic payment methods have a higher churn rate, suggesting a need for more flexible or appealing payment options.

# Model Training and Evaluation
The project evaluates several machine learning models, including Decision Tree, Logistic Regression, Random Forest, and Naive Bayes, for their effectiveness in predicting customer churn. Key findings from the model performance evaluation include:
The Logistic Regression model outperforms others with an accuracy of 80%, indicating its efficacy in correctly predicting churn and non-churn customers.
It offers a well-balanced precision and recall, particularly for identifying the critical minority class representing churned customers.
The model's strengths lie in its ability to balance churn detection ability, precision, recall, and F1 score, making it the preferred model for identifying customers at risk of churn.

# Deployment and Summary
The project concludes with recommendations for deploying the logistic regression model within a robust data pipeline on scalable infrastructure. This approach will integrate churn likelihood forecasts into business systems, enabling timely and effective retention campaigns.

# Summary
The analysis underscores the critical challenge of customer retention, with 26% of the customer base exhibiting churn. It highlights specific areas for intervention, such as improving tech support and incentivizing payment methods that are less associated with churn. The logistic regression model, with its superior accuracy and balance of predictive metrics, stands as the best tool for identifying at-risk customers and informing targeted retention strategies.
