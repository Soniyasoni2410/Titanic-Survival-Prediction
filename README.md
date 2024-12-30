# Titanic-Survival-Prediction

## Project Overview

This project aims to predict the survival of passengers aboard the Titanic using machine learning techniques. The dataset used for this task includes various features such as age, gender, ticket class, fare, and cabin, which are processed and analyzed to build a predictive model.

## Dataset

The dataset contains information about Titanic passengers, including:

Survival: Indicates whether the passenger survived (1) or not (0).

Pclass: Ticket class (1st, 2nd, or 3rd class).

Sex: Gender of the passenger.

Age: Age of the passenger.

SibSp: Number of siblings/spouses aboard.

Parch: Number of parents/children aboard.

Ticket: Ticket number.

Fare: Fare paid for the ticket.

Cabin: Cabin number.

Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).

## Approach

1. Data Preprocessing

   Handling Missing Values: Imputed missing values in features like Age and Embarked.

   Feature Engineering: Extracted useful features from the dataset (e.g., Title extraction from names, family size creation).

   Encoding: Converted categorical variables such as Sex and Embarked into numerical values using one-hot encoding or label encoding.

   Normalization: Scaled continuous features to ensure consistent ranges.

2. Feature Selection

   Analyzed the importance of features using statistical tests and feature importance metrics.

   Retained the most significant features: Pclass, Sex, Age, Fare, SibSp, Parch, and Embarked.

3. Model Building

   Algorithm Used: Random Forest Classifier

   Built and trained a Random Forest model, leveraging its ensemble nature to improve predictive performance.

   Tuned hyperparameters such as the number of estimators, max depth, and minimum samples split to achieve optimal results.

4. Evaluation

   Evaluated the model using metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.

   Achieved a final accuracy of 85% on the test dataset.

## Challenges

Handling missing data in Age and Cabin columns.

Balancing the dataset to avoid bias toward majority classes.

Selecting optimal hyperparameters for the Random Forest model to maximize performance.

## Summary of Performance

Model Used: Random Forest Classifier

Accuracy: 85%

Additional Metrics:

Precision: 83%

Recall: 82%

F1-Score: 83%

ROC-AUC: 88%

## Future Improvements

Enhance feature engineering by exploring additional passenger attributes.

Experiment with other machine learning models for comparison.

Optimize the handling of missing data in Cabin to extract meaningful patterns.
