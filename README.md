# Telecom-Customer-Churn-Analysis
Telecom customer churn analysis and dashboard using Power BI

Introduction

Customer churn occurs when a customer stops using a company's services. It is an important concern for telecom companies because losing customers can result in customer loss and potential revenue loss. Understanding customer churn helps businesses identify customer behavior patterns and improve customer retention.

This project focuses on analyzing telecom customer churn using Power BI. The analysis covers customer demographics, service subscriptions, contracts, tenure, and billing behavior. The main purpose is to understand customer churn patterns, identify customer segments with higher churn, and provide insights that can support better business decisions.

📌 Business Problem

The telecom company wants to understand why customers leave its services and which customer segments are more likely to discontinue their subscriptions. The company also needs to examine how different services, contract types, and payment methods are associated with customer churn. In addition, understanding the potential revenue impact of churn is important for planning effective customer retention strategies.

Power BI is used in this project to analyze the customer data and present the results through interactive visualizations. These insights can help the company understand churn-related patterns and identify areas that may require improvement.

🎯 Project Objectives

The objective of this project is to analyze customer demographics and tenure to understand how customer characteristics relate to churn. It also examines service subscriptions, contract types, and billing behavior to identify patterns among customers who leave the company. The project aims to identify important churn-related factors, recognize customer segments with higher churn, and understand the potential revenue impact of customer loss.

Another objective is to develop an interactive Power BI dashboard that presents key performance indicators and analytical findings in an understandable format. The results are used to suggest business recommendations that may help improve customer retention.

📋 Dataset Description

This project uses the Telco Customer Churn dataset, which contains 7,043 customer records and 21 fields in CSV format. The dataset includes information about customer demographics, subscribed services, contract details, billing information, tenure, and churn status.

Important fields include Customer ID, Gender, Senior Citizen, Tenure, Phone Service, Internet Service, Contract, Payment Method, Monthly Charges, Total Charges, and Churn. These fields help analyze customer characteristics and compare churn patterns across different customer groups.

Data Cleaning and Transformation

The dataset was imported into Power Query for data preparation. Column data types were checked and corrected where necessary, and missing or invalid values were examined. Numerical and categorical fields were prepared for analysis, and tenure ranges were created to group customers according to their length of service. Service-related fields were also prepared to support comparisons across different subscription types.

The overall workflow followed in this project is Raw CSV Data, Power Query, Data Cleaning and Transformation, Data Model, DAX Measures, and Power BI Dashboard. This process prepares the dataset for analysis and helps present the results through meaningful visualizations.

DAX Measures

DAX was used to calculate important measures required for the analysis. These include Customer Count, Churned Customers, Churn Rate, Average Monthly Charges, Average Tenure, Average Total Charges, and Churn Risk Score. These measures help summarize customer information, evaluate churn performance, and compare different customer segments.

The calculated measures are displayed through KPI cards and charts to make the analysis easier to understand. They also help users explore churn patterns across demographic, service, contract, and billing categories.

Overall Dashboard

![Overall Dashboard](https://github.com/user-attachments/assets/36de8d69-c670-439f-a6cd-80877de928d5)

Customer Demographics Analysis

The Customer Demographics Analysis section examines the distribution of customers by gender and senior citizen status. It also analyzes customer distribution across tenure ranges and compares churn rates among customers with different lengths of service. Average monthly charges are examined in relation to tenure, including comparisons by gender.

Interactive demographic filters allow users to explore specific customer groups and understand how customer characteristics and tenure are associated with churn patterns.                                                                                                                                                          

![Customer Demographics Analysis](https://github.com/user-attachments/assets/49b00b0e-0cb1-45d5-aeec-177007cf68cc)

Service Subscription Analysis

The Service Subscription Analysis section examines phone service usage, internet service types, and additional services subscribed to by customers. It analyzes churn rates across Fiber Optic, DSL, and customers without internet service. The dashboard also explores add-on services used by churned customers, service counts, and combinations of services associated with churn.

The analysis indicates that Fiber Optic customers have a relatively higher churn rate in the reported results. The approximate churn rates shown in the project are 41.9% for Fiber Optic, 19.0% for DSL, and 7.4% for customers without internet service. These comparisons help identify service categories that may require further investigation.

Interactive service filters allow users to explore different service categories and examine how churn patterns vary across customer groups.
![Service Subscription Analysis](https://github.com/user-attachments/assets/84ffd83a-e0bc-40e8-88e4-111a4f7a0ff0)

Contract and Billing Analysis

The Contract and Billing Analysis section studies customer churn across different contract types and payment methods. It examines average total charges by contract, monthly charges by payment method, paperless billing in relation to churn, and tenure distribution across contract categories.

Billing-related KPIs and interactive filters help users compare customer groups and explore how contract and billing characteristics are associated with churn. The results can support further investigation into contract preferences, payment experiences, and potential opportunities to improve customer retention.
![Contract and Billing Analysis](https://github.com/user-attachments/assets/91f4387b-edee-4cf3-adc8-f8ffa4941331)


Churn Prediction and Key Drivers

The Churn Prediction and Key Drivers section focuses on factors associated with higher customer churn. The factors examined include month-to-month contracts, Fiber Optic internet service, electronic check payments, short customer tenure, paperless billing, and the senior citizen segment.

A rule-based Churn Risk Score is used to identify customers who have multiple churn-related factors. This score supports segment-based risk analysis and helps highlight customers who may need additional attention. It is a rule-based scoring method and not a machine-learning prediction model.
![Churn Prediction and Key Drivers](https://github.com/user-attachments/assets/0a776c3b-6d37-44f1-8971-5104ff1bec75)

Key Findings

The analysis indicates that month-to-month customers experience the highest churn among contract categories, while customers with shorter tenure show higher churn. Fiber Optic customers and customers using electronic check payments also show relatively higher churn in the reported analysis. Customers with multiple churn-related factors may represent higher-risk segments that deserve further investigation.

The overall churn rate presented in the project is approximately 26.5%. Customer churn can also have a potential revenue impact because the company may lose future revenue when customers discontinue their services. These findings help identify areas where additional customer retention efforts may be useful.

Business Recommendations

Based on the analysis, the company could encourage customers to consider longer-term contracts by providing suitable benefits and offers. Improving onboarding and support for new customers may help address issues experienced during the early stages of service. Targeted retention offers could also be considered for customer segments with several churn-related factors.

The company could further investigate Fiber Optic pricing and service quality, review the electronic-check payment experience, and monitor churn patterns regularly through Power BI. These recommendations are intended to support customer retention and help reduce potential customer and revenue loss.

Conclusion

This project demonstrates how Power BI can be used to analyze telecom customer churn and present business insights through interactive dashboards. Power Query was used for data cleaning and transformation, DAX was used for calculations and key performance indicators, and Power BI was used to visualize the results.

The analysis identified important churn-related patterns involving month-to-month contracts, short tenure, Fiber Optic internet service, and electronic check payments. Based on these findings, business recommendations were developed to help the company investigate high-churn customer segments, improve customer retention, and reduce potential revenue loss.

Tools and Technologies

Power BI was used to develop the dashboard and visualize customer churn patterns. Power Query was used to prepare and transform the dataset, while DAX was used to calculate measures and key performance indicators.

Project Files

The repository contains the Power BI report file and dashboard screenshots that illustrate the analysis and visualizations.

Dataset Source

The project uses the Telco Customer Churn dataset. The original dataset source link should be included here.

Disclaimer

The Churn Risk Score used in this project is rule-based. It should not be interpreted as a machine-learning prediction or as a guarantee that a customer will leave the company.

Author
Mohammad.Mariyambi

