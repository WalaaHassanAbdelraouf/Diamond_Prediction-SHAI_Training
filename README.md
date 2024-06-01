# Diamond_Prices_Prediction

This project aims to predict the prices of diamonds based on various attributes using machine learning techniques.

## Table of Contents

1. [Project Overview](#project-overview)
2. [Dataset](#dataset)
3. [Model Description](#model-description)
4. [Evaluation](#evaluation)
5. [Fine-Tuning](#fine-tuning)
6. [Conclusion](#conclusion)



## Project Overview

The goal of this project is to develop a predictive model that can estimate the price of a diamond based on its characteristics such as carat, cut, color, clarity, and other relevant features. By leveraging machine learning algorithms, we aim to provide accurate price predictions to assist buyers and sellers in the diamond market.

## Dataset

The dataset used for this project is the [Diamonds dataset](https://www.kaggle.com/shivam2503/diamonds) from Kaggle. It includes the following features:

- `carat`: The weight of the diamond.
- `cut`: The quality of the cut (Fair, Good, Very Good, Premium, Ideal).
- `color`: The color of the diamond (ranging from D (best) to J (worst)).
- `clarity`: The clarity of the diamond (ranging from IF (best) to I1 (worst)).
- `depth`: The depth percentage of the diamond.
- `table`: The width of the diamond's top relative to its widest point.
- `price`: The price of the diamond.
- `x`: Length in mm.
- `y`: Width in mm.
- `z`: Depth in mm.

## Model Description

The model is built using several machine learning algorithms, including:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- KNeighbors Regressor
- Gradient Boosting Regressor

The final model selection is based on performance metrics such as Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).

## Evaluation

Model evaluation is performed using cross-validation and a test dataset. The results are analyzed using various metrics, including:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R-squared (R²) score

## Fine-Tuning

To enhance the accuracy of our predictions, we used advanced techniques such as hyperparameter tuning with Randomized Search and feature scaling with MinMax Scaler.
And then, we reevaluated the model using:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R-squared (R²) score

## Conclusion
By integrating Randomized Search for hyperparameter tuning and MinMax Scaler for feature scaling, this project aims to build a robust and accurate diamond price prediction model. These techniques help optimize the model's performance and ensure that the features contribute appropriately to the predictions.
