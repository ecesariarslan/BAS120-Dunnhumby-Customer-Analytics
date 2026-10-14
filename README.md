# Customer Analytics & High-Value Customer Prediction

## 📊 Project Overview

This project was completed as part of BAS-120: Introduction to Analytics.

The goal of the project was to analyze historical Dunnhumby customer transaction data and build a predictive model to identify customers who are likely to become high-value customers in a future period.

The analysis includes data exploration, customer-level feature engineering, predictive modeling, model evaluation, and business recommendations.

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- DuckDB
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab
- GitHub

## 🔍 Project Workflow

1. Explored historical transaction data using DuckDB and Python.
2. Selected an observation period and a future outcome period.
3. Created customer-level behavioral features from transaction data.
4. Defined high-value customers based on future spending.
5. Split the data into training and testing sets.
6. Compared Decision Tree models with different maximum depths.
7. Selected the final model using validation performance.
8. Evaluated the model using test accuracy, a confusion matrix, and a classification report.
9. Interpreted the model and developed business recommendations.

## 🤖 Machine Learning Model

A Decision Tree Classifier was used to predict whether a customer would become a high-value customer.

Several tree depths were evaluated to balance predictive performance and model complexity.

### Final Model Performance

- **Test Accuracy:** 85.5%
- **High-Value Customer Precision:** 0.68
- **High-Value Customer Recall:** 0.79
- **High-Value Customer F1-Score:** 0.73

The final model correctly classified:

- 470 not-high-value customers
- 143 high-value customers

## 🔑 Key Finding

Feature importance analysis showed that **total sales during the observation period was the strongest predictive feature** in the final Decision Tree model.

This suggests that historical customer spending can provide useful information for identifying customers who may become high-value customers in the future.

## 💼 Business Recommendation

The model could be used as a decision-support tool to help retailers identify customers for targeted marketing, loyalty offers, and promotional campaigns.

Because the model is not perfect, its predictions should be combined with additional customer information and business judgment rather than used as the sole basis for marketing decisions.

## 📁 Project File

The complete analysis, code, visualizations, Decision Tree, confusion matrix, and model evaluation are available in:

**BAS120_Dunnhumby_Project_Ece.ipynb**

## 🎓 Course

**BAS-120: Introduction to Analytics**  
Wake Technical Community College
