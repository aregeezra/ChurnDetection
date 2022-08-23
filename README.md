# ChurnDetection

# Churn

## Customer Churn Data

PowerCo is a major gas and electricity utility that supplies to corporate, SME (Small & Medium Enterprise), and residential customers. The power-liberalization of the energy market in Europe has led to significant customer churn, especially in the SME segment. They have partnered with BCG to help diagnose the source of churning SME customers.

A fair hypothesis is that price changes affect customer churn. Therefore, it is helpful to know which customers are more (or less) likely to churn at their current price, for which a good predictive model could be useful.

Moreover, for those customers that are at risk of churning, a discount might incentivize them to stay with our client. The head of the SME division is considering a 20% discount that is considered large enough to dissuade almost anyone from churning (especially those for whom price is the primary concern).

The Associate Director (AD) held an initial team meeting to discuss various hypotheses, including churn due to price sensitivity. After discussion with your team, you have been asked to go deeper on the hypothesis that the churn is driven by the customers’ price sensitivities. 

Your AD wants an email with your thoughts on how the team should go about testing this hypothesis.

The client plans to use the predictive model on the 1st working day of every month to indicate to which customers the 20% discount should be offered.


![customer churn](https://user-images.githubusercontent.com/110170707/181729174-9d61edf7-b0d3-44ff-8128-ebc019d4def1.png)

I followed in this project the steps of the project management method called CRISP-DM. This method has undergone modifications aimed at the reality of a Data Science project and with that it was called CRISP-DS.

CRISP-DS has the following steps with their respective courts:

## 1 - Business Question

Predict how much energy the power companies in the datasets will consume in the next 12 months.

## 2 - Understanding the Business

This forecast will be used to plan companies in relation to the investments necessary for the expansion and maintenance of their power plants.

## 3 - Data Collection

0.0 - IMPORTS

0.1 - Helper Function

0.2 - Loading Data

## 4 - Data Cleaning

1.0 - DESCRIPTION OF DATA


1.1 - Rename Columns

1.2 - Data Dimensions

1.3 - Data Types

1.4 - Check NA

1.5 - Fillout NA

1.6 - Change Types

1.7 - Descriptive Statistical

- 1.7.1 - Numerical Attributes

- 1.7.2 - Categorical Attributes

2.0 FEATURE ENGINEERING


2.1 - Creation of Hyphoteses

- 2.1.1 - Demographic Hyphoteses
- 2.1.2 - Geographic Hyphoteses
- 2.1.3 - Sociocultural Hyphoteses

2.2 - Final list of Hypotheses

2.3 - Feature Engineering

3.0 - VARIABLE FILTERING


3.1 - Line filtering

3.2 - Column Selection

## 5 - Data Exploration

4.0 - EXPLORATORY DATA ANALYSIS

4.1 - Univariate Analysis

- 4.1.1 - Response Variable

- 4.1.2 - Numerical Variable

- 4.1.3 - Categorical Variable

4.2 - Bivariate Analysis

- 4.2.1 - Summary of Hyphoteses

4.3 - Multivariate Analysis

- 4.3.1 - Numerical Attributes
- 4.3.2 - Categorical Attributes
