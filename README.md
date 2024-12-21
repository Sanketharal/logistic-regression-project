# Titanic Survival Prediction

This project predicts the survival chances of passengers on the Titanic using a logistic regression model.

## Overview

The Titanic dataset is one of the most popular datasets for understanding machine learning concepts. This project uses passenger data like age, sex, class, and more to predict whether a passenger survived the Titanic disaster.

## Features

- **Data Preprocessing**: Handled missing values, feature encoding, and scaling.
- **Machine Learning Model**: Implemented Logistic Regression for binary classification.
- **Evaluation Metrics**: Used accuracy, precision, recall, and confusion matrix for performance evaluation.

## Dataset

The dataset includes the following attributes:
- `PassengerId`: Unique identifier for each passenger.
- `Pclass`: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd).
- `Sex`: Gender of the passenger.
- `Age`: Age of the passenger.
- `SibSp`: Number of siblings/spouses aboard.
- `Parch`: Number of parents/children aboard.
- `Fare`: Passenger fare.
- `Embarked`: Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).

## Steps

1. **Data Cleaning**:
   - Removed rows with missing values.
   - Filled missing values for age using median values.
2. **Feature Engineering**:
   - Encoded categorical variables like `Sex` and `Embarked`.
3. **Model Training**:
   - Split data into training and testing sets.
   - Trained a logistic regression model.
4. **Evaluation**:
   - Evaluated the model on the test dataset using accuracy, precision, and recall.
  
## Tools and Libraries

- **Python**: Programming language.
- **Pandas**: Data manipulation.
- **NumPy**: Numerical computations.
- **Scikit-learn**: Model building and evaluation.
- **Matplotlib/Seaborn**: Data visualization.
