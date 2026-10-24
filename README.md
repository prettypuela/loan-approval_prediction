# Loan Approval Prediction Using Supervised Machine Learning

## Project Overview

This project uses supervised machine learning to predict whether a loan application is likely to be approved or rejected based on applicant information.

A Logistic Regression model is trained to learn patterns from historical loan application data and make predictions on unseen data.

## Project Objectives

- Explore and understand loan application data.
- Identify and handle missing values.
- Prepare categorical and numerical features for machine learning.
- Train a Logistic Regression classification model.
- Evaluate model performance using accuracy, a confusion matrix, precision, recall, and F1-score.
- Identify the features that influence the model's predictions.

## Dataset

The dataset contains **614 loan applications** and **13 columns**, including:

- Gender
- Marital status
- Number of dependents
- Education
- Self-employment status
- Applicant income
- Co-applicant income
- Loan amount
- Loan term
- Credit history
- Property area
- Loan status

The target variable is `Loan_Status`:

- `Y` — Loan approved
- `N` — Loan not approved

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab
- GitHub

## Methodology

1. Import the required Python libraries.
2. Load and inspect the dataset.
3. Explore data types, missing values, and duplicate records.
4. Prepare the data for machine learning.
5. Separate the input features from the target variable.
6. Split the data into training and testing sets.
7. Build a preprocessing pipeline for categorical and numerical features.
8. Train a Logistic Regression model.
9. Evaluate the model using classification metrics and a confusion matrix.
10. Examine model coefficients to understand feature influence.

## Model Performance

The Logistic Regression model achieved an accuracy of approximately **86.18%** on the test dataset.

The classification report and confusion matrix provide additional information about correct predictions and errors for approved and rejected applications.

## Key Learning Outcomes

Through this project, I practised data cleaning, exploratory data analysis, feature preprocessing, supervised machine learning, model evaluation, and interpreting model coefficients.

## Project Files

- `loan_approval_prediction.ipynb` — Jupyter notebook containing the analysis and model.
- `loan_data.csv` — Dataset used for the project.
- `README.md` — Project documentation.

## Limitations

This project is an educational machine learning exercise. Its predictions should not be used as the sole basis for real-world lending decisions. Model performance does not guarantee fair or reliable decisions for every applicant.

## Author

GitHub: [@prettypuela](https://github.com/prettypuela)
