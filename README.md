## Dataset Information

The dataset consists of two sheets containing customer demographic, financial, and account-related information used to analyze customer churn behavior.

### Customer Information
- Customer ID
- Surname
- Credit Score
- Geography
- Gender
- Age
- Tenure
- Estimated Salary

### Account Information
- Customer ID
- Balance
- Number of Products
- Credit Card Status
- Active Member Status
- Churn Status (Exited)

The dataset contains approximately 10,000 customer records and was modeled using Customer ID as the primary key to combine customer and account information.

---

## Tools Used

- **Power BI** – Data Modeling, Dashboard Development, Data Visualization
- **Power Query** – Data Cleaning and Transformation
- **DAX** – Creation of calculated columns, measures, and customer segmentation groups (Age Groups, Balance Groups, Churn Rate, KPI Measures, etc.)
- **Excel/CSV** – Source Data Storage

---

## Data Modeling

A star-schema-inspired model was created by linking the Customer Information and Account Information tables through the **Customer ID** field. 
Additional calculated columns and measures were developed using DAX to support advanced analysis and interactive reporting.

### DAX Implementations
- Churn Rate Measure
- Total Customers Measure
- Active Customers Measure
- Churned Customers Measure
- Age Group Classification
- Balance Group Classification
- Additional KPI and analytical measures for dashboard reporting

- ## Interactive Features

The dashboard includes dynamic filtering capabilities that allow users to explore churn patterns across different customer segments:

- **Country Filter** – Analyze churn metrics for specific countries.
- **Gender Filter** – Compare churn behavior between male and female customers.
- **Number of Products Filter** – Investigate how product ownership impacts customer retention.

These filters dynamically update all KPIs and visualizations, enabling deeper analysis of customer churn trends.
