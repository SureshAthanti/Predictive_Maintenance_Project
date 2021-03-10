# Aircraft Predictive Maintenance

## Goal 

The goal is is to predict the remaining useful component of life. The remaining useful life estimates are in the units if time (cycles/hours/mileage). 
We have used Linear and non - linear models to predict the Time To Failure of a machine.


## Documents to look for:

1. G8_INFO-T780-002_Final_Project.ipynb - This is the Jupyter file that has the entire code to run and the documentation part. 
2. CMAPSSData - Folder containing the data required for the project.
3. Group8_Aircraft Predictive Maintenance presentation

## Dataset:

The dataset is taken from the Prognostics Data Repository of NASA (National Aeronautics and Space Administration).
Source: https://ti.arc.nasa.gov/tech/dash/groups/pcoe/prognostic-data-repository/#turbofan (direct download link: https://ti.arc.nasa.gov/c/6/)


## Installation - Please install below special libraries before you run the G8_INFO-T780-002_Final_Project.ipynb file

-- !pip install yellowbricks </br>
-- !pip install lightgbm </br>
-- !pip install xgboost </br>
-- !pip install catboost </br>

## Process Flow/Project Structure:

Below Steps followed for the algorithm implementation
1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis
4. RUL feature extraction for the regression task.
5. Visualizations of the data
6. Pipelining of the data 
7. Implementation of the regression models
8. Evaluation and Results comparison.

## Models Implemented:

1. Linear Regression
2. Decision tree Regression
3. Polynomial Regression
4. Lasso Regression 
5. RandomForest Regression 
6. LGBM Regression
7. XGBoost Regression
8. CatBoost Regression

## Conclusion

Damage propagation model/Predictive maintenance is very useful in many industries for estimating the maintenance period for in-service equipment. 

Our, solution is for the aircraft run-to-failure period estimation based on the simulated dataset. This analysis can be used in the aircraft or defense industries for better maintenance strategies.

As future work, we can implement the same models for estimating the Remaining Useful Life of certain parts with limited life before it’s failure can be predicted by extending this approach for other parts.

The work can be extended with Neural Network Models to predict RUL based on input sensor measurements with larger datasets. So that optimized maintenance can be planned and downtime for the aircraft can be reduced. 
