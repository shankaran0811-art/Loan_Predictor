🏦 Loan Approval Prediction using Machine Learning
📌 Overview

This project aims to predict whether a loan application will be Approved or Rejected based on applicant financial and personal details. The model leverages machine learning techniques to assist in decision-making and risk assessment.

🎯 Problem Statement

Financial institutions receive numerous loan applications daily. Manually evaluating each application is time-consuming and prone to bias.
This project builds a predictive model to automate and support loan approval decisions using historical data.

📂 Dataset

The dataset contains applicant details such as:

Income
Loan Amount
Loan Term
CIBIL Score
Number of Dependents
Asset values (residential, commercial, luxury, bank)
Employment & education status
🧹 Data Preprocessing
Cleaned column names (removed spaces, standardized format)
Handled categorical variables using encoding techniques
Checked and handled missing values
Converted target variable (loan_status) into numerical format
📊 Exploratory Data Analysis (EDA)
Analyzed distribution of loan approval vs rejection
Visualized relationships between features and target variable
Observed strong correlation between CIBIL score and loan approval
🤖 Model Building
Models Used:
Logistic Regression (baseline model)
Random Forest Classifier (final model)
Train-Test Split:
80% training, 20% testing
📈 Model Evaluation
Metric	Logistic Regression	Random Forest
Accuracy	90.5%	97.8%

Additional Evaluation:

Precision, Recall, F1-score
Confusion Matrix
ROC-AUC Score (~0.99)
🧠 Key Insights
CIBIL Score is the most important feature (~81% importance)
Higher income increases approval probability
Higher loan amount relative to income increases risk
Model performs strongly due to clear patterns in dataset
⚠️ Limitations
Model heavily relies on CIBIL score
May not generalize well to extreme or unseen real-world cases
Does not include real banking constraints (e.g., loan-to-income rules)
🚀 Future Improvements
Add feature engineering (e.g., loan-to-income ratio)
Improve model robustness for edge cases
Integrate rule-based decision layer for realistic predictions
Deploy using Streamlit for interactive predictions
🛠️ Tech Stack
Python
Pandas, NumPy
Matplotlib / Seaborn
Scikit-learn
▶️ How to Run
Clone the repository:
git clone https://github.com/yourusername/loan-approval-prediction.git
Install dependencies:
pip install -r requirements.txt
Run the notebook:
jupyter notebook
📌 Results
Achieved 97.8% accuracy using Random Forest
Demonstrated strong classification performance across both classes
Identified key financial factors influencing loan approval decisions
🙌 Conclusion

This project demonstrates the application of machine learning in financial decision-making. It highlights the importance of feature analysis, model evaluation, and understanding real-world limitations beyond accuracy metrics.

🔗 Author

Shankaran T
Aspiring Data Scientist