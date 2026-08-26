# Hot Chocolate Sales Prediction Using Linear Regression

## 📌 Project Overview

This project uses machine learning to predict hot chocolate sales based on weather conditions and weekend information.

The project includes data cleaning, exploratory data analysis, visualization, and a Linear Regression model for predicting hot chocolate sales.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## 📊 Dataset Features

The dataset contains the following features:

* `temperature_C`
* `humidity_pct`
* `wind_speed_kmh`
* `is_weekend`
* `hotchoc_sales`

## 🔍 Project Workflow

1. Loaded the dataset using Pandas
2. Converted dataset values to numeric format
3. Checked and handled missing values
4. Checked and removed duplicate records
5. Performed correlation analysis
6. Visualized the relationship between temperature and hot chocolate sales
7. Selected weather and weekend-related features
8. Split the data into training and testing sets
9. Trained a Linear Regression model
10. Generated predictions
11. Evaluated the model using MAE, MSE, RMSE, and R² score

## 🤖 Machine Learning Model

**Algorithm:** Linear Regression

**Input Features:**

* Temperature
* Humidity
* Wind Speed
* Weekend indicator

**Target:**

* Hot Chocolate Sales

## 📈 Model Evaluation

The model was evaluated using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

## 📁 Files

* `Project_1.py` — Python source code
* `README.md` — Project documentation
* `06_temperature_vs_hotchocolate_sales.csv` — Dataset

## 🎯 Objective

The objective of this project is to understand how weather conditions and weekends can be used as input features for predicting hot chocolate sales using a basic machine learning regression model.
