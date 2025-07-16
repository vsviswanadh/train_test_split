# train_test_split
# Car Price Prediction Model

## Overview
This project implements a linear regression model to predict the selling price of cars based on their mileage and age. The model is trained and evaluated using a dataset containing car details.

## Dataset
- **Source**: `carprices.csv`
- **Features**: 
  - Mileage
  - Age (in years)
- **Target**: Sell Price (in $)

## Setup
1. Install required libraries:
   - pandas
   - matplotlib
   - scikit-learn

## Code Structure
### Data Loading and Exploration
- The dataset is loaded using pandas.
- A preview of the first 3 rows is displayed to understand the data structure.

### Data Preprocessing
- Features (`Mileage`, `Age(yrs)`) and target (`Sell Price($)`) are extracted.
- The dataset is split into training and testing sets (70% train, 30% test) with a random state of 10 for reproducibility.

### Model Training
- A linear regression model is initialized and trained on the training data.

### Prediction and Evaluation
- The model predicts the sell price for the test set.
- The model's accuracy is evaluated using the R^2 score.

## Results
- **Predicted Prices**: Array of predicted sell prices for the test set.
- **Actual Prices**: Array of actual sell prices from the test set.
- **R^2 Score**: 0.921242248377633, indicating a good fit of the model to the data.

## Usage
1. Run the provided Python script to load the data, train the model, and evaluate the predictions.
2. The output includes predicted prices and the R^2 score for model performance.

## Dependencies
- pandas
- matplotlib
- scikit-learn

## Notes
- Ensure the `carprices.csv` file is in the working directory.
- The model can be further optimized by tuning hyperparameters or using more features.
