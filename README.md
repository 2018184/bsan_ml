Introduction

This repository contains datasets and Python code for analyzing the relationship between diet metrics and COVID-19 mortality outcomes across 170 countries.


Dataset Description

The datasets are segmented into four files: food quantity, food kcal, fat quantity, and protein quantity percentages, each with data on 23 categories of diet metrics.


Data Preprocessing

Missing values were handled, and descriptive statistics were calculated for each continent.


Regression Analysis

Ten regression models were used to understand the relationship between diet metrics and COVID-19 outcomes, focusing on milk (excluding butter) and alcoholic beverages as independent variables.


Model Evaluation

The best-performing models after hypertuning using grid search were Random Forest Regression, KNeighbors Regression, and AdaBoost Regression.


Recommendation

Based on evaluation metrics, we recommend utilizing the Random Forest Regression model for predicting COVID-19 outcomes based on diet metrics.
