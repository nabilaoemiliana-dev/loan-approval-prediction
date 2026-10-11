# Loan Approval Prediction Using Machine Learning

## Project Overview
This project uses machine learning to predict loan application approval status based on applicant demographic and financial information. The project explores data preprocessing, exploratory data analysis, model training, and evaluation.

## Objectives
- Explore applicant data and identify patterns associated with loan approval.
- Build and compare Logistic Regression and Decision Tree classification models.
- Evaluate model performance using classification metrics and cross-validation.
- Develop an interactive form to generate predictions for new applicant data.

## Tools & Technologies
- Python
- Pandas
- Scikit-learn
- Matplotlib and Seaborn
- Google Colab

## Models
- Logistic Regression
- Decision Tree Classifier

## Results
The Decision Tree model achieved the following results on the test dataset:

- **Accuracy:** 96.84%
- **ROC-AUC:** 0.9884
- **5-Fold Cross-Validation Accuracy:** 96.34% (mean)

The model's feature importance analysis identified CIBIL score as the most influential feature in its predictions.

## Interactive Prediction
An interactive form was developed to accept applicant information and display the model's predicted loan approval status.

## Limitations
This project predicts historical loan approval status, not whether a borrower will default on a loan. The results reflect patterns in the dataset and should not be interpreted as a real-world lending decision or a guarantee of loan repayment.

## Disclaimer
This project is for educational and portfolio purposes only.
