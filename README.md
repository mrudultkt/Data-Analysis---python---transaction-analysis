# Data-Analysis---python---transaction-analysis

# Python Data Analysis Assignment

## Overview

This project focuses on analyzing customer, card, and transaction datasets using Python. The objective is to perform data preprocessing, exploratory data analysis (EDA), and derive business insights from customer spending behavior, credit profiles, card portfolios, age groups, and gender-based transaction patterns.

## Objective

The primary goals of this assignment are:

* Clean and preprocess raw datasets.
* Perform data quality checks.
* Analyze customer card profiles.
* Explore transaction patterns and spending behavior.
* Study customer credit health and spending relationships.
* Analyze age-based customer portfolios.
* Analyze gender-based spending behavior.
* Generate business insights and recommendations.

## Datasets Used

### 1. users_data.csv

Contains customer demographic and financial information.

Key fields:

* Customer ID
* Current Age
* Gender
* Income
* Debt
* Credit Score
* Number of Credit Cards

### 2. cards_data.csv

Contains card-related information.

Key fields:

* Card Brand
* Card Type
* Credit Limit
* Card Issue Details
* Chip Availability

### 3. transactions_data.csv

Contains transaction history for all customers.

Key fields:

* Transaction Date
* Transaction Amount
* Merchant Information
* Transaction Method (Swipe/Online)
* Error Information

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Jupyter Notebook

## Project Tasks

### Task A: Data Preprocessing

Performed the following activities:

* Converted currency columns into numeric format.
* Cleaned transaction amount fields.
* Checked and handled duplicate records.
* Identified and treated missing values.
* Standardized transaction methods.
* Cleaned city names.
* Standardized state codes.
* Formatted ZIP codes.

### Task B: Data Analysis

#### Customer Card Profile

* Card brand distribution
* Card type distribution
* Credit limit analysis
* Card brand vs credit limit comparison

#### Transaction Analysis

* Data collection time frame
* Top spending customers
* Highest and lowest transaction amounts
* Transaction analysis by payment method
* Monthly spending trends

#### Customer Spend Profile vs Credit Health

* Total spend analysis
* Average ticket size
* Transaction frequency
* Correlation between spending and financial indicators

#### Age Portfolio Analysis

* Customer distribution by age bands
* Credit limit analysis by age group
* Age vs income analysis
* Age vs credit score analysis
* Online transaction behavior by age group

#### Gender Analysis

* Average transaction amount by gender
* Day-of-week spending patterns
* Time-of-day spending patterns
* Weekend vs weekday transaction behavior

## Key Insights

* Mastercard and Visa dominate the card portfolio.
* Debit cards account for the majority of issued cards.
* Spending is concentrated among a small group of high-value customers.
* Credit limits vary significantly across customer segments.
* Younger customers show stronger digital transaction preferences.
* Female customers contribute a larger share of transaction activity.
* Customer financial characteristics influence spending behavior.

## Business Recommendations

* Develop loyalty programs for high-value customers.
* Promote credit card adoption among debit card users.
* Create age-specific product offerings.
* Strengthen digital engagement strategies for younger customers.
* Implement targeted marketing campaigns using customer segmentation.
* Monitor unusual transactions for fraud and risk management.

## Deliverables

* Jupyter Notebook (.ipynb)
* Data preprocessing and analysis code
* Visualizations and charts
* Insights and recommendations

## How to Run

1. Place the following files in the project directory:

   * users_data.csv
   * cards_data.csv
   * transactions_data.csv

2. Open the Jupyter Notebook.

3. Run all cells sequentially.

4. Review generated visualizations, insights, and conclusions.

## Author

Name: Mrudul Mukundan