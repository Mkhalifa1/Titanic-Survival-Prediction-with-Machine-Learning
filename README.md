# Titanic Survival Prediction with Machine Learning

## Understanding the Data
The Titanic dataset contains demographic and travel-related information for passengers aboard the Titanic. The goal is to predict whether a passenger survived the disaster (target variable: `Survived`).

### Key Features:
- **PassengerId**: Unique identifier for each passenger.
- **Pclass**: Passenger's class (1st, 2nd, 3rd).
- **Name**: Passenger's name.
- **Sex**: Passenger's gender (male or female).
- **Age**: Passenger's age.
- **SibSp**: Number of siblings or spouses aboard the Titanic.
- **Parch**: Number of parents or children aboard the Titanic.
- **Ticket**: Ticket number.
- **Fare**: Passenger's fare.
- **Cabin**: Cabin number.
- **Embarked**: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).

### Target Variable:
- **Survived**: 1 if the passenger survived, 0 if not.

## Approach:
1. **Identify Missing Values**:  
   Missing values are present in the `Age`, `Cabin`, and `Embarked` columns. We'll impute the missing data using appropriate strategies:
   - **Numerical Columns**: Use the median (e.g., for `Age
