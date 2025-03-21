# Student Dropout Prediction Pipeline

This repository contains a machine learning pipeline for predicting student dropouts. The main notebook, `dropout_pipeline.ipynb`, guides you through the entire process — from data preprocessing to model evaluation and prediction.


## Repository Structure

- `dropout_pipeline.ipynb`: The main Jupyter notebook that contains the complete pipeline for predicting student dropouts.
- `data/`: Directory containing the dataset used for training and evaluation.
  - `history_engcomp_and_ccomp_all_semesters_until_2023_1.csv`: The dataset containing historical student data.
- `models/`: Directory containing the trained machine learning models.
- `predictions/`: Directory containing the prediction results.


## Notebook Overview

### 1. Importing Libraries

The notebook begins by importing the necessary libraries for data manipulation, visualization, and machine learning.

### 2. Data Loading and Preprocessing

- Load the dataset from `data/history_engcomp_and_ccomp_all_semesters_until_2023_1.csv`.
- Perform data cleaning and preprocessing to prepare the dataset for modeling.

### 3. Exploratory Data Analysis (EDA)

- Visualize the distribution of features and the target variable.
- Generate insights to inform the modeling process.

### 4. Model Training, Tuning, and Predictions

- Train multiple machine learning models, including Random Forest, XGBoost, and LightGBM.
- Save the trained models in the `models/` directory.
- Evaluate model performance using the accuracy metric.
- Compare the performance of different models to identify the best-performing one.
- Use the trained models to make predictions on new data.
- Save the predictions to the `predictions/` directory.

## Results

The prediction results are saved in the `predictions/` directory. The notebook includes visualizations and evaluation metrics to document the performance of the models.
