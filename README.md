README for CrudeOilPrediction Repository

CrudeOilPrediction - Georgios Tsoupras

This repository contains the source code for my thesis, which focuses on the prediction and analysis
of crude oil prices using various machine learning techniques such as Random Forest, Gradient
Boosting, and XGBoost.
Project Overview
The project consists of several key steps, including:
1. Data Preprocessing:
- Loading and cleaning the crude oil dataset.
- Converting columns to appropriate data types.
- Handling missing values.
- Creating new features like lagged values and rolling window statistics.
2. Exploratory Data Analysis (EDA):
- Visualization of the distribution of data.
- Correlation analysis between different features.
3. Model Training:
- Training multiple machine learning models (Random Forest, Gradient Boosting, and XGBoost)
to predict crude oil prices.
- Performing Grid Search to optimize the hyperparameters of the models.
4. Evaluation:
- Evaluating model performance using Mean Squared Error (MSE), Root Mean Squared Error
(RMSE), and R2 Score.
- Comparing actual vs predicted prices and trends.
Disclaimer:
If you encounter any issues running the code, a PDF file containing the results and the code used
for the thesis is available for reference. This document provides detailed outputs and insights as part
of the thesis analysis.
Installation and Setup
1. Clone the repository:
git clone https://github.com/georgeTs19/CrudeOilPredictionGeorgiosTsoupras.git
2. Install dependencies:
Ensure you have Python installed. Then, install the required libraries by running:
pip install -r requirements.txt
3. Run the code:
- Download the dataset (if necessary) and place it in the same directory as the code.
- Run the Jupyter notebook or Python script to reproduce the analysis.
Dataset

The dataset contains historical crude oil prices and related financial data with the following features:
- Date
- Price, Open, High, Low prices
- Volume
- Percentage changes in crude oil price, USD rate, and other related financial metrics.
Ensure that the dataset file is in CSV format and named final_dataset.csv before running the scripts.
How to Use
1. Run Data Preprocessing:
Use the script to preprocess the data:
python preprocess_data.py
2. Model Training:
Train the machine learning models:
python train_model.py
3. Evaluation:
Evaluate the model predictions and plot the results:
python evaluate_model.py
Results
The results include:
- Prediction Accuracy: Trend prediction accuracy for crude oil prices.

- Actual vs Predicted Prices: Visual comparison between actual and predicted crude oil prices.
- Model Metrics: Performance metrics for each model, including MSE, RMSE, and R2 Score.
Dependencies
The project relies on the following Python libraries:
- pandas
- matplotlib
- seaborn
- scikit-learn
- xgboost
- numpy
Install all dependencies by running:
pip install -r requirements.txt
License
This project is licensed under the MIT License - see the LICENSE file for more details.
