# Laptop Price Prediction Using Machine Learning

This project aims to build a **machine learning model** that predicts the price of a laptop based on user-defined configurations. If a user wants to buy a laptop, this model provides a tentative price based on their specified configurations.

## Problem Statement
The goal is to help users get an estimated price for a laptop based on the configurations they input, such as processor type, RAM, storage, and other hardware features. This can assist users in making informed purchasing decisions.

## Project Structure
- `laptop_price_prediction.ipynb`: Jupyter notebook containing code for data preprocessing, model training, and evaluation.
- `data`: Folder containing the dataset (`laptops.csv` or similar).
- `models`: Directory to store trained models for later use.

## Dataset
The dataset includes various features related to laptop specifications, such as:
- **Brand**: The laptop's manufacturer.
- **Model Name**: Specific model of the laptop.
- **Processor**: Type of processor (e.g., Intel i5, AMD Ryzen 7).
- **RAM**: Amount of RAM (e.g., 8GB, 16GB).
- **Storage**: Storage size (e.g., 256GB SSD, 1TB HDD).
- **GPU**: Graphics card details (if available).
- **Screen Size**: Size of the laptop's display.
- **Operating System**: Type of operating system (e.g., Windows, macOS).
- **Price**: The price of the laptop (target variable).

## Steps Involved
1. **Data Preprocessing**:
   - Cleaning and handling missing values.
   - Encoding categorical variables (e.g., Brand, Processor, OS).
   - Feature scaling (for numerical features such as RAM, Storage, and Screen Size).

2. **Model Training**:
   - Multiple machine learning models are trained to predict the price, such as:
     - Linear Regression
     - Decision Tree
     - Random Forest
     - Gradient Boosting

   - Cross-validation and hyperparameter tuning are performed to improve the model's performance.

3. **Evaluation**:
   - Metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-Squared are used to evaluate the model’s accuracy.

## Results
The model achieves an R-squared score of `92%` (replace with actual value) in predicting the price of laptops based on user input configurations. This helps users to estimate laptop prices with reasonable accuracy.


