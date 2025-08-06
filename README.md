Credit Card Default Prediction

Project Overview

This project focuses on predicting whether a customer will default on their credit card payment using real-world data from Taiwan. The objective is not only to classify customers as likely to default or not, but to provide a probability-based insight which is valuable for risk management and financial decision-making.

Dataset Summary

The dataset includes one target variable:

default.payment.next.month: 1 (default), 0 (no default)
And 23 features such as:

Credit limit, Gender, Education, Marital status, Age
Past payment history for six months (April to September 2005)
Monthly bill statements and previous payments
These features help build a comprehensive profile of customer behavior and payment trends.

Models Used

Several machine learning models were tested and compared:

Logistic Regression
Decision Tree Classifier
Random Forest Classifier
Gradient Boosting
XGBoost (with hyperparameter tuning)
Results and Observations

Initial models like Random Forest showed strong performance in terms of F1 score and AUC, but also signs of overfitting due to a large gap between train and test scores.

After applying cross-validation and tuning the parameters, XGBoost performed best:

Test Accuracy: 87.10%
AUC Score: 0.874
This improved both model generalization and robustness.

Repository Contents

Pavneet_Thind_Credit_Card_Default_Prediction.ipynb: Google Colab notebook that includes exploratory data analysis, feature engineering, model training, and evaluation.
credit-card-default-prediction.pdf: Presentation summarizing the problem, approach, results, and key takeaways.
How to Run

Clone the repository:
git clone https://github.com/Pavneet54/credit-card-default-prediction.git
cd credit-card-default-prediction
Open the notebook in Google Colab or Jupyter Notebook.
Run the notebook step-by-step to reproduce the results.

About the Author
Pavneet Thind
Machine Learning & Data Science Enthusiast