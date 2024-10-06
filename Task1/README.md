# Titanic Survival Prediction Project

## Project Overview

This project aims to analyze the Titanic dataset to predict whether a passenger survived the tragic sinking of the Titanic. Using various features such as age, gender, ticket class, fare, and embarkation location, the project utilizes machine learning techniques to build a predictive model.

## Dataset

The dataset used in this project is the Titanic dataset, which contains information about the passengers on the Titanic. Key features include:

- **Passenger Class (Pclass)**: The class of the ticket (1st, 2nd, or 3rd).
- **Sex**: The gender of the passenger.
- **Age**: The age of the passenger.
- **SibSp**: The number of siblings or spouses aboard the Titanic.
- **Parch**: The number of parents or children aboard the Titanic.
- **Fare**: The fare paid by the passenger.
- **Embarked**: The port of embarkation (C = Cherbourg; Q = Queenstown; S = Southampton).

## Key Steps

1. **Data Exploration**: Load the dataset and perform initial exploration to understand the structure and identify missing values.
2. **Data Preprocessing**: Clean the dataset by handling missing values and converting categorical variables into numerical values.
3. **Feature Selection**: Identify relevant features for prediction.
4. **Model Training**: Split the dataset into training and testing sets, and train a Random Forest Classifier on the training set.
5. **Model Evaluation**: Evaluate the model's performance using accuracy as the metric.

## Installation

To run this project, you will need the following Python packages:

- `pandas`
- `scikit-learn`
- `matplotlib`
- `numpy`

You can install these packages using pip:

```bash
pip install pandas scikit-learn matplotlib numpy
```
