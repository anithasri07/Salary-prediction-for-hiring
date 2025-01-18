# Hiring Prediction Project

This project focuses on predicting salaries based on attributes like experience and test scores using multivariate regression.

## Files in this Repository

1. **hiring.csv**
   - A dataset containing 8 rows and 4 columns.
   - Columns: experience, test_score(out of 10), interview_score(out of 10), salary($).
   - Example rows:
     ```
     [{'experience': null, 'test_score(out of 10)': 8.0, 'interview_score(out of 10)': 9, 'salary($)': 50000},
      {'experience': null, 'test_score(out of 10)': 8.0, 'interview_score(out of 10)': 6, 'salary($)': 45000},
      {'experience': 'five', 'test_score(out of 10)': 6.0, 'interview_score(out of 10)': 7, 'salary($)': 60000}]
     ```

2. **Multivariate Regression Hiring.ipynb**
   - A Jupyter Notebook demonstrating the use of multivariate regression for hiring predictions.
   - Contains 18 code cells spanning 21 lines of code.

## Getting Started

1. Load the 'hiring.csv' dataset for exploratory data analysis.
2. Open the 'Multivariate Regression Hiring.ipynb' notebook to see data preprocessing and model building.

## Requirements

- Python 3.7+
- Libraries: pandas, numpy, sklearn, matplotlib, jupyter

## How to Use

1. Install the required libraries using `pip install -r requirements.txt`.
2. Run the notebook in JupyterLab or Jupyter Notebook.
