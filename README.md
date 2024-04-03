# Used Car Price Prediction using Random Forest and Genetic Algorithm

This project aims to predict the prices of used cars utilizing machine learning techniques, specifically Random Forest (RF) for modeling and a Genetic Algorithm (GA) for hyperparameter tuning. The Genetic Algorithm Library used for hyperparameter tuning is PyGAD.

## Introduction

Predicting the price of used cars is a common problem in the automotive industry and can be addressed using machine learning algorithms. Random Forest is a robust and versatile algorithm known for its effectiveness in regression tasks, making it suitable for predicting car prices.

## Methodology

1. **Data Collection**: The first step involves gathering relevant data on used cars, including features like mileage, model year, brand, etc.
2. **Data Preprocessing**: This phase includes data cleaning, handling missing values, encoding categorical variables, and feature scaling to prepare the data for modeling.
3. **Model Building**: Random Forest, a powerful ensemble learning algorithm, is employed for building the predictive model. It constructs multiple decision trees during training and outputs the average prediction of individual trees.
4. **Hyperparameter Tuning**: Genetic Algorithm (GA) is used to optimize the hyperparameters of the Random Forest model. PyGAD library is utilized for implementing the Genetic Algorithm to search for the optimal set of hyperparameters.
5. **Model Evaluation**: The trained model is evaluated using appropriate evaluation metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), or R2-Squared to assess its performance.

## Dependencies

Ensure you have the following dependencies installed:

- Python (>=3.10.0)
- scikit-learn
- pandas
- numpy
- PyGAD

Install the dependencies using pip:

```
Copy code
pip install scikit-learn pandas numpy pygad
```

## Usage

1. **Data Preparation**: Prepare dataset containing features and target variable (car prices).
2. **Code Execution**: Run the Python script provided in the repository. This script should include the following steps:
   - Data preprocessing
   - Splitting the dataset into training and testing sets
   - Building the Random Forest model
   - Hyperparameter tuning using Genetic Algorithm
   - Model evaluation

## Acknowledgements

- PyGAD Library: https://pygad.readthedocs.io/
- Dataset Source: https://www.kaggle.com/datasets/adityadesai13/used-car-dataset-ford-and-mercedes
