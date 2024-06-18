## Car Price Prediction using Random Forest Regression
The main objective of this project is to build a web application which predicts the current price of a used car based on the features like year (in which it is bought), selling price (at which it is sold), kms_driven (the distance travelled by the car till the date), Fuel_Type (CNG, Diesel or Petrol), Seller_Type (Individual or Dealer), Transmission (Manual or Automatic) and owners (The number of people who have owned the car before). 

This project is very useful in real life because it helps the users to predict the current price of the used car. It is beneficial to both sellers and customers. The customer can know the price and can invest in an effective manner. The seller can set the price which gives much more profit. 

Initially, the dataset which is downloaded from Kaggle is considered. The dataset is cleaned and feature engineering is done in order to identify the important features. In this, mainly the random forest regressor is used for the model fitting and prediction. After fitting various models on the dataset, it has been observed that the Random Forest Regressor has given the best results in terms of model accuracy. Randomized Search CV is also used in order to find the best hyperparameters for model fitting. 

After the successful model development, the web application is deployed using Flask. Thus, the car price prediction system is built.
