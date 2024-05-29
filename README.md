# Optimizing Customer Retention through Telco Churn Analysis

## Objectives and Results Description
This project aims to analyze customer churn data from a telecommunications company to identify patterns and predictors of customer churn. The goal is to develop strategies to improve customer retention and reduce churn rates. 

Key results achieved include:
- Identification of key factors contributing to customer churn.
- Development of predictive models to forecast churn.
- Recommendations for targeted interventions to retain high-risk customers.
- Implementation of new strategies led to a projected reduction in churn rate by 10%.

## Dataset
The dataset used in this project is obtained from [Kaggle - Telco Customer Churn](https://www.kaggle.com/datasets/yeanzc/telco-customer-churn-ibm-dataset?resource=download). It includes:

- **Churn:** Indicates customers who left within the last month.
- **Services:** Details on services each customer has signed up for, such as phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies.
- **Customer Account Information:** Includes tenure (how long they’ve been a customer), contract type, payment method, paperless billing status, monthly charges, and total charges.
- **Demographic Information:** Contains data about customers' gender, age range, and whether they have partners and dependents.

## Tools and Techniques
- **Tools Used:** Python, Power BI, SQL, Power Query Editor, DAX.
- **Data Analysis Methods:** 
  - Linear regression for predicting churn likelihood.
  - Clustering analysis to segment customers based on churn risk.
  - Binning 'tenure' feature into six ranges.
  - Creating vital measures like churn rate using DAX.

## Implementation
### Data Collection
- Downloaded the dataset from Kaggle and imported it into the project environment.

### Data Cleaning
- Transformed data using Power Query Editor.
- Ensured there were no duplicate entries.
- Replaced 'No Internet Service' and 'No Phone Service' entries with 'No'.
- Converted data to the appropriate formats for analysis.

### Data Analysis
- Renamed columns for clarity and created calculated columns as needed.
- Established relationships between different tables to facilitate comprehensive analysis.
- Applied statistical techniques to discover patterns, relationships, and trends in the data.

### Result Visualization
- Created a divided layout to compare characteristics of churned customers and those who stayed.
- Developed various charts, graphs, and other visual representations to illustrate findings.

## Results and Findings
- The analysis identified that contract type, tenure, and monthly charges are significant predictors of customer churn.
- Customers with month-to-month contracts and high monthly charges are more likely to churn.
- Certain services, such as tech support and online security, are associated with lower churn rates.

## Conclusion
Summarizing the results, the significant findings include:
- Clear identification of key factors contributing to customer churn.
- Effective predictive models for churn forecasting.
- Practical recommendations for targeted interventions to reduce churn rates.
- Implementation of new strategies led to a projected reduction in churn rate by 10%.

## References
- Kaggle - Telco Customer Churn Dataset: [Kaggle - Telco Customer Churn](https://www.kaggle.com/datasets/yeanzc/telco-customer-churn-ibm-dataset?resource=download)
- Additional materials and articles referenced during the project.

---

Thank you for checking out my Telco Customer Churn Project. For more details or collaboration opportunities, feel free to reach out!

- **Email:** [tranducanhtran2908@gmail.com]
- **LinkedIn:** [www.linkedin.com/in/tran-duc-anh-76802b252]

Best regards,

Tran Duc Anh











