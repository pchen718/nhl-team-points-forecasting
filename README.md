# Forecasting NHL Team Points Using Statistical Learning

## Overview
This project applies statistical learning methods to forecast NHL team point totals
using team-level performance, possession, and special teams metrics.

## Methods
- Feature selection via correlation analysis
- Train-test split with cross-validation
- Random Forest, Gradient Boosting, and Bagging models
- Model evaluation using RMSE and R²

## Results
- Random Forest achieved R² ≈ 0.86 on held-out data
- Ensemble methods consistently outperformed linear baselines
- PDO, shot metrics, and special teams efficiency were key predictors

## Data
Team-level NHL season data aggregated across multiple seasons.
(Data not included due to licensing.)

## Paper
A full write-up of the methodology and results is available here:  
📄 **[Project Paper (PDF)](NHLDataPaper.pdf)**

## Code
This repository includes the R code used to implement and evaluate the statistical
learning models described in the paper.

## Tools
R, caret, randomForest, gbm, ggplot2
