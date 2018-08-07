# Train Test Split and Cross Validation
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

### Performing K-Folds Cross Validation
- Taking the idea of a single train/test split and expanding it to multiple tests across different train/test splits of your data, performing various K-Folds Cross Validation (changing cv argument to alter amount)
  - 3 Fold Cross-Validation
  - 5 Fold Cross-Validation
