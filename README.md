# Heart Disease Prediction Using Machine Learning

## Overview
This project aims to predict whether a person has heart disease based on various medical attributes using machine learning techniques. The prediction is based on a dataset that includes several features like age, sex, chest pain type, blood pressure, and more. The project utilizes decision trees and random forest classifiers to make predictions, and the model is trained and evaluated using the `heart.csv` dataset.

### Objective
The goal of this project is to:
- Build a machine learning model to predict heart disease.
- Utilize classification algorithms (Decision Tree, Random Forest) to determine the likelihood of heart disease.
- Evaluate model performance and compare different classifiers.

## Features
The dataset includes the following features:
- **Age**: The age of the person.
- **Sex**: Gender of the person (1 = Male, 0 = Female).
- **ChestPainType**: Type of chest pain experienced.
- **RestingECG**: Resting electrocardiographic results.
- **ExerciseAngina**: Whether or not the person experiences exercise-induced angina.
- **ST_Slope**: Slope of the peak exercise ST segment.
- **Blood Pressure, Cholesterol**: Key indicators related to heart health.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Model Building](#model-building)
- [Evaluation](#evaluation)
- [Contributing](#contributing)

## Installation
### Prerequisites
Ensure you have Python installed. You can download it from [here](https://www.python.org/downloads/).

### Required Libraries
To run this project, install the following libraries:
```bash
pip install numpy pandas scikit-learn xgboost matplotlib



## Usage
Running the Jupyter Notebook
To run the Jupyter notebook that contains the machine learning code:

Install Jupyter if you don't have it already:

bash
Copy code
pip install notebook
Start the notebook server:

bash
Copy code
jupyter notebook
Open the Heart_Disease_Prediction.ipynb file and run the cells.

Model Prediction
The trained models (Decision Tree and Random Forest) can be used to predict the likelihood of heart disease for new input data. You can provide input values in the notebook and see the results.

## Model Building
Data Preprocessing
The dataset was cleaned by handling missing values, encoding categorical variables using one-hot encoding, and scaling numerical features where necessary.

Classifiers Used
Decision Tree Classifier:
A basic decision tree model was trained and evaluated with hyperparameter tuning for parameters like max_depth and min_samples_split.

Random Forest Classifier:
An ensemble method was used with a random forest classifier, tuned for n_estimators, max_depth, and min_samples_split.

XGBoost Classifier (Optional):
XGBoost can also be used to further enhance the performance. It is known for handling imbalanced datasets and improving model performance.

## Evaluation
The models were evaluated using the accuracy metric, and hyperparameter tuning was performed to improve their performance on the validation set.

Accuracy and confusion matrix were used to assess the effectiveness of the models.
Models were compared based on their ability to predict the presence or absence of heart disease.
Contributing
We welcome contributions to improve this project! If you'd like to contribute, please:

Fork the repository.
Create a new branch for your feature or bug fix.
Make your changes.
Submit a pull request with a description of the changes.
