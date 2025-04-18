# Bulldozer Price Predictor

## Project Overview
This machine learning project aims to predict the sale price of bulldozers using historical data. The model is trained on auction sale data of bulldozers, including various features like model specifications, configurations, and sale dates.

## Dataset
The data comes from the Kaggle Bluebook for Bulldozers competition and includes:
- Train.csv - Training data through 2011
- Valid.csv - Validation data from January-April 2012  
- Test.csv - Test data from May-November 2012

## Model Performance
The final Random Forest Regressor model achieves:
- Training RMSLE (Root Mean Squared Log Error)
- Validation RMSLE
- R² Score on validation data

## Key Features
- Data preprocessing pipeline for handling:
  - Missing values
  - Categorical variables
  - Date features
- Random Forest model with hyperparameter tuning
- Feature importance analysis
- Time series data handling

## Technologies Used
- Python 3.x
- Libraries:
  - pandas
  - numpy 
  - scikit-learn
  - matplotlib

## Usage
1. Install required dependencies:
````python
pip install pandas numpy scikit-learn matplotlib
````
2. Run the Jupyter notebook:
````python
jupyter notebook end-to-end-bulldozer-price-regression.ipynb
````
## Model Features
The most important features for predicting bulldozer prices include:

Year made
Product size
Sale year
Machine hours
Product group

## Future Improvements
- Try other algorithms like XGBoost or LightGBM
- Feature engineering to create more predictive variables
- Deep learning approaches for price prediction
- Deployment as a web service

## License

[MIT](https://choosealicense.com/licenses/mit/)
