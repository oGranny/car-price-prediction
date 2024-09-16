# Car Price Prediction

This project aims to predict car prices using machine learning techniques. The dataset contains various features of cars, and the goal is to build a model that can accurately predict the price of a car based on these features. The dataset is sourced from the Kaggle competition "Regression of Used Car Prices".

## Dataset

The dataset used in this project contains the following features:
- `brand`: The brand of the car.
- `model`: The model of the car.
- `year`: The year the car was manufactured.
- `mileage`: The mileage of the car.
- `price`: The price of the car (target variable).

## Preprocessing

Several preprocessing steps are performed on the dataset:
1. **Encoding**: The features are encoded using label/one-hot encoding.
2. **Handling Missing Values**: Any missing values in the dataset are handled appropriately.
3. **Feature Scaling**: Numerical features are scaled to ensure they are on a similar scale.

## Modeling

The following machine learning models are used to predict car prices:
- Linear Regression
- Ridge Regression
- Decision Tree
- Random Forest
- Gradient Boosting

## Evaluation

The models are evaluated on kaggle with scores (less is better):
- Linear regression: 75286.11932
- Ridge regression: 75286.11944
- Lasso regression: 75286.12671
- Random forest regression: 79804.29567
- XGBoost regression: 88311.93628

## Usage

To run the notebook and train the models, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/oGranny/car_price_prediction.git
    cd car_price_prediction
    ```

2. Download the dataset from [kaggle](https://www.kaggle.com/competitions/playground-series-s4e9/)

3. Run the Jupyter Notebook:
    ```sh
    jupyter notebook notebook.ipynb
    ```

4. Follow the instructions in the notebook to preprocess the data, train the models, and evaluate their performance.

## Conclusion

This project demonstrates how to build and evaluate machine learning models for predicting car prices. By following the steps outlined in the notebook, you can train your own models and make predictions on new data.