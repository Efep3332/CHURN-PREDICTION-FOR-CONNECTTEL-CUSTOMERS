# CHURN-PREDICTION-FOR-CONNECTTEL-CUSTOMERS
The aim of this project is to predict churn customers for Connecttel company.
Customer Data Overview:
Churn Distribution: The number of customers who churned (1869) is considerably lower than those who didn't (5174), indicating an imbalanced dataset.

Gender: There are slightly more male customers (3555) compared to female customers (3488).

Citizenship: Most customers are Junior Citizens (5901), with a smaller number being Senior Citizens (1142).

Partners and Dependents: The majority of customers don't have partners (3641) or dependents (4933).

Internet Service: Fiber optic is the most used internet service (3096), followed by DSL (2421), and some customers (1526) don't use internet services.

Payment Method: Electronic check is the most common payment method (2365), followed by Mailed check (1612), Bank transfer (automatic) (1544), and Credit card (automatic) (1522).

Correlation Matrix:
SeniorCitizen vs. Tenure: Weak positive correlation (0.016567).

SeniorCitizen vs. MonthlyCharges: Moderate positive correlation (0.220173).

Tenure vs. MonthlyCharges: Moderate positive correlation (0.247900).

Machine Learning Model Results:
XGB Classifier:
Accuracy: 78.99% Precision: 62.15% Recall: 52.82% F1-Score: 57.10% AUC-ROC: 83.25%

Random Forest:
Accuracy: 80.48% Precision: 68.56% Recall: 48.53% F1-Score: 56.83% AUC-ROC: 83.81%

SGD Classifier:
Accuracy: 80.91% Precision: 63.27% Recall: 66.49% F1-Score: 64.84% AUC-ROC: 85.48%

SVC:
Accuracy: 80.06% Precision: 70.18% Recall: 42.90% F1-Score: 53.24% AUC-ROC: 82.41%

Naive Bayes:
Accuracy: 28.03% Precision: 25.88% Recall: 92.23% F1-Score: 40.42% AUC-ROC: 48.57%

Decision Tree:
Accuracy: 77.50% Precision: 59.33% Recall: 47.72% F1-Score: 52.90% AUC-ROC: 68.04%

Logistic Regression:
Accuracy: 82.19% Precision: 69.06% Recall: 59.25% F1-Score: 63.78% AUC-ROC: 85.86%

![image](https://github.com/Efep3332/CHURN-PREDICTION-FOR-CONNECTTEL-CUSTOMERS/assets/141910310/17add1f8-9bbc-4bea-bfba-3c87d25e7c2a)

