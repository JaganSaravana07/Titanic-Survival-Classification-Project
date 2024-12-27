# Titanic Survival Classification
## Project Description
This project aims to develop a predictive model that determines the likelihood of a passenger's survival on the Titanic based on a set of socio-economic and demographic factors. By analyzing data from the Titanic dataset, the project investigates how various attributes like socio-economic status, age, and gender influenced survival outcomes. This model can serve as a foundational system for understanding how specific passenger characteristics impacted survival probability.

## Objective
The primary objective of this project is to create an accurate classification model that predicts whether a passenger would survive the Titanic disaster. This involves:

- Identifying and understanding key factors that most significantly impacted survival chances.
- Building a machine learning model to predict survival outcomes based on these factors.
- Evaluating the model's effectiveness and refining it to improve predictive accuracy.

## Requirement
- Pandas: For data manipulation and analysis.
- NumPy: For numerical computations.
- Matplotlib: For data visualization.
- Seaborn: For enhanced data visualization.
- Scikit-learn: For data preprocessing and machine learning utilities.

## Conclusion
The Titanic Survival Classification project aimed to predict passenger survival likelihood using various classification algorithms. Models including Logistic Regression, SVC, K-Neighbors, Gaussian Naïve Bayes, Linear SVC, Decision Tree, and Random Forest were evaluated based on cross-validation scores to identify the most effective model for accurate prediction.

Support Vector Machine (SVM) emerged as the most reliable model, demonstrating the highest mean cross-validation score. Following hyperparameter tuning, SVM further improved in prediction accuracy, achieving a training score of 83.54% and a mean cross-validation score of 0.829. This tuning allowed the model to generalize effectively, improving its predictive performance on unseen data.

The final model’s performance highlights its potential in survival prediction tasks, supporting its application in similar classification problems with robust data preprocessing and hyperparameter optimization.
