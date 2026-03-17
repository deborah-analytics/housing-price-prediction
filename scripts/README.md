## Scripts and Modelling Pipeline

This folder contains the R scripts and modelling pipeline used to develop and evaluate housing price prediction models.

### Main Script

* **housing_model_pipeline.Rmd**
  This script implements the full machine learning workflow using the CRISP-DM methodology.

### Key Processes Covered

* Data loading and preprocessing
* Handling missing values and feature selection
* Exploratory data analysis (EDA)
* Model training using multiple algorithms:

  * Linear Regression
  * Support Vector Regression (SVR)
  * Decision Tree
  * Random Forest (100, 200, and 500 trees)
* Model evaluation using:

  * RMSE (Root Mean Squared Error)
  * MAE (Mean Absolute Error)
  * R² (Coefficient of Determination)

### Output

The script produces:

* trained models
* performance comparison metrics
* visualisations used for analysis and reporting

### Note

The script is written in R Markdown to combine code, outputs, and explanations in a reproducible format.
