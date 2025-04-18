# NFL Injury Prediction Model

This project uses machine learning techniques to predict whether an NFL player will be ruled out for a game based on injury data spanning from 2009 to 2022. The model supports teams, analysts, and fantasy football players by identifying high-risk injuries using structured features from practice reports and injury logs.

## Files
- `NFL_data_preprocess.ipynb`: Preprocessing pipeline including data cleaning, feature engineering, and train-validation-test splits.
- `NFL_machine_learning.ipynb`: Model training, tuning, and evaluation.
- `injury_train.csv`: Training data.
- `injury_val.csv`: Validation data.
- `injury_test.csv`: Test data.
- `proj3_report.pdf`: Summary report of methodology and model results.

## Project Overview
- **Dataset**: Over 80,000 rows of NFL injury reports from the 2009–2022 seasons.
- **Target**: Binary classification — whether a player is ruled "Out" or remains "Active."
- **Features Used**: Injury type, player position, team, week, year, and practice status.

## Techniques & Tools
- Logistic Regression
- Support Vector Machines (RBF & Polynomial Kernels)
- Decision Trees
- Random Forests
- Neural Network (Multi-Layer Perceptron)
- Scikit-learn, Pandas, NumPy, Matplotlib

## Results
- Logistic Regression and SVM achieved the highest predictive performance.
- Full metrics and evaluation details are provided in the final report (`proj3_report.pdf`).

## Goal
To evaluate how player injury and practice data can predict game-day availability and inform decision-making for coaching staff, front offices, and fantasy football managers.
