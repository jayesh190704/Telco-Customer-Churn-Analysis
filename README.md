# Telco Customer Churn Analysis

## Project objective:
The objective of this project is to analyze customer churn patterns for a telecom 
company and identify the key drivers behind customer retention and churn. The project 
leverages Power BI to build an interactive dashboard that provides actionable insights to business stakeholders.

## Dataset used
- <a href ="https://github.com/jayesh190704/Telco-Customer-Churn-Analysis/blob/main/Telco_Customer_Churn.csv"> Dataset</a>

## 📌 Key KPIs
•	Total Customers
•	Churn Rate %
•	Active vs. Churned Customers
•	Revenue Impact due to Churn
•	Average Tenure of Churned Customers
•	Service Usage vs. Churn Correlation

## Dashboard Interaction
- Dashboard Interaction <a href="https://github.com/jayesh190704/Telco-Customer-Churn-Analysis/blob/main/Telco_Customer%20Analysis.pbix"> view Dashboard </a>

## 🛠 Project Process
	Data Import – Loaded the dataset into Power BI.
	Data Cleaning & Transformation –
  o	Handled missing values in Total Charges.
  o	Converted categorical variables into usable formats.
  o	Standardized churn column into binary labels.
	Data Modeling –
  o	Created relationships among fact and dimension tables.
  o	Defined DAX measures for KPIs (Churn Rate, Avg Tenure, Revenue Loss).
	Visualization Design –
  o	Used slicers for segmentation (gender, contract type, internet service).
  o	Built KPI cards, charts, and tables for churn analysis.

## Dashboard  
<img width="1856" height="779" alt="Dmart Analysis dashboard" src ="https://github.com/jayesh190704/Telco-Customer-Churn-Analysis/blob/main/Dashboard%20Snapshot.png" />

#🔑 Key Insights & Features
•	Customers with month-to-month contracts have the highest churn rate.
•	Electronic check payment method users churn significantly more than others.
•	Churn is higher among customers with fiber optic internet service.
•	Longer tenure customers are less likely to churn.
•	Customers using multiple services show higher retention.

# Why This Project Stands Out
•	Complete end-to-end Power BI workflow: data cleaning, modeling, visualization.
•	Interactive & user-friendly dashboard with slicers and drill-down features.
•	Focused on business insights rather than just visual representation.
•	Real-world relevance to telecom and subscription-based businesses.
 
✅ Conclusion

	The analysis highlights that churn is influenced by contract type, payment method, and services used. Retention strategies should focus on:
o Offering discounts for long-term contracts.
o	Reducing issues with fiber optic service quality.
o	Encouraging auto-payment methods to reduce churn in electronic check users.


🚀 Future Scope

o Add predictive modeling (ML integration) for churn prediction.
o Incorporate customer feedback/sentiment analysis.
o Build a real-time churn monitoring system using Power BI + streaming datasets.
o Create a what-if analysis dashboard to test retention strategies.
