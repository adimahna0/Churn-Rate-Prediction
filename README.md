# Churn Rate Prediction

## Introduction

Customer churn is a critical issue for many businesses, as retaining customers is often more cost-effective than acquiring new ones. This project focuses on predicting customer churn using machine learning models, leveraging various customer-related features to improve prediction accuracy.

By analyzing factors such as:
- Age of the user
- Usage frequency
- Subscription type
- Contract length
- History of payment delays

I aim to build robust models that can help identify customers at risk of leaving. This approach not only helps in understanding the key drivers of churn but also enables businesses to take proactive measures to retain their customers, ultimately improving long-term profitability.

## Machine Learning

Using statistical tests and feature engineering, I derived new features based on the initial ones that showed the highest correlation with accurate customer churn predictions. After adding the new features and removing those with minimal correlation, I tested several machine learning models, including:

- **Logistic Regression**
- **Decision Tree Classifier**
- **Gradient Boosting Classifier**
- **Gaussian Naive Bayes**
- **XGBoost Classifier**

The best-performing model was the **Gradient Boosting Classifier** with the following metrics:
- **Accuracy**: 98.6%
- **Precision**: 99.87%
- **Recall**: 97.6%
- **F1 Score**: 98.7%

## Data Visualization

For data visualization, I conducted feature selection analysis by creating correlation heatmaps and exploring features based on customer churn status. Through univariate analysis, discrete data distribution, multivariate analysis, and correlation analysis, I analyzed features against customer churn to uncover interesting insights.

---

Feel free to explore the code and the detailed analyses in this repository. Contributions and feedback are welcome!
