#  House Price Prediction

This project uses a machine learning model to predict house prices based on various features in the dataset. It is built using Python and Scikit-learn, and is based on a Kaggle-style competition format.

## Files Included
- `train.csv` — Training data with house features and the target variable `SalePrice`
- `test.csv` — Test data for which predictions need to be made
- `submission.csv` — Final output file with predicted house prices

## Model and Workflow
- **Model Used**: Random Forest Regressor
- **Workflow**:
  1. Load and inspect the training and test datasets
  2. One-hot encode categorical variables
  3. Handle missing values using mean imputation
  4. Train a RandomForestRegressor model
  5. Predict `SalePrice` for the test set
  6. Save predictions in `submission.csv`

