#   
  
# Used Car Price Prediction Using Multiple Linear Regression  
  
## Overview  
  
This project focuses on predicting used car prices using Multiple Linear Regression (MLR) with the Ordinary Least Squares (OLS) method.  
  
The project uses a real-world CarDekho used-car dataset and focuses on data preprocessing, feature engineering, regression modelling, statistical analysis and model evaluation.  
  
## Objectives  
  
- Clean and prepare the used-car dataset  
- Perform exploratory analysis  
- Prepare variables for regression  
- Build a Multiple Linear Regression model using OLS  
- Evaluate the model on unseen data  
- Check for multicollinearity using VIF  
- Interpret the factors affecting used-car prices  
  
## Methodology  
  
The main steps included:  
  
1. Data loading and inspection  
2. Data cleaning  
3. Removal of rare categories  
4. Calculation of vehicle age  
5. Mileage preprocessing  
6. Categorical variable encoding  
7. Log transformation of selling price  
8. Train-test splitting  
9. Multiple Linear Regression using OLS  
10. Model evaluation  
11. Multicollinearity analysis using VIF  
12. Residual analysis  
13. Interpretation of results  
  
## Evaluation Metrics  
  
The model was evaluated using:  
  
- R-squared  
- Adjusted R-squared  
- RMSE  
- MAE  
- MAPE  
- Variance Inflation Factor (VIF)  
  
## Key Results  
  
The model achieved an R-squared of approximately 0.703 on the log-price scale.  
  
After converting predictions back to the real price scale, the model achieved an R-squared of approximately 0.595 and an MAE of approximately ₹170,909.  
  
## Tools Used  
  
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Scikit-learn  
- Statsmodels  
- Jupyter Notebook  
  
## Project Files  
  
- `used_car_price_prediction_mlr_ols.ipynb` — Jupyter Notebook containing the analysis and implementation.  
- `Predicting_Used_Car_Prices.pdf` — Research report explaining the project.  
  
## Authors  
  
Arthur Stephen Arhinsah    
Buabeng Daniel    
Awuah Baffour Peter    
Boamah Chief Junior  
  
University of Mines and Technology (UMaT)  
Department of Data Science and Analytics  
