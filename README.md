# Decision-Tree-Bank-Marketing-Subscription-Prediction
Predicts whether a bank customer will subscribe to a term deposit using a Decision Tree Classifier. Includes data preprocessing, model training, evaluation, and interpretable decision rules for actionable business insights.
Overview

Predict whether a bank customer will subscribe to a term deposit using a Decision Tree Classifier. This project demonstrates interpretable machine learning with clear decision rules.

Objective

Predict customer subscription (yes / no)

Control overfitting with max_depth

Extract decision rules for business insights

Dataset

UCI Bank Marketing Dataset

Target: y (Subscription)

Features: Age, Job, Marital Status, Education, Balance, Housing Loan, Contact, Campaign Duration, Previous Outcome

Tools

Python | Pandas | Scikit-learn | Matplotlib

Workflow

Load dataset & handle missing values

Encode categorical features

Split into train/test sets

Train Decision Tree (max_depth=5, Gini)

Visualize tree

Evaluate metrics: accuracy, precision, recall, F1-score

Compare train/test accuracy

Extract decision rules

Model Details

Algorithm: Decision Tree Classifier

Criterion: Gini Impurity

Max Depth: 5

Train/Test Split: 75% / 25%

Random State: 42

Evaluation

Train Accuracy: XX%

Test Accuracy: YY%

Classification metrics show good prediction for non-subscribers and moderate for subscribers

Overfitting controlled by limiting tree depth

Key Decision Rules

Long call duration + successful previous outcome → likely to subscribe

Contact via cellular + ≤2 campaign calls → higher subscription chance

Housing loan = yes + low balance → unlikely to subscribe
