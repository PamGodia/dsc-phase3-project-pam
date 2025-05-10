# dsc-phase3-project-pam

## 1. Project overview

### Project Goal

To predict whether there is a pattern of customers who will ("soon") stop doing business with SyriaTel, a telecommunications company.

### Objectives

To determine if there is a predictive pattern of customers who will ("soon") stop doing bussiness with SyriaTel.

## 2. Business understanding

The audience are the telecom business staff whose interest is reducing how much money is lost because of customers who don’t want to stay with the company very long.

### Question

Are there any predictable patterns for customers who do not want to stay with the network for long?

### Dataset

We use the Churn in Telecom's dataset

## 2. Data preparation

Data preparation included formating columns to rename them correctly, removing extra spaces, cheking for missing values, defining the features (X) and target (y) varaibles, dealing with categorical variables, and encoding the target variables from boolean to binary.
The feaatures selected are 'account_length', 'area_code', 'total_day_charge', 'total_eve_charge', 'total_night_charge', 'total_intl_charge.

## 3. Modelling

### 3.1. Modelling was first done using the statsmodels

Statsmodel was used to fit the baseline model.
The results was a Pseudo R-Squared of 0.07172 which meant that the model explains only 7.17% of the variability
The coefficients results indicate that total_day_charge, total_eve_charge, total_night_charge, total_intl_charge are significant and influence whether whether one churns or not.A unit increase in international charge increases the chance of churn by 29 percent.

### 3.2. Modelling using scikit-learn

