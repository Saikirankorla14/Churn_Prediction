# Churn_Prediction

Project Overview
This project aims to predict customer churn — identifying which customers are likely to stop using a service such as telecom or subscriptions. Using machine learning models, this project helps companies take proactive actions to retain customers.
Dataset
The Telco Customer Churn dataset includes customer details such as demographic information, account information, services subscribed, and whether the customer has churned. This data is used to train classification models.
Methodology
- Data Preprocessing: Handling missing values, encoding categorical variables, and feature scaling.
- Feature Engineering: Created new features from existing ones (e.g., tenure groups).
- Model Training:
   • Logistic Regression for baseline performance.
   • Random Forest Classifier for improved accuracy.
- Evaluation: Accuracy, Precision, Recall, F1-Score, and ROC-AUC metrics.
Technologies Used
- Python
- Scikit-learn
- Pandas and NumPy
- Matplotlib and Seaborn for visualization
Learning Outcomes
- Learn how to handle and preprocess structured customer data.
- Understand classification algorithms like Logistic Regression and Random Forest.
- Evaluate classification performance using appropriate metrics.
- Gain insights into customer behavior and churn patterns.
How to Run the Project
1. Clone the repository or download the code.
2. Install required Python libraries using `pip install -r requirements.txt`.
3. Load the Telco Customer Churn dataset.
4. Run the Jupyter Notebook or script to preprocess data, train models, and evaluate results.

Distribution of Churn:
<img width="549" height="393" alt="Distribution_of_churn" src="https://github.com/user-attachments/assets/0419b962-36fd-4663-ad86-4b75328bf0a7" />

Churn by Tenure:
<img width="686" height="547" alt="churn_by_Tenure" src="https://github.com/user-attachments/assets/f379d2eb-4217-4bd9-b2de-f1a6440678b8" />

Churn by Monthly Charges:
<img width="695" height="547" alt="churn_by_MonthlyCharges" src="https://github.com/user-attachments/assets/d7345901-a19a-44d5-bd75-b11753212d35" />


