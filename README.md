# Fraud Detection Project

## Project Resources

- ["Challenge.ipynb" - Identifying Outliers using Standard Deviation and Interquartile Range.](https://github.com/jancichocki/Module_7_Challenge/blob/main/challenge.ipynb)
- ["Visual Data Analysis.ipynb" - Visual Data Analysis of Fraudulent Transactions.](https://github.com/jancichocki/Module_7_Challenge/blob/main/visual_data_analysis.ipynb)

## Overview
Fraudulent transactions represent a significant threat to financial institutions and their customers. Detecting and preventing fraud is crucial for maintaining trust and financial stability. In this project, we explore various methods and techniques for identifying potential fraudulent transactions using statistical analysis, SQL queries, and visualizations.

## Challenge
The primary challenge in fraud detection is to distinguish legitimate transactions from fraudulent ones accurately. Traditional methods often rely on rule-based systems or machine learning algorithms. However, these approaches may not always capture subtle patterns or emerging fraud tactics. In this project, we focus on two common methods for identifying outliers in transaction data: standard deviation and interquartile range.

## Methods

### Identifying Outliers using Standard Deviation
The standard deviation method involves calculating the mean and standard deviation of transaction amounts. Transactions that deviate significantly from the mean by a predefined threshold are flagged as outliers. While this method is straightforward, it may not be robust to extreme outliers or skewed distributions.

### Identifying Outliers using Interquartile Range (IQR)
The interquartile range (IQR) method is based on quartiles, specifically the first (Q1) and third (Q3) quartiles. The IQR is the range between Q1 and Q3, representing the middle 50% of the data. Transactions outside a certain range around the median are considered outliers. This method is more robust to skewed distributions and extreme values.

### Visual Data Analysis of Fraudulent Transactions
Visualizing transaction data can provide valuable insights into consumption patterns, trends, and anomalies. We use hvPlot, a Python library for interactive visualizations, to generate line plots, box plots, and other visualizations. By examining transaction trends over time and comparing different cardholders' behavior, we can identify suspicious patterns that may indicate fraudulent activity.

## Data Analysis Questions
To demonstrate the practical application of our methods, we address specific data analysis questions posed by stakeholders:

### Data Analysis Question 1: Verification of Fraudulent Transactions
Stakeholders suspect that two key customers may have been victims of fraud. We verify if there are any fraudulent transactions in their transaction history. Using SQL queries and visualizations, we analyze transaction trends for these customers and look for unusual patterns that may indicate fraudulent activity.

### Data Analysis Question 2: Identification of Anomalies
The CEO of a major corporate client suspects unauthorized use of their corporate credit card for expensive restaurant bills. We investigate transactions for this cardholder in the first quarter of 2018 and identify any anomalies or outliers that may indicate fraudulent activity.

## Conclusion
Fraud detection is an ongoing challenge that requires a combination of statistical analysis, data querying, and visual exploration. By leveraging techniques such as standard deviation, interquartile range, SQL queries, and visualizations, we can enhance fraud detection capabilities and mitigate financial risks associated with fraudulent transactions.
