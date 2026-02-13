# customer-churn-prediction
Customer Churn Prediction  Python, ML  | Performed exploratory data analysis  | Engineered features to improve predictive accuracy | Implemented Logistic Regression and Random Forest models

📌 Project Overview

This project builds an end-to-end machine learning pipeline to predict customer churn using the Telco Customer Churn dataset. The objective is to identify high-risk customers and provide actionable insights for improving retention strategies.

⸻

📊 Dataset
	•	Source: IBM Telco Customer Churn Dataset
	•	~7,000 customers
	•	Target variable: Churn
	•	Features: Demographics, services, billing, contract details

⸻

🔎 Exploratory Data Analysis (Key Insights)

🔹 Overall Churn Rate
	•	26.54% of customers churned.

🔹 Contract Type Impact
	•	Month-to-month: 42.71% churn
	•	One year: 11.27%
	•	Two year: 2.83%

Month-to-month contracts are the strongest churn driver.

🔹 Tenure Effect
	•	Retained customers: 37.57 months average tenure
	•	Churned customers: 17.98 months average tenure

Churn risk is highest in early customer lifecycle.

🔹 Payment Method Impact
	•	Electronic check: 45.29% churn
	•	Automatic payments: ~16% churn

Encouraging automatic payments may reduce churn.

⸻

🛠 Technologies Used
	•	Python
	•	Pandas
	•	NumPy
	•	Matplotlib / Seaborn
	•	Scikit-learn
![Contract vs Churn](reports/figures/contract_vs_churn.png)