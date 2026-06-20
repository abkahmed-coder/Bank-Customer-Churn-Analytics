# Bank Customer Churn Analytics Dashboard

## Project Overview

This project presents an interactive Power BI dashboard designed to analyze customer churn in a retail banking environment. The objective is to identify customer segments with a higher likelihood of leaving the bank and uncover the factors contributing to customer attrition.

The dashboard combines customer demographic and account information to provide insights into churn behavior across multiple dimensions, including age, balance, tenure, product ownership, gender, and geography. Through interactive visualizations and KPI tracking, the analysis helps stakeholders understand customer retention challenges and identify opportunities to improve customer loyalty.

This project demonstrates skills in data cleaning, data modeling, DAX calculations, data visualization, and business insight generation using Power BI.

---

## Business Problem

Customer churn is a significant challenge for financial institutions, as acquiring new customers is often more costly than retaining existing ones. Understanding why customers leave and identifying high-risk segments can help organizations develop targeted retention strategies and improve long-term profitability.

This analysis aims to answer the following questions:

* Which customer groups are most likely to churn?
* How does account balance influence churn behavior?
* Does product ownership impact customer retention?
* Which age groups and countries experience the highest churn?
* What customer segments should be prioritized for retention efforts?

---

## Dataset Information

The dataset consists of two sheets containing customer demographic, financial, and account-related information used to analyze customer churn behavior.

### Customer Information

* Customer ID
* Surname
* Credit Score
* Geography
* Gender
* Age
* Tenure
* Estimated Salary

### Account Information

* Customer ID
* Balance
* Number of Products
* Credit Card Status
* Active Member Status
* Churn Status (Exited)

The dataset contains approximately 10,000 customer records and was modeled using Customer ID as the primary key to combine customer and account information.

---

## Tools Used

* Power BI – Data Modeling, Dashboard Development, and Data Visualization
* Power Query – Data Cleaning and Transformation
* DAX – Creation of calculated columns, measures, KPIs, and customer segmentation groups
* Excel / CSV – Source Data Storage

---

## Data Modeling

A data model was created by linking the Customer Information and Account Information tables using the Customer ID field.

Additional DAX calculations were developed to support analysis and reporting, including:

### DAX Measures

* Total Customers
* Active Customers
* Churned Customers
* Churn Rate

### DAX Calculated Columns

* Age Group Classification
* Balance Group Classification
* Additional segmentation fields used for dashboard analysis

---

## Key Metrics

The dashboard tracks the following key performance indicators:

* Total Customers: 9,997
* Active Customers: 7,963
* Churned Customers: 2,037
* Churn Rate: 20%

---

## Dashboard Features

The dashboard provides multiple analytical views to explore customer churn:

* Customer Churn by Country
* Customer Churn by Gender
* Customer Churn by Age Group
* Customer Churn by Balance Group
* Customer Churn by Number of Products
* Customer Churn by Tenure
* KPI Summary Cards for customer retention performance

---

## Interactive Features

The dashboard includes dynamic filtering capabilities that allow users to explore churn patterns across different customer segments:

* Country Filter
* Gender Filter
* Number of Products Filter

These filters dynamically update all KPIs and visualizations, enabling deeper analysis of customer churn trends.

---

## Key Insights

### Product Ownership and Churn

Customers holding only one product account represent the majority of churned customers, suggesting that lower product adoption and engagement may increase the likelihood of customer attrition.

### High-Value Customer Risk

High-value customers are the most vulnerable to churn. The 71K–92K balance group recorded the highest churn, while customers with four products exhibited a 100% churn rate, indicating a potential loss of highly engaged and profitable customers.

### Age-Based Churn Patterns

Customers aged 41–50 years represent the highest churn segment, making this demographic a key target for customer retention initiatives.

---

## Business Recommendations

### Increase Customer Engagement

Implement cross-selling strategies to encourage single-product customers to adopt additional banking services and increase customer loyalty.

### Retain High-Value Customers

Develop personalized retention programs for customers with high account balances and multiple products to reduce the risk of losing profitable customer segments.

### Target High-Risk Age Groups

Create tailored marketing and customer engagement campaigns aimed at customers aged 41–50 years to improve retention rates.

### Investigate Multi-Product Customer Churn

Conduct further analysis on customers holding four products to identify the factors contributing to the observed 100% churn rate.

---

## Dashboard Snapshot

*Insert dashboard screenshot here.*

---

## Conclusion

The analysis reveals that customer churn is concentrated among specific customer segments, particularly single-product customers, customers aged 41–50 years, and high-value customers with balances between 71K and 92K. The finding that customers with four products exhibited a 100% churn rate highlights an area requiring further investigation.

By leveraging these insights, the bank can develop targeted retention strategies, improve customer engagement, and reduce customer attrition, ultimately supporting long-term business growth and profitability.
