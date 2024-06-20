# ML-Project-2

This project aims to predict the selling price of used cars based on various features such as the car's present price, year, kilometers driven, fuel type, seller type, transmission type, and ownership.I have used linear regression and lasso regression to have a comparison between both

## Table of Contents

- Dataset
- Installation
- Exploratory Data Analysis
- Data Preprocessing
- Model Training
- Linear Regression
- Lasso Regression
- Evaluation
- Results
- Conclusion


## Dataset

The dataset consists of 301 entries and 9 columns:

- Car_Name
- Year
- Selling_Price
- Present_Price
- Kms_Driven
- Fuel_Type
- Seller_Type
- Transmission
- Owner


## Data Preprocessing

The following preprocessing steps were applied:

-Encoding categorical features:
-Fuel_Type: Petrol (0), Diesel (1), CNG (2)
-Seller_Type: Dealer (0), Individual (1)
-Transmission: Manual (0), Automatic (1)
-Splitting the data into features (X) and target (Y).
-Splitting the data into training and testing sets.
