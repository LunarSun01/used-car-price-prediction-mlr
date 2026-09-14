#   
  
# Used Car Price Prediction Using Multiple Linear Regression and OLS  
  
## Project Overview  
  
This project focuses on predicting the selling price of used cars using machine learning.  
  
The main model used is **Multiple Linear Regression (MLR)**, with **Ordinary Least Squares (OLS)** used to estimate the regression coefficients and analyze the relationship between the independent variables and car selling price.  
  
The project uses a used-car dataset containing information such as car name, year, selling price, present price, kilometers driven, fuel type, seller type, transmission, and owner.  
  
## Objectives  
  
The main objectives of this project are to:  
  
- Explore and understand the used-car dataset.  
- Clean and preprocess the data.  
- Select relevant features for prediction.  
- Build a Multiple Linear Regression model.  
- Apply Ordinary Least Squares (OLS) for regression analysis.  
- Evaluate the performance of the model.  
- Identify how different factors influence used-car prices.  
  
## Technologies Used  
  
- Python  
- Jupyter Notebook  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Statsmodels  
  
## Machine Learning Approach  
  
### Multiple Linear Regression  
  
Multiple Linear Regression is used to predict the selling price of a car based on multiple independent variables.  
  
The general form is:  
  
Y = β₀ + β₁X₁ + β₂X₂ + ... + βₙXₙ + ε  
  
Where:  
  
- **Y** = predicted selling price  
- **β₀** = intercept  
- **β₁ ... βₙ** = regression coefficients  
- **X₁ ... Xₙ** = independent variables  
- **ε** = error term  
  
### Ordinary Least Squares (OLS)  
  
Ordinary Least Squares is used to estimate the coefficients of the regression model.  
  
OLS works by finding the coefficient values that minimize the sum of the squared differences between the actual and predicted values.  
  
OLS was also used to examine statistical information such as:  
  
- R-squared  
- Adjusted R-squared  
- Coefficients  
- P-values  
- Statistical significance  
  
## Model Evaluation  
  
The model was evaluated using the following metrics:  
  
- **R² (R-squared)** – measures how much of the variation in selling price is explained by the model.  
- **Adjusted R²** – adjusts R² based on the number of predictors used.  
- **MAE (Mean Absolute Error)** – measures the average absolute prediction error.  
- **RMSE (Root Mean Squared Error)** – measures the square root of the average squared prediction error.  
- **MAPE (Mean Absolute Percentage Error)** – measures prediction error as a percentage.  
  
## Dataset  
  
The dataset contains information about used cars and their selling prices.  
  
The dataset is stored in the `data` folder.  
  
```text  
data/  
**└──** CAR DETAILS FROM CAR DEKHO.csv  
  
Used_Car_Price_Prediction/  
│  
**├──** README.md  
│  
**├──** data/  
│   **└──** CAR DETAILS FROM CAR DEKHO.csv  
│  
**└──** notebook/  
    **└──** used_car_price_prediction.ipynb  
  
## **How to Run the Project**  
1. Clone or download this repository.  
2. Open the project folder in Visual Studio Code or Jupyter Notebook.  
3. Open the notebook inside the notebook folder.  
4. Make sure the dataset is located inside the data folder.  
5. Run the notebook from the beginning.  
The notebook uses a relative dataset path so that the project can be reproduced on another computer.  
## **Conclusion**  
This project demonstrates how Multiple Linear Regression can be applied to used-car price prediction.  
OLS provides additional statistical analysis that helps explain the relationship between the selected features and the selling price, while the evaluation metrics are used to assess the predictive performance of the model.  
  
### Step 2 — Save it  
  
Press:  
  
**Ctrl + S**  
  
Then your project should look like:  
  
```text  
Used_Car_Price_Prediction/  
│  
**├──** README.md          ← ✅  
**├──** data/  
│   **└──** CAR DETAILS FROM CAR DEKHO.csv  
│  
**└──** notebook/  
    **└──** used_car_price_prediction.ipynb  
