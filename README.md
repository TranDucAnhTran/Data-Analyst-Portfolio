# 📊 Optimizing Customer Retention through Telco Churn Analysis

## 🎯 Objectives and Results Description
This project aims to analyze customer churn data from a telecommunications company to identify patterns and predictors of customer churn. The goal is to develop strategies to improve customer retention and reduce churn rates.

Key results achieved include:
- 📈 Identification of key factors contributing to customer churn.
- 🔮 Development of predictive models to forecast churn.
- 🎯 Recommendations for targeted interventions to retain high-risk customers.
- 📉 Implementation of new strategies led to a projected reduction in churn rate by 10%.

## 📂 Dataset
The dataset used in this project is obtained from [Kaggle - Telco Customer Churn](https://www.kaggle.com/datasets/ylchang/telco-customer-churn-1113). It includes:

- **📊 Churn:** Indicates customers who left within the last month.
- **🔧 Services:** Details on services each customer has signed up for, such as phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies.
- **📂 Customer Account Information:** Includes tenure (how long they’ve been a customer), contract type, payment method, paperless billing status, monthly charges, and total charges.
- **👥 Demographic Information:** Contains data about customers' gender, age range, and whether they have partners and dependents.

## 🛠️ Tools and Techniques
- **🔧 Tools Used:** Power BI, SQL, Power Query Editor, DAX.
- **📊 Data Analysis Methods:** 
  - Logistic regression for predicting churn likelihood based on customer features.
  - Clustering analysis (K-means) to segment customers based on churn risk.
  - Decision tree analysis to identify the most important factors influencing churn.
  - Binning 'tenure' feature into six ranges to simplify analysis and visualization.
  - Creating vital measures like churn rate and average tenure using DAX.

## 🛠️ Implementation
### 🗂️ Data Collection
- Downloaded the dataset from Kaggle and imported it into the project environment using Python's Pandas library for initial data exploration.

### 🧹 Data Cleaning
- Transformed data using Power Query Editor to ensure consistency and accuracy.
- Removed duplicate entries to prevent skewing the analysis.
- Replaced 'No Internet Service' and 'No Phone Service' entries with 'No' to standardize categorical variables.
- Converted data to the appropriate formats (e.g., numerical, categorical) for analysis.

### 📊 Data Analysis
- Renamed columns for clarity and created calculated columns as needed to derive additional insights.
- Established relationships between different tables (e.g., customer demographics, service usage) to facilitate comprehensive analysis.
- Applied statistical techniques, such as correlation analysis, to identify relationships between variables.
- Developed predictive models using logistic regression and decision trees to forecast customer churn.

### 📈 Result Visualization
- Created a divided layout in Power BI to compare characteristics of churned customers and those who stayed.
- Developed various charts, graphs, and other visual representations (e.g., bar charts, pie charts, scatter plots) to illustrate findings.
- Used slicers and filters in Power BI to allow interactive exploration of the data.

## 📈 Results and Findings
The analysis identified that contract type, tenure, and monthly charges are significant predictors of customer churn. Specifically:
- Customers with month-to-month contracts and high monthly charges are more likely to churn.
- Certain services, such as tech support and online security, are associated with lower churn rates.

Additional findings include:
- Gender is not a significant factor for churning.
- Senior citizens have a relatively high churn rate at 41%, which is almost twice as high as non-senior citizens.
- Having dependents (e.g., children) reduces the likelihood of churn. There is only 6% churn among customers that have dependents, about 5 times lower than customers that do not.
- Customers that are single have a 13% higher churn rate than married ones.
- Phone service and multiple lines are not significant factors affecting customer churn rate.
- Customer churn uses a lot of fiber optic services (69.4%), which can be a factor leading to customer churn.
- High customer churn rates are seen among customers who do not use tech support and online security services.
- Most customers who churn use manual payment modes (1,379 customers).
- 57.3% of churned customers use the Electronic Check payment method.
- 88.55% of churned customers opt for month-to-month contracts.
- New customers (i.e., tenure under 12 months) have the highest cases of churn.
- Customers who have churned have slightly higher monthly charges.

## 🏁 Conclusion
Summarizing the results, the significant findings include:
- Clear identification of key factors contributing to customer churn, enabling targeted intervention strategies.
- Effective predictive models for churn forecasting, providing actionable insights for business decisions.
- Practical recommendations for targeted interventions, such as offering discounts to high-risk customers or enhancing customer support services.
- Implementation of new strategies led to a projected reduction in churn rate by 10%, demonstrating the potential impact of data-driven decision-making.

## 📚 References
- Kaggle - Telco Customer Churn Dataset: [Kaggle - Telco Customer Churn](https://www.kaggle.com/datasets/ylchang/telco-customer-churn-1113)
- Additional materials and articles referenced during the project.

---
## Presentation

You can watch my presentation on customer churn analysis using Power BI on YouTube. In this video, I provide a detailed guide on how to use Power BI to analyze data and derive important insights.

**Title:** Power BI | Phân tích Tỷ lệ khách hàng rời bỏ (Học viên Đức Anh)  
**Link:** [YouTube Video](https://www.youtube.com/watch?v=RBPA0lM6Jq8&t=655s)


Thank you for checking out my Telco Customer Churn Project. For more details or collaboration opportunities, feel free to reach out!

- **📧 Email:** [tranducanhtran2908@gmail.com]
- **🔗 LinkedIn:** [www.linkedin.com/in/tran-duc-anh-76802b252]

Best regards,

Tran Duc Anh











