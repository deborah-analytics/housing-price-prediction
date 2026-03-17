# Housing Price Prediction using Machine Learning

## Overview

This project applies machine learning techniques to predict housing prices using a structured residential dataset.

The analysis follows the CRISP-DM methodology, covering data understanding, preparation, modelling, and evaluation to produce accurate and interpretable predictions.

## Objectives

* Predict housing sale prices using multiple machine learning models
* Identify key factors influencing property value
* Compare model performance using evaluation metrics
* Select the most optimal predictive model

## Dataset

The dataset contains 13,932 records and 14 features describing property characteristics, location, and environmental factors.

Key features include:

* Total living area
* Land size
* Structure quality
* Distance to amenities
* Property age
* Environmental factors (e.g., noise exposure)

## Methodology

The project follows the CRISP-DM framework:

1. Business Understanding
2. Data Understanding
3. Data Preparation
4. Modelling
5. Evaluation

## Models Implemented

* Linear Regression
* Support Vector Regression (Linear, RBF, Polynomial)
* Decision Tree
* Random Forest (100, 200, 500 trees)

## Model Evaluation

Models were evaluated using:

* RMSE (Root Mean Squared Error)
* MAE (Mean Absolute Error)
* R-squared (R²)

## Results

* The **Random Forest model (100 trees)** achieved the best performance
* Demonstrated highest predictive accuracy and generalisation ability
* Successfully used to predict housing prices for new data

## Key Insights

* Property size strongly influences price
* Structure quality significantly impacts valuation
* Location-based variables contribute to pricing variation
* Environmental factors show weaker influence

## Tools & Technologies

* R
* RStudio
* tidyverse
* ggplot2
* caret
* randomForest
* e1071

## Outcome

This project demonstrates an end-to-end machine learning workflow, from data preprocessing to model evaluation and prediction, with practical applications in real estate analytics.

## Future Improvements

* Incorporate geospatial modelling
* Use boosting algorithms (e.g., XGBoost)
* Deploy model as a web application
