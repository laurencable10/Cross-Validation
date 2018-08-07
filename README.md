# Cross Validation
## Using Boston Housing Data 

Building upon validating "generalizeability" of models by testing them on unseen data through two methods via the Scikit-Learn library : 
  - Train/Test Split
  - K-Fold Cross-Validation  

* The dataset utilized median housing prices in Boston, in addition to other attribute information including per capita crime rate, nitric oxides concentration,  weighted distances to five Boston employment centers, full-value property-tax rate per $10,000, index of accessibility to radial highways, etc* 

## Overview 

### Exploratory Data Analysis
- Leveraging a correlation heat map to investigate potential relationships and predictors

### Model Building
- Building MLR Model using RM, AGE, & NOX as Predictor Variables
  - Defining X and y variables 
  - Fitting linear regression model 
  - Making predictions 
  - Scoring model 
  - Plotting actual versus predicted values 

### Performing Train/Test Splits
- Validating model's ability to handle new data by performing various train/test splits (changing test_size argument to alter amount)
  - 50-50 Split
  - 70-30 Split
  - 90-10 Split
- Comparing and explaining performances of  various train/test splits 

We prevent overfitting by not using all the data, and
We retain some remaining data to evaluate our model.
In the case of cross-validation, the model fitting and evaluation is performed multiple times on different train/test splits of the data.

Ultimately we can use the training/test validation framework to compare multiple models on the same dataset. This could be comparisons of two linear models, or of completely different models on the same data.

