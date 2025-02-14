# Credit Scoring Analysis

## Overview
This project analyzes a dataset of historical bank loans to build a **credit scoring model**. It explores key factors influencing loan defaults and applies **data preprocessing** techniques to prepare the dataset for modeling.

## Dataset
The dataset (`bankloan_data.csv`) contains various attributes of loan applicants:

- **Customer**: Unique ID of the applicant (not predictive).
- **Age**: Applicant's age in years.
- **Education**: Highest education level attained.
- **Employ**: Years in current job.
- **Address**: Years at current address.
- **Income**: Annual income (in thousands of dollars).
- **Leverage**: Debt-to-income ratio.
- **CredDebt**: Credit card debt.
- **OthDebt**: Other debts (in thousands of dollars).
- **MonthlyLoad**: Percentage of income used to pay debts.
- **Default**: Target variable (1 = default, 0 = non-default).

## Steps Performed

### 1. Data Loading & Exploration
- Imported necessary libraries (`pandas`, `numpy`, `seaborn`, `matplotlib`, `scorecardpy`).
- Loaded the dataset (`bankloan_data.csv`).
- Displayed random samples and summarized the data structure.
- Examined the distribution of the **Default** variable (36% default rate).

### 2. Exploratory Data Analysis (EDA)
- Checked for missing values.
- Computed summary statistics (`describe()`, `info()`).
- Visualized distributions of key variables.

### 3. Data Preprocessing (if applicable)
- Handled missing values.
- Scaled numerical features.
- Encoded categorical variables.
- Split dataset into training/testing sets.

### 4. Model Development (if applicable)
- Applied feature selection techniques.
- Built logistic regression or machine learning models.
- Evaluated model performance using accuracy, AUC, etc.

## Results & Insights
- The dataset contains **36% default cases**, making it important to handle class imbalance.
- Features like **income, leverage, and credit debt** have a strong impact on default risk.
- Further steps may involve hyperparameter tuning and validation strategies.

## Tools & Libraries
- `pandas`, `numpy`, `seaborn`, `matplotlib`
- `scorecardpy` (for credit scoring analysis)
- `scikit-learn` (if modeling was performed)

## Next Steps
- Improve feature engineering.
- Test alternative machine learning models.
- Deploy the final model for real-world predictions.
