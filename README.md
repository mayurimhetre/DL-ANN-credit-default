# Credit Card Default Prediction

## Overview
This project focuses on predicting whether a **credit card holder will default** on their payment in the next month using historical financial and demographic data. The dataset is widely used for binary classification tasks in finance.

## Dataset Description
Dataset Link: https://archive.ics.uci.edu/dataset/350/default+of+credit+card+clients

The dataset contains the following columns:

| Column | Description |
|--------|-------------|
| ID | Customer ID |
| LIMIT_BAL | Credit limit of the card |
| SEX | Gender (1 = male, 2 = female) |
| EDUCATION | Education level (1 = graduate, 2 = university, 3 = high school, 4 = others) |
| MARRIAGE | Marital status (1 = married, 2 = single, 3 = others) |
| AGE | Age of the customer |
| PAY_0 to PAY_6 | Past payment status for the last 6 months |
| BILL_AMT1 to BILL_AMT6 | Bill statement amounts for the last 6 months |
| PAY_AMT1 to PAY_AMT6 | Amounts paid in the last 6 months |
| default payment next month | Target variable (1 = default, 0 = no default) |

## Objective
The main goal of this project is to **build a machine learning model** that predicts whether a customer will default next month, helping banks manage risk and take proactive measures.

### Results
Neural network developed in pytorch gives 82 % accuracy
