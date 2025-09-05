# Crime Prediction Using Machine Learning

## Overview
This project applies machine learning models to predict crime patterns based on a public dataset.

## Dataset
- Source: https://www.kaggle.com/datasets/currie32/crimes-in-chicago?select=Chicago_Crimes_2012_to_2017.csv
- Features include location, type of crime, date/time, etc.

## Methods
- Data cleaning & preprocessing
- Exploratory Data Analysis (EDA)
- Models: Logistic Regression, Random Forest, Decision Tree, Neural Network
- Evaluation: Accuracy, Precision, Recall

## Results
- Best model: Random Forest (~88% accuracy)
- Key insight:
  - Strongest balance between false positives and false negatives
  - Generalizes well
  - Consistent accuracy across various crime types, not just the most frequent ones

## Visualization
See `results/` folder for presentation slides and plots.

## How to Run
1. Clone the repo
2. Install dependencies: `pip install -r requirements.txt`
3. Open notebook: `CrimePredictionNotebook.ipynb`
