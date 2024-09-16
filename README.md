# Titanic Survival Prediction Using Machine Learning

This project aims to predict whether a passenger survived the Titanic disaster by analyzing various features such as age, gender, ticket class, and more, using machine learning techniques.

## Importing Libraries

In this project, I used essential libraries that are crucial for data manipulation, analysis, and visualization:

- **pandas**: A powerful library for data manipulation and analysis, particularly useful for handling tabular data.
- **numpy**: A fundamental library for numerical computations, enabling efficient operations on arrays.
- **seaborn**: A versatile data visualization library based on matplotlib, ideal for creating informative statistical graphics.
- **matplotlib.pyplot**: A widely-used library for generating plots and charts, which is essential for visualizing my data and analysis results.

## Loading Data

The project begins by loading the Titanic dataset from CSV files using pandas. The data is split into training and test data, which include key information about passengers that forms the basis for my analysis and predictions.

## EDA (Exploratory Data Analysis)

To gain a deep understanding of the dataset, I perform comprehensive **Exploratory Data Analysis (EDA)**, including:

- **Visualizing distributions** of important numerical features like age, number of siblings/spouses (SibSp), number of parents/children (Parch), and fare to uncover patterns and identify outliers.
- **Exploring relationships** between different variables to detect correlations that could influence survival predictions.

## Data Cleaning

Data cleaning plays a pivotal role in enhancing the quality of the dataset. Key steps include:

- **Handling missing values** through methods like imputation to address gaps in the data.
- **Dropping irrelevant columns** like "PassengerId," "Cabin," "Name," and "Ticket" that do not contribute significantly to the predictive analysis.
- **Feature engineering**: Creating or transforming features to improve the predictive power of the model.

## Model Testing

The core of the project involves testing various machine learning models to identify the best approach for predicting survival. After evaluation, the **Random Forest Classifier** was selected for its strong performance in classification tasks. The model was fine-tuned to achieve an accuracy of **82.68%** on the test dataset.

Other models considered include Decision Tree, LGBM, XGBoost, ExtraTrees, and Logistic Regression, but Random Forest proved to be the most effective.

## Test Submission

Once the Random Forest Classifier was trained, I applied it to the  dataset and generated predictions. A submission file was created to assess how well the model generalizes to unseen data.
A **titanic-survival-prediction-results.csv** file was created to represent whether each passenger survived or not, which is crucial for evaluation purposes.

## Conclusion

With a final accuracy of **82.68%**, the Random Forest Classifier successfully predicts Titanic passenger survival. This project demonstrates the application of machine learning techniques to historical data, providing valuable insights into the factors that influenced survival during the Titanic disaster.

---

