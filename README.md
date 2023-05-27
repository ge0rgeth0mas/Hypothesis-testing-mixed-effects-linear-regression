# Walmart Sales Dataset - Hypothesis Testing Project

This repository contains a hypothesis testing project conducted on the Walmart Sales Dataset obtained from Kaggle. The project explores the relationship between weekly sales and various factors such as temperature, holidays, fuel price, CPI, and unemployment.

## Dataset Overview

The dataset includes information about the weekly sales of 45 Walmart stores for the years 2010-2012. It provides details about the stores, dates, weekly sales, holiday flags, average temperature, fuel price, CPI, and unemployment.

## Project Objectives

The main objective of this project is to investigate whether there is a correlation between the average temperature and weekly sales in Walmart stores. The hypothesis tested is that average temperature influences the weekly sales performance. The project follows a mixed-effects modeling approach to account for the random effects of different stores.

## Project Steps

The project follows the following steps:

1. Data Preprocessing: Loading and preprocessing the dataset, checking for missing values, and ensuring data consistency.
2. Data Exploration: Analyzing the distribution and summary statistics of variables, visualizing relationships between temperature and weekly sales, and examining other factors.
3. Hypothesis Testing: Formulating research and null hypotheses, fitting a mixed-effects model using the statsmodels library in Python to test the hypothesis.
4. Model Assessment: Evaluating the goodness of fit, examining model diagnostics, and checking the assumptions of the model.
5. Interpretation and Reporting: Interpreting the results of the hypothesis testing, assessing statistical significance, and drawing conclusions about the correlation between average temperature and weekly sales.

## Repository Contents

- `hypothesis-testing-mixed-effects-walmart-sales.ipynb`: Jupyter Notebook containing the complete project code and analysis.
- `README.md`: This file, providing an overview of the project and repository.
- `walmart-sales-dataset-of-45stores.csv`: The dataset file used for the analysis.
- `requirements.txt`: The list of dependencies.

## Usage

To reproduce the analysis or explore the project further, follow these steps:

1. Clone this repository: `git clone https://github.com/ge0rgeth0mas/Hypothesis-testing-mixed-effects-linear-regression.git`
2. Install the required dependencies: `pip install -r requirements.txt`
3. Open the Jupyter Notebook: `jupyter notebook hypothesis-testing-mixed-effects-walmart-sales.ipynb`
4. Run the notebook cells to execute the code and generate the results.

Feel free to modify and adapt the code or use it as a reference for your own projects.

## Acknowledgements

- Walmart Sales Dataset: [Kaggle](https://www.kaggle.com/datasets/varsharam/walmart-sales-dataset-of-45stores)

## Conclusion

The project's findings support the hypothesis that there is a correlation between weekly sales and average temperature in Walmart stores. Other factors such as CPI, holiday flags, week number, and month number were also found to significantly impact weekly sales. However, fuel price was not a significant predictor.

Please refer to the Jupyter Notebook for a detailed analysis and interpretation of the results.

For any questions or further information, feel free to reach out.
