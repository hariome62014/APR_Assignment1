# Wine Quality Prediction using Logistic Regression

## Overview
This project implements a logistic regression model to predict wine quality based on physicochemical properties. The dataset used is the Wine Quality dataset from the UCI Machine Learning Repository.

## Dataset
The dataset contains 1,599 red wines with 11 physicochemical properties and a quality rating between 0-10. For this binary classification task, wines with quality ≥ 7 are classified as "good" and those with quality < 7 as "bad".

## Features
1. Fixed acidity
2. Volatile acidity
3. Citric acid
4. Residual sugar
5. Chlorides
6. Free sulfur dioxide
7. Total sulfur dioxide
8. Density
9. pH
10. Sulphates
11. Alcohol

## Target
Binary classification of wine quality:
- 0: Bad wine (quality < 7)
- 1: Good wine (quality ≥ 7)

## Requirements
- Python 3.7+
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Installation
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
