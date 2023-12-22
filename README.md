# Bulldozer-price-prediction-model

The purpose of this model is to predict the sale price of bulldozers, assessing how well we can predict the sale price of a bulldozer given its characteristics and previous examples of how much similar bulldozers have been sold for.

The data is in a CSV file downloaded from Kaggle's Bluebook for Builders competition and passed as input data.

'RandomForestRegressor' machine learning model is used.

The model is evaluated using the 'show_scores' function.

Hyperparameter tuning is done with RandomizedSearchCV.

Finally, the dataframe compatible with Kaggle submission requirements is generated as a result.
