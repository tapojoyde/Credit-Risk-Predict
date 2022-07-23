# Credit Risk Prediction
When a bank receives a loan application, based on the applicant’s profile the bank has to make a decision regarding whether to go ahead with the loan approval or not. Two types of credit risks (CRs) related to applicants are associated with the bank’s decision :
- Good CR, i.e. applicant is likely to repay the loan, so disapproving the loan results in a loss of business to the bank.
- Bad CR, i.e. applicant is not likely to repay the loan, so approving the loan results in a financial loss to the bank.

Therefore, we intend to predict whether the person (debtor), described by the attributes of the dataset, is a good (1) or a bad (0) credit risk using predictive modeling. This repository contains the Python notebooks for this project to predict credit risk for a South German bank by analysig significant features and building an efficient model. The tasks and objectives are divided into two phases for EDA and Modeling as outlined below.

## Phase 1: Exploratory Data Analysis || Notebook: [Phase2_Model.ipynb](https://nbviewer.org/github/tapojoyde/Credit-Risk-Predict/blob/main/Phase2_Model.ipynb)
- Performing data preprocessing including dealing with missing values, possible outliers, unusual values etc.
- Discretizing and encoding of features for classification.
- Handling dataset imbalance and scaling.
- Preparating descriptive features and target feature for use in Scikit-Learn models.
- Exploring and analysing correlations among various parameters.

## Phase 2: Predictive Modeling || Notebook: [Phase1_EDA.ipynb](https://nbviewer.org/github/tapojoyde/Credit-Risk-Predict/blob/main/Phase1_EDA.ipynb)
- Carrying out feature selection using Random Forest Importance (RFI).
- Performing model fitting using 4 different ML classification algorithms.
- Hyperparameter tuning and evaluating models using statistical tests and performance metrics.
- Discussing limitations of our approach and possible solutions.
***
