## Student Pass/Fail Prediction Using Random Forest
This project uses machine learning to predict whether a student will pass or fail based on their math, reading, and writing scores. We apply a Random Forest Classifier, a powerful ensemble model, to accurately classify student outcomes.

## Problem Statement
Given three exam scores for each student, the goal is to predict if the student will pass (1) or fail (0).

## Dataset
Sourced from Kaggle

Features:

math score

reading score

writing score

Target:

pass/fail (engineered column based on average score threshold)

## Tools & Libraries
Python 

pandas

scikit-learn

seaborn + matplotlib (for visualization)

## Steps Performed
Data Cleaning

Encoded categorical variables (e.g., gender, race)

Created a pass/fail column based on average score

Feature Selection

Selected math score, reading score, and writing score as predictors

Model Training

Used RandomForestClassifier from sklearn.ensemble

Evaluation Metrics

Accuracy Score

Confusion Matrix

Classification Report

User Input Prediction

Ability to input student scores and get real-time predictions

## Result
Achieved high accuracy in predicting student outcomes. Random Forest effectively handles variability in marks and shows strong generalization.

## Future Improvements
Add feature importance visualization

Handle edge cases (e.g., invalid marks)

Deploy as a simple web app using Streamlit

## Author
Built with ❤️ by Arjun — engineering student, data wrangler, and machine learning explorer.
