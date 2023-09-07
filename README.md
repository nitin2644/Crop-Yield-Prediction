# Crop Yield Prediction Model

## Table of Contents

- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Goal](#goal)
- [Data](#data)
- [Key Activities](#key-activities)
- [Evaluation](#evaluation)
- [Technologies Used](#technologies-used)


## Introduction

Welcome to the Crop Yield Prediction Model project! In agriculture, predicting crop yields is a critical task for decision-making and risk management. This project leverages predictive modeling to accurately estimate crop yields for various crops based on historical data and environmental factors.

## Project Overview

- **Objective**: Develop a machine learning model to predict crop yields based on historical data and environmental factors.
- **Importance**: Accurate crop yield prediction aids in agricultural risk management and decision-making for sustainable farming.
- **Evaluation Metric**: The model's performance is measured using the Coefficient of Determination (R2_score).

## Goal

The primary goal of this project is to build a machine learning model that can accurately predict crop yields by analyzing historical data and considering environmental factors such as weather conditions (rain, temperature), pesticide usage, and other relevant variables. The model's predictions will be evaluated using the R2_score.

## Data

- **Dataset**: The project uses historical data related to crop yield, weather conditions, and agricultural practices.
- **Importance**: Accurate and comprehensive data is crucial for training and testing the prediction model.

## Key Activities

The project involves the following key activities:

- Data Preprocessing: Cleaning and preparing the dataset for analysis.
- Feature Engineering: Selecting relevant features and creating new ones for modeling.
- Machine Learning Modeling: Building predictive models using regression techniques.
- Model Evaluation: Assessing the model's performance using the R2_score metric.

## Evaluation

The evaluation metric for this project is the Coefficient of Determination (R2_score). R-squared measures how well the data fit the regression model and indicates the proportion of variance in the dependent variable that can be explained by the independent variables.

- **Scikit-Learn**: The `sklearn.metrics.r2_score` library is used for calculating the R2_score.

## Technologies Used

The following technologies and libraries are used in this project:

- Python
- Scikit-Learn
- Pandas
- Jupyter Notebook

