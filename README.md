# Machine-Learning
Project on Cyber Attack Severity prediction,Hypothesis Test,Sample Project on basic ML project 

🚀 Project Overview
This project aims to predict the severity of cyber attacks based on input features such as attack type, source, vulnerability exploited, and network characteristics, using machine learning models. By predicting severity levels accurately, it assists organizations in prioritizing incident response and risk management effectively.

🎯 Objectives
Build a machine learning pipeline to predict cyber attack severity.
Handle class imbalance using SMOTE to improve model performance.
Evaluate models using accuracy, precision, recall, F1-score, and ROC-AUC.
Deploy the model for practical use in security operations for prioritizing threats.

🛠️ Tech Stack
Python (Pandas, NumPy, Scikit-learn, Imbalanced-learn)
Google collab for experimentation
Matplotlib/Seaborn for visualization

📂 Dataset
The dataset includes features such as:
Attack type
Source IP reputation
Destination criticality
Exploited vulnerability
Network traffic volume
Past incident severity
The target variable is Severity Level (Low, Medium, High, Critical).

🧩 Approach
Data Cleaning: Handled missing values and removed irrelevant columns.
Exploratory Data Analysis: Visualized feature relationships with severity.
Feature Engineering: Encoded categorical variables.
Class Imbalance Handling: Used SMOTE to oversample minority classes.
Model Building: Tested Random Forest, XGBoost, and Logistic Regression.
Model Evaluation: Assessed using F1-score and ROC-AUC.
Model Deployment (optional): Can be integrated into a SIEM tool for live scoring.

⚠️ Challenge Faced
A major challenge was class imbalance, where 'Critical' attacks were underrepresented. This was addressed using SMOTE, which significantly improved recall and F1-score for minority classes.

📊 Results
Accuracy: ~99% on test data
Improved minority class recall using SMOTE

🌟 Key Learnings
Importance of handling imbalanced data in cybersecurity contexts.
Feature selection and interpretability in critical infrastructure predictions.
Model evaluation metrics beyond accuracy for imbalanced datasets.

🚀 Future Enhancements
Incorporate deep learning models for improved feature extraction.
Deploy as a REST API for integration into SOC workflows.
Use real-time streaming data for live severity prediction.

If you found this project useful, feel free to ⭐ star this repository and fork it to contribute further







