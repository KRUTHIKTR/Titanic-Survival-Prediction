# Titanic Survival Prediction Using Machine Learning

Predict whether a passenger survived the Titanic disaster using machine learning models on classic Titanic dataset. This project involves data cleaning, feature engineering, exploratory data analysis (EDA), and multiple classification algorithms to achieve a high accuracy in survival prediction.

## Table of Contents

- [Overview](#overview)  
- [Features](#features)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Project Structure](#project-structure)  
- [Contributing](#contributing)  
- [License](#license)  

## Overview

This repository focuses on predicting the survival of Titanic passengers using machine learning techniques. The approach includes thorough exploratory data analysis, data preprocessing to handle missing data and feature engineering, and evaluating several classification models like Random Forest, Decision Tree, XGBoost, Extra Trees, and Logistic Regression. The final model, Random Forest, achieved an accuracy of approximately **82.68%**.

## Features

- In-depth exploratory data analysis (EDA) to understand data patterns  
- Data cleaning and missing value imputation  
- Feature selection and engineering to improve model performance  
- Model training and evaluation using different classifiers  
- Prediction generation for unseen test data  

## Installation

1. **Clone the repository:**

    ```
    git clone https://github.com/KRUTHIKTR/Titanic-Survival-Prediction.git
    cd Titanic-Survival-Prediction
    ```

2. **Create a Python virtual environment (optional but recommended):**

    ```
    python -m venv venv
    source venv/bin/activate         # On Windows use: venv\Scripts\activate
    ```

3. **Install the required dependencies:**

    ```
    pip install -r requirements.txt
    ```
    
## Usage

- Open the main Jupyter Notebook (`Titan-EDA-and-Modeling.ipynb`) to explore data analysis, modeling, and prediction steps.
- Ensure the data files `train.csv` and `test.csv` are placed in the `data/` directory.
- Run all notebook cells to train models and generate predictions.
- The final survival predictions will be saved as `titanic-survival-prediction-results.csv`.
