# Deriving and Communicating Insights with Data Visualization
Exploratory and explanatory data analysis of [Prosper](https://www.prosper.com/) loan data with Python in Jupyter Notebook for demonstrating the significance of data visualization techniques in data analysis. Data visualizations are created with libraries such as matplotlib and seaborn throughout the course of the data analysis process from systematically exploring the dataset to deriving meaningful insights and communicating key findings.

## Software Requirements
* conda 4.6.3 or similar versions
* python 3.7.2 (or python 3)
* Libraries
  - pandas
  - matplotlib
  - seaborn
  - copy

## Datasets
* `data/` Directory
  - This directory contains the raw dataset and its data dictionary.
  - Sources of the files available in this directory are described below instead of uploading these files to the remote repository.
* `prosperLoanData.csv`
  - Prosper loan data was made available by [Udacity](https://www.udacity.com/) for students enrolled in its __Data Analyst Nanodegree__ program.
  - The data was manually downloaded from this [link](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv).
  - The file contains data for 113,937 listings across 81 variables including such main features as `BorrowerAPR`, `CreditScoreRangeLower` and `CreditScoreRangeUpper`.
* `data_dictionary.xlsx`
  - The Excel file lists the names of all variables in the loan data and provides the definition for each variable.
  - The file was manually downloaded from the [Google Spreadsheet](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0).
* `prosperLoanData_clean.csv`: contains the clean version of the raw Prosper loan data.

## Part 0: Data Wrangling
* The structure of the raw dataset was described after a preliminary review of this data.
* Based on the purpose of analyzing the loan data, identifying the correlation of variables associated with each loan with a borrower's APR, 16 features, which were considered to be most relevant to this investigation, were selected.
* A sub-dataset containing only these _main_ features was created from the raw dataset.
* Ten assessments of the sub-dataset which render data cleaning necessary were made and documented.
* Data cleaning was defined, coded, performed, and verified for each of these assessments.
* Clean version of the dataset was stored in a separate `.csv` file.

## Part 1: Exploratory Data Analysis
### 1. Univariate Exploration
Listed below are key statistics observed for each of the main features.
* Among the three terms, 12, 36, and 64 months, 36 months accounted for approximately 75% of all listings.
* Among the 21 categories of loans offered in Prosper, approximately 57% of all listings aimed to consolidate debt.
* Among the 50 states, California ranked the first in the number of listings which accounted for around 13% of all listings.
* Nearly 95% of the borrowers who received loans from Prosper were employed (including full-time employees).
* Distribution of the range of borrowers' credit scores was approximately normal with its center at approximately between 660 and 699.
* Among the quantitative variables, right-skewed distribution was observed for borrowers' employment status duration, total credit lines, total inquiries, debt to income ratio, and monthly income.
* Nearly all listings were for borrowers without any delinquencies in the past seven years from when their credit profile was pulled.
* Almost all borrowers who applied for loans had not spent more than their available credit line.
* Most frequently observed loan amounts were between $4,000 and $5,000, between $15,000 and $16,000 and between $10,000 and $11,000.

## Part 2: Explanatory Data Analysis

## Author
Jong Min (Jay) Lee [jmlee5629@gmail.com]

## Acknowledgement
* This project was completed as a mandatory requirement for the _Data Visualization_ unit from the __Data Analyst Nanodegree__ program at [Udacity](https://www.udacity.com/).
* Raw dataset and definitions for its variables were provided by [Udacity](https://www.udacity.com/).
