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
- [License](#license)

## Installation
### Prerequisites
Ensure you have Python installed. You can download it from [here](https://www.python.org/downloads/).

### Required Libraries
To run this project, install the following libraries:
```bash
pip install numpy pandas scikit-learn xgboost matplotlib
