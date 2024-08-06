# PRODIGY_ML_01

This is Linear Regression based House Prices Prediction Model.
This Model predicts the prices of houses based on their square footage and the number of bedrooms and bathrooms.

Files in the Repository
train.csv: Training dataset containing features and target variable (SalePrice).
test.csv: Test dataset containing features.
sample_submission.csv: Sample submission file.
HousePricesPrediction.py: Python script to train the model and make predictions.

Usage
Run the HousePricesPrediction.py script to train the model and make predictions on the test dataset. The script performs the following steps:

Load Training Data: Reads the train.csv file.
Select Features and Target: Uses 'GrLivArea', 'BedroomAbvGr', and 'FullBath' as features and 'SalePrice' as the target variable.
Split Data: Splits the data into training and validation sets.
Train Model: Initializes and trains a linear regression model.
Evaluate Model: Predicts on the validation set and prints the Mean Squared Error and R-squared value.
Predict on Test Data: Reads the test.csv file, predicts the house prices, and saves the predictions in sample_submission.csv.

The script outputs the following:

Mean Squared Error and R-squared value for the validation set.
Predicted house prices for both the validation and test sets.
A sample_submission.csv file containing the predicted house prices for the test set, ready for submission on Kaggle.
Contributing
If you wish to contribute to this project, feel free to fork the repository and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

License
None.

Contact
For any questions or issues, please open an issue in this repository or contact the author at maryamsameen16@gmail.com.

Happy coding!
