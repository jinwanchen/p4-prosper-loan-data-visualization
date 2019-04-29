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

## Part 1: Exploratory Data Analysis
### Data Wrangling
* The structure of the raw dataset was described after a preliminary review of this data.
* Based on the purpose of analyzing the loan data, identifying the correlation of variables associated with each loan with a borrower's APR, 16 features, which were considered to be most relevant to this investigation, were selected.
* A sub-dataset containing only these _main_ features was created from the raw dataset.

## Part 2: Explanatory Data Analysis

## Author
Jong Min (Jay) Lee [jmlee5629@gmail.com]

## Acknowledgement
* This project was completed as a mandatory requirement for the _Data Visualization_ unit from the __Data Analyst Nanodegree__ program at [Udacity](https://www.udacity.com/).
* Raw dataset and definitions for its variables were provided by [Udacity](https://www.udacity.com/).
