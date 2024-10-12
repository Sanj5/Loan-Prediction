# **LOAN APPROVAL PREDICTION**

## **INTRODUCTION**
This project predicts the likelihood of loan approval based on various factors such as applicant characteristics, financial details, and loan history. The dataset provided contains information for both training and testing models, and the goal is to predict the probability of loan approval for each applicant in the test dataset.

## **DATASET**
The project uses the following files:

- train.csv: Contains the training dataset with features and a target variable loan_status (0 or 1).
- test.csv: Contains the test dataset for which loan approval predictions are required.
- sample_submission.csv: A sample submission file showing the format required for submission.

## **FILE STRUCTURE**
- Loan-Prediction
  - loan_prediction.py
  - README.md
  - sample_submission.csv
  - submission_final.csv
  - test.csv
  - train.csv

## **SETUP INSTRUCTIONS**

1. Clone the repository
  - git clone https://github.com/Sanj5/Loan-Prediction.git
  - cd Loan-Prediction

2. Install required dependencies
  - pip install pandas scikit-learn numpy

3. Run the project
  - python loan_prediction.py

4. Output
  - After running the script, you will find the predictions in a file named submission_final.csv. This file will be formatted with the columns id and loan_status.
  