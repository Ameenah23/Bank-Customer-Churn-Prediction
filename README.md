# Bank-Customer-Churn-Prediction

### Project Overview
This project aims to predict customer churn for a bank using machine learning models. Customer churn refers to the loss of clients or customers. By predicting which customers are likely to churn, the bank can take proactive measures to retain them.

#### Dataset
The dataset includes:

Customer ID, tenure, number of products, credit card status, active member status, churn status, demographic information, credit score groups, log-transformed balance, and estimated salary.

### Exploratory Data Analysis (EDA)
- Initial Inspection: Loaded and inspected the dataset.
- Descriptive Statistics: Calculated central tendency and distribution.
- Data Cleaning: Handled missing values and outliers, encoded categorical variables.
- Correlation Analysis: Identified relationships between features and churn using a heatmap.

### Feature Selection
  - Feature Importance: Used Random Forest to determine top features for model training.

### Model Training and Evaluation
- Models: Trained Random Forest, Logistic Regression, Decision Tree, and SVM.
- Performance Metrics: Evaluated using accuracy, precision, recall, and F1 score.
- Hyperparameter Tuning: Performed Grid Search with Cross-Validation.

### Model Comparison
- Performance Metrics:
    - Random Forest: Accuracy = 85.05%, Precision = 69.11%, Recall = 43.26%, F1 Score = 53.21%
    - Logistic Regression: Accuracy = 82.65%, Precision = 63.37%, Recall = 27.74%, F1 Score = 38.58%
    - Decision Tree: Accuracy = 78.10%, Precision = 44.73%, Recall = 48.60%, F1 Score = 46.59%
    - SVM: Accuracy = 84.50%, Precision = 83.74%, Recall = 26.21%, F1 Score = 39.92%
- ROC AUC Scores:
    - Random Forest: 0.8539
    - XGBoost: 0.8593
- Confusion Matrix: Plotted for Random Forest and XGBoost.

### Feature Importance
Plotted for XGBoost to identify key predictive features.

### Conclusion
- Best Model: XGBoost slightly outperformed Random Forest with a higher ROC AUC score.
- Key Features: Estimated salary, account balance, and number of products.
- Next Steps: Further tuning, feature engineering, and model interpretation for actionable insights.

This report highlights the key steps and findings in developing machine learning models to predict customer churn effectively.
