# customer_churn_prediction

This project involves predicting customer churn, a critical business problem where the goal is to identify customers who are likely to leave a service or product subscription. Accurate churn prediction allows companies to take proactive measures to retain valuable customers.

## Overview

The project includes data exploration, preprocessing, feature engineering, and model building to predict customer churn. It uses various machine learning algorithms and techniques to create predictive models and evaluate their performance.

## Dataset

The dataset used in this project contains information about customers, including demographics, subscription details, and churn status.

### Data Exploration

- Initial data exploration is performed to gain insights into the dataset.
- Key statistics, data types, and missing values are examined.
- The distribution of categorical variables like 'Location' and 'Gender' is visualized.

### Feature Engineering

- Several new features are created to enhance the predictive power of the model.
- Age groups, encoding of categorical variables, and usage-related ratios are introduced.
- Principal Component Analysis (PCA) is applied to reduce dimensionality and improve model performance.

## Models

Various machine learning models are trained and evaluated:

1. **Random Forest Classifier**: A decision tree-based ensemble model.
2. **Logistic Regression**: A linear classification model.
3. **XGBoost Classifier**: A gradient boosting model.
4. **Neural Network**: A deep learning model with multiple layers.

## Model Evaluation

The models are evaluated using standard classification metrics:

- **Accuracy Score**: Measures the overall model accuracy.
- **Classification Report**: Provides precision, recall, F1-score, and support for each class.
- **Confusion Matrix**: Displays the true positive, true negative, false positive, and false negative counts.

## Requirements

- Python 3.x
- Libraries: pandas, numpy, seaborn, matplotlib, scikit-learn, xgboost, tensorflow

## Conclusion

This project serves as a practical example of predicting customer churn using machine learning techniques.
