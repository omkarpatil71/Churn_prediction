📌 Customer Churn Prediction
📖 Project Overview

This project predicts whether a telecom customer will churn (leave the service) using Machine Learning. The dataset contains customer demographics, services subscribed, contract details, and billing information.

The goal is to identify customers likely to churn so businesses can take preventive actions.

🎯 Problem Statement

Customer churn is a major issue in subscription-based businesses. Predicting churn helps companies:

Improve customer retention

Reduce revenue loss

Optimize marketing efforts

🛠️ Technologies Used

Python

Pandas

NumPy

Matplotlib & Seaborn

Scikit-learn

📊 Data Preprocessing Steps

Handled missing values

Converted categorical variables using get_dummies()

Cleaned TotalCharges column (removed blank string values)

Converted object columns to numeric

Feature scaling (if applied)

🤖 Machine Learning Models Used

Logistic Regression

(Add more if you used them like Random Forest / SVM)

📈 Model Evaluation

The model was evaluated using:

Confusion Matrix

F1 Score

Accuracy Score

F1-score was used as a primary metric due to class imbalance.

📌 Key Features Used

Contract Type

Payment Method

Tenure

Monthly Charges

Total Charges

Internet Service

Multiple Lines

📊 Visualizations Included

Correlation Heatmap

Churn Distribution

Confusion Matrix Visualization

Feature Importance (if used)

🚀 Future Improvements

Hyperparameter tuning

Cross-validation

Try advanced models (XGBoost, LightGBM)

Deploy using Flask / Streamlit

👨‍💻 Author

Omkar Patil
