# Flight Price Prediction

Predicting flight prices has become increasingly important for both passengers and airlines. This project aims to build a model that can accurately predict flight ticket prices using historical data. The model will help passengers make informed decisions about when to book their flights and help airlines make better pricing decisions.

## Data

The data used in this project is obtained from [Kaggle]() and contains information about flight prices, airlines, departure and arrival times, and more. The data has been split into a training set and a test set, and the model will be trained on the training set and tested on the test set.

## Preprocessing

The data has been preprocessed to clean and transform it into a format that can be used to build the model. The steps involved in preprocessing the data are:

1. Importing the necessary libraries
2. Loading the training and test datasets into pandas dataframes
3. Combining the training and test datasets into a single dataframe
4. Cleaning and transforming the data to remove missing values, remove irrelevant columns, and convert string values into numerical values
5. Encoding categorical variables into numerical values

## Model Building

The model has been built using the Random Forest Regressor from the scikit-learn library. The model has been trained on the preprocessed data and evaluated using mean squared error and R-squared. The results have shown that the model is able to predict flight prices with a high degree of accuracy.

## Conclusion

This project has successfully built a model that can accurately predict flight prices. The model can be used by passengers to make informed decisions about when to book their flights, and by airlines to make better pricing decisions. The code for this project is open-source and can be used and modified as needed.
