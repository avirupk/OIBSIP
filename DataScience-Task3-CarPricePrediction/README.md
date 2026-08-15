# Car Price Prediction 🚗

## OASIS INFOBYTE Data Science Internship

### Task 3 — Car Price Prediction with Machine Learning

## 📌 Project Overview

This project focuses on predicting the selling price of used cars using Machine Learning techniques.

The dataset contains information about cars such as car name, manufacturing year, present price, kilometers driven, fuel type, seller type, transmission, and number of previous owners.

## 🎯 Objective

The main objective of this project is to build Machine Learning regression models that can predict the selling price of a used car based on its available features.

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 📊 Dataset

The dataset used in this project is:

`car_prediction_data.csv`

The dataset contains 301 records and 9 columns.

### Features

- Car_Name
- Year
- Selling_Price
- Present_Price
- Kms_Driven
- Fuel_Type
- Seller_Type
- Transmission
- Owner

## 🔎 Data Analysis and Preprocessing

The following steps were performed:

1. Imported the required libraries
2. Loaded the dataset
3. Inspected the dataset structure
4. Checked dataset shape and information
5. Performed statistical analysis
6. Checked for missing values
7. Checked for duplicate records
8. Removed duplicate rows
9. Standardized categorical values
10. Performed exploratory data analysis
11. Encoded categorical features
12. Split the dataset into training and testing sets

## 🤖 Machine Learning Models

Two regression models were used:

- Linear Regression
- Random Forest Regressor

## 📈 Model Evaluation

The models were evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

## 📁 Project Files

```text
DataScience-Task3-CarPricePrediction/
│
├── Car_Price_Prediction.ipynb
├── car_prediction_data.csv
└── README.md
