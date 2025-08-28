#📌 Predicting the Probability of Personal Loan Acceptance 

🔎 Project Overview

This project applied machine learning classification techniques to predict whether a customer would accept a personal loan. The goal was to help the bank improve customer targeting in marketing campaigns, increase loan uptake, and reduce campaign costs.

By building predictive models, I demonstrated skills in:

Data preprocessing & exploratory data analysis (EDA)

Feature selection & handling multicollinearity

Applying and tuning multiple machine learning models

Evaluating results using classification metrics

📊 Dataset

Size: 5,000 customers

Target Variable: Personal Loan (1 = Accepted, 0 = Not Accepted)

Features (12): Age, Experience, Income, ZIP Code, Family, CCAVG, Education, Mortgage, Securities Account, CD Account, Online Banking, Credit Card

⚙️ Technologies Used

Programming Language: Python

Libraries & Tools:

pandas, NumPy (data manipulation)

Matplotlib, Seaborn (visualization)

scikit-learn (machine learning models & evaluation)

XGBoost, Random Forest, AdaBoost, Decision Tree

🤖 Machine Learning Models

The following models were trained and compared:

Decision Tree

Bagging

Random Forest

AdaBoost

XGBoost (best performing model)

📈 Results

XGBoost achieved the best performance with:

Perfect AUC = 1.0

High precision, recall, and F1-scores for both classes

Key predictors of loan acceptance:

Income (higher income → more likely to accept loan)

Education level (Bachelor’s or higher)

Credit card spending (CCAVG)

✅ Business Recommendations

Based on the results, the bank should:

Target high-income customers for personal loan campaigns.

Focus on customers with Bachelor’s or higher education.

Prioritize customers with high credit card activity.

Deploy the XGBoost model in marketing systems to predict potential loan customers.

🚀 How to Run This Project

1. Clone the repository:

git clone https://github.com/your-username/personal-loan-prediction.git
cd personal-loan-prediction


2. Install dependencies:

pip install -r requirements.txt


3 Open the Jupyter Notebook:

jupyter notebook "predicting the probability of personal loan.ipynb"
