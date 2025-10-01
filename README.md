Customer Churn Prediction & Analysis

This repository contains an end-to-end customer churn project built using Python and Power BI.
It analyzes churn patterns, builds predictive models, and visualizes insights to help businesses understand why customers leave.

🔹 Project Workflow

Data Preprocessing

Handled missing values, categorical encoding, and outlier treatment.

Feature engineering (e.g., tenure groups, contract type buckets).

Exploratory Data Analysis (EDA)

Distribution of churn across tenure, payment method, contract type, and internet service.

Correlation heatmaps & statistical summaries.

Machine Learning Models

Logistic Regression, Random Forest, XGBoost, etc.

Evaluated with Accuracy, Precision, Recall, F1-score, ROC-AUC.

Feature importance extracted for churn drivers.

Visualization (Power BI)

Interactive Customer Churn Dashboard with KPIs, charts, and churn drivers.

Highlights: Contract type, Tenure group, Monthly charges, Payment method, Internet service.

🔹 Key Insights

Month-to-Month contracts → highest churn risk.

Higher monthly charges → more likely to churn.

Electronic Check payment method → strong churn driver.

Tenure < 12 months → significantly higher churn.

🔹 Tech Stack

Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost)

Power BI (Interactive dashboard, DAX calculations)

Jupyter Notebook for analysis

Dataset: Telco Customer Churn (Kaggle)
