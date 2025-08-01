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
- [Dependencies](#Dependencies)  

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

## Project Structure
  ```
    Titanic-Survival-Prediction/
    ├── data/
    │ ├── train.csv
    │ └── test.csv
    ├── Titan-EDA-and-Modeling.ipynb
    ├── requirements.txt
    ├── README.md
    └── titanic-survival-prediction-results.csv
  ```
- `data/` folder contains raw datasets.  
- Notebook contains analysis and modeling code.  
- `requirements.txt` specifies Python dependencies.  
- `README.md` provides project overview and instructions.

## Contributing

Contributions are highly welcome! To contribute:

1. Fork the repository.  
2. Create a new branch for your feature or bugfix:
    ```
    git checkout -b feature/my-feature
    ```
3. Commit your changes:
    ```
    git commit -m "Add new feature"
    ```
4. Push the branch to your fork:
    ```
    git push origin feature/my-feature
    ```
5. Open a Pull Request describing your changes.

Please adhere to existing code style and document your work clearly.


## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

## Dependencies

The project requires the Python packages (mentioned in `requirements.txt`)

## Contact
For any queries, feel free to reach out:

<a href="mailto:kruthiktrgowda24@gmail.com" target="_blank">
  <img src="https://img.shields.io/static/v1?message=Gmail&logo=gmail&label=&color=D14836&logoColor=white&labelColor=&style=for-the-badge" height="26" alt="gmail logo"  />
</a>

<a href="https://github.com/KRUTHIKTR" target="_blank">
<img src=https://img.shields.io/badge/github-%2324292e.svg?&style=for-the-badge&logo=github&logoColor=white alt=github style="margin-bottom: 5px;" />
</a>

<a href="https://linkedin.com/in/kruthiktr" target="_blank">
<img src=https://img.shields.io/badge/linkedin-%231E77B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white alt=linkedin style="margin-bottom: 5px;" />
</a>

<a href="https://linktr.ee/kruthik_tr" target="_blank">
  <img src="https://img.shields.io/static/v1?message=Linktree&logo=linktree&label=&color=1de9b6&logoColor=white&labelColor=&style=for-the-badge" height="26" alt="linktree logo"  />
</a>


###### Thank you for checking out the Titanic Survival Prediction project! Feel free to explore and contribute.


