# Song Popularity Prediction

## Overview
This project aims to predict the popularity of songs based on their various attributes. Using machine learning techniques, we developed a predictive model to forecast the popularity of songs, enabling better understanding and analysis of music trends.

## Tech Stack and Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Dataset
The dataset used in this project contains a comprehensive list of songs along with their attributes such as duration, acousticness, danceability, energy, instrumentalness, liveness, tempo, and audio valence.

## Methodology
1. **Data Analysis and Preprocessing**: Conducted exploratory data analysis (EDA) and data preprocessing to handle missing values and ensure data quality.
2. **Feature Selection**: Implemented feature selection techniques to identify relevant predictors for building the predictive model.
3. **Model Building**: Utilized a RandomForestRegressor model and performed hyperparameter tuning using RandomizedSearchCV to optimize model performance.
4. **Evaluation**: Evaluated the model using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE) to assess predictive accuracy.
