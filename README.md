# Personal Loan Prediction

## Table of contents

*   Libraries
*   Read and Understand Data
*   Data Preprocessing
*   Exploratory Data Analysis
    *   Univariate Analysis
    *   Bivariate Analysis
*   Insights based on EDA
*   Model Building
    *   Logistic Regression
    *   Support Vector Classifier
    *   Decision Tree
*   Recommendation

## Context

A US bank named Thera Bank has a sizable customer base. The majority of these clients are liability clients (depositors), and their deposits range in amount. Asset customers make up a very tiny portion of the bank's customer base, and the bank is interested in swiftly growing this group to attract more loan business and, as a result, increase its interest-earning potential. The management is particularly interested in finding ways to turn its liability customers into personal loan customers while keeping them as deposits.

To identify the potential customers who have a higher probability of purchasing the loan is our main target.

## Motivation

To understand Logistic regression, Support Vector, Decision tree, hyperparamter tuning Decision trees and explore these algorthims using Sklearn

## Dataset Introduction
*  **ID** : Customer ID
*  **Age**: Customer’s age in completed years
*  **Experience**: # years of professional experience
*  **Income**: Annual income of the customer (in thousand dollars)
*  **ZIP Code**: Home Address ZIP code.
*  **Family**: the Family size of the customer
*  **CCAvg**: Average spending on credit cards per month (in thousand dollars)
*  **Education**: Education Level.
   1: Undergrad;
   2: Graduate
   3: Advanced/Professional
*  **Mortgage**: Value of house mortgage if any. (in thousand dollars)
*  **Personal_Loan**: Did this customer accept the personal loan offered in the last campaign?
*  **Securities_Account**: Does the customer have securities account with the bank?
*  **CD_Account**: Does the customer have a certificate of deposit (CD) account with the bank?
*  **Online**: Do customers use internet banking facilities?
*  **CreditCard**: Does the customer use a credit card issued by any other Bank (excluding All life Bank)?

## Objective of the project

*  To predict whether a liability customer will buy a personal loan or not.
*  Which variables are most significant.
*  Which segment of customers should be targeted more.
*  Does Age have any impact of customer buying loan?
*  Do people with less income borrow loans?
