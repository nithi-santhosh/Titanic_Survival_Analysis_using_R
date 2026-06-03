# Who Survived the Titanic?  
## An Exploratory Analysis of Survival Patterns During the 1912 Maritime Disaster

This repository contains an end-to-end data analysis project developed using **R** and **R Markdown** on the built-in **Titanic** dataset from R.

## Project Overview

The report investigates the factors that influenced passenger survival during the Titanic disaster through:

- Data Wrangling
- Exploratory Data Analysis (EDA)
- Survival analysis by passenger class, sex, and age
- Chi-Square Hypothesis Testing
- Logistic Regression Analysis
- Machine Learning-based Survival Prediction
- Model Evaluation using Confusion Matrix, Accuracy, Sensitivity, Specificity, and Kappa Statistics

## Dataset

The built-in Titanic dataset in R contains survival information for **2,201 passengers and crew members** aboard the Titanic. It summarizes passenger class, sex, age group, and survival status in an aggregated contingency-table format.

## Key Findings

- Passenger class significantly influenced survival outcomes.
- Female passengers had a much higher survival rate than male passengers.
- Children were more likely to survive than adults.
- Logistic Regression showed that class, sex, and age were strong predictors of survival.
- The machine learning model achieved approximately **76% accuracy** in predicting survival outcomes.

## Files Included

- `Titanic_Survival_Analysis_Report_ML_final.Rmd` – R Markdown source file
- `Titanic_Survival_Analysis_Report_ML_final.pdf` – Final PDF report

## Tools and Packages Used

- R
- R Markdown
- tidyverse
- ggplot2
- knitr
- caret
- broom
- stargazer

## How to Reproduce

1. Open the `.Rmd` file in RStudio.
2. Install the required packages if needed.
3. Knit the file to generate the PDF report.

## Author

**Nithi Santhosh**  
IIM Bangalore
PGPBA 2026-28
