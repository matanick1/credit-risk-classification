# README

## Credit Risk Classification

This project focuses on predicting credit risk based on loan applicant data. By applying machine learning algorithms and resampling techniques, the project aims to accurately classify whether a loan would be approved or not based on various financial indicators.

### Files Included:

1. `lending_data.csv` - Contains data on loan applicants, their financial backgrounds, and loan approval status.
2. `credit_risk_classification.ipynb` - A Jupyter notebook detailing the classification analysis, model training, and evaluation.

## File Descriptions:

### 1. `lending_data.csv`:

- Provides data on various loan applicants, including loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, total debt, and loan approval status.

### 2. `credit_risk_classification.ipynb`:

- **Data Splitting**: Instructions to load the dataset, create labels and features sets, and split data into training and testing datasets.
- **Logistic Regression with Original Data**: Steps to fit a logistic regression model using the original training data, make predictions, and evaluate performance.
- **Logistic Regression with Resampled Data**: Instructions to resample the training data to address class imbalance, fit a logistic regression model, make predictions, and evaluate the model's post-resampling performance.

Throughout the notebook, specific questions are posed and answered to provide insights into the analysis.

## How to Use:

1. **Jupyter Notebook**:
   - Open `credit_risk_classification.ipynb` in Jupyter Notebook or Jupyter Lab.
   - Ensure all dependencies, especially required Python packages, are installed.
   - Run the cells in sequence to conduct the classification analysis.

2. **CSV Data**:
   - The `lending_data.csv` file can be imported into any data processing or analysis tool for further exploration or used as a data source for other projects.

## Notes:

- Ensure that the notebook and CSV file are in the same directory for the analysis to work correctly.
- The analysis and results are based on the current structure and content of the `lending_data.csv` file. Adjustments may be needed if the dataset changes in the future.
