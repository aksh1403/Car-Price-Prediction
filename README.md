# 🚗 Car Price Predictor

A beginner-friendly machine learning project that predicts the fair market value of used cars. This project demonstrates a complete end-to-end data science pipeline, from loading raw data to making predictions with a trained model.

## 📋 Overview
This repository contains a Python script/notebook that uses a **Linear Regression** algorithm to find mathematical patterns in past car sales. By looking at features like the car's brand, year, engine size, and mileage, the model learns how to accurately estimate the price of a new car listing.

## 🛠️ Tech Stack
* **Python 3**
* **Pandas:** Used for data manipulation, cleaning, and one-hot encoding (dummy variables).
* **Scikit-Learn:** Used for splitting the data, training the Linear Regression model, and evaluating its accuracy.

## 🚀 What the Code Does
1. **Data Loading:** Imports a raw `.csv` dataset of used car sales.
2. **Data Cleaning:** Removes irrelevant columns (like ID numbers) and converts text-based categories (like 'Automatic' or 'Honda') into numerical values the math model can understand.
3. **Train/Test Split:** Divides the dataset into an 80% training set (to teach the model) and a 20% testing set (to grade the model).
4. **Model Training:** Fits a Linear Regression model to the training data.
5. **Evaluation:** Grades the model's performance using Mean Absolute Error (MAE) to see how many dollars off the predictions are on average.
6. **Prediction:** Takes a sample car, modifies its features (e.g., setting mileage to 150,000), and outputs a predicted real-world price.

## 💻 How to Run
1. Clone this repository to your local machine.
2. Ensure you have the required libraries installed:
   ```bash
   pip install pandas scikit-learn
