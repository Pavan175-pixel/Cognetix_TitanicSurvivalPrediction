# Titanic Survival Prediction

## Objective

Build a Machine Learning model to predict whether a passenger survived the Titanic disaster based on passenger information.

## Dataset

The Titanic dataset contains passenger details such as:

* Passenger Class
* Gender
* Age
* Fare
* Embarked Port
* Number of Siblings/Spouses
* Number of Parents/Children

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn

## Data Preprocessing

* Handled missing Age values using median
* Filled missing Embarked values using mode
* Removed Cabin column due to excessive missing values
* Converted categorical features into numeric values

## Exploratory Data Analysis

* Survival Distribution
* Survival by Gender
* Missing Value Analysis

## Machine Learning Algorithm

* Logistic Regression

## Results

* Accuracy: 79.89%
* Confusion Matrix Generated
* Classification Report Generated

## Output

The model predicts passenger survival with approximately 80% accuracy.

## How to Run

1. Install required libraries using requirements.txt
2. Open titanic_survival_prediction.ipynb
3. Run all cells
