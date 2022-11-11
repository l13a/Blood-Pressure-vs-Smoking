# Smoking v.s. Blood Pressure

## Correlation analysis of what factors influence combined systolic blood pressure. I placed an emphasis on the effects of smoking on blood pressure.

## Presentation Link
https://youtu.be/s9u3FVuF33E

## Data
Analysis of a subset of the NHANES dataset on what factors influence combined systolic blood pressure

## Assumption checks
checked for multicollinearity, homoscedasticity, normality, linearity, and variance inflation factors; detected and handled leverage points and outliers with residual plots, Cook's distance, DFFITS and DFBETAS

## Methods 

### Variable Selection
Compared models (forward and backward stepwise selection by AIC/BIC, LASSO, and the full model) in variable selection

### Shrinkage Methods
Applied shrinkage methods (Ridge, LASSO, and Elastic Net) to stabilize the variance of estimates

### Cross Validation 
Performed cross-validation with AIC, BIC, and LASSO

## Results: 
age is a significant predictor for blood pressure; 
females have a **higher** increase in average blood pressure with an increase in age than males; 
obese females (BMI >= 25) who smoke have **lower** blood pressure on average than those who don't smoke
