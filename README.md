# EDA Lending Club Case Study

This repository contains an exploratory data analysis (EDA) of Lending Club data using Jupyter Notebook, Pandas, Matplotlib, and Seaborn.

## Table of Contents
- [Introduction](#introduction)
- [Data](#data)
- [Analysis](#analysis)
- [Conclusion](#conclusion)
- [Requirements](#requirements)
- [Usage](#usage)

## Introduction
This project involves an exploratory data analysis of the Lending Club dataset. The objective is to uncover insights about loan characteristics, borrower profiles, and the factors that contribute to loan defaults.

## Data
The dataset used in this analysis includes information about loans issued by Lending Club, including loan amounts, interest rates, grades, borrower details, and loan status.

## Analysis
The analysis is performed using the following Python libraries:
- **Pandas**: For data manipulation and analysis.
- **Matplotlib**: For basic plotting and visualization.
- **Seaborn**: For advanced data visualization.

### Key Findings:
* **Loan Purpose**:
  * Small business loans have a higher proportion of charge-offs.
  * Wedding loans have the least proportion of charge-offs.
* **Loan Grades**:
  * Loans with **Grade A** have the lowest risk of being charged off.
  * Loans with **Grade F** and **Grade G** have the highest risk of being charged off.
  * The likelihood of a loan being charged off increases progressively from **Grade A** to **Grade G**.
* **Employment Length**:
  * Those who are unemployed or have less than one year of experience are more likely to be charged off.
  * It makes sense, given that they have little or no expertise and no source of income to repay the debt.
  * The rest of the applicants have almost equal chances of being charged off.
* **Geographic Insights**:
  * States NE are most likely to be charged off, but there aren't enough applications to make a determination.
  * New York, California, and Florida have significant charge-off rates on their applications.
* **Bankruptcy History**:
  * Applicants with public record bankruptcies of 1 or 2 have a higher charge-off rate compared to those with no public record bankruptcies.

## Conclusion
The analysis provides insights into the factors affecting loan defaults. It highlights the importance of borrower profiles and loan characteristics in determining the likelihood of charge-offs.

## Requirements
The following Python packages are required to run the analysis:
- pandas
- matplotlib
- seaborn
- numpy

## Usage
To reproduce the analysis:
1. Clone this repository.
2. Install the required packages.
3. Open `case_std.ipynb` in Jupyter Notebook.
4. Run the notebook cells to perform the analysis.

