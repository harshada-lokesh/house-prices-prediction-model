# House Prices Prediction - Kaggle Competition

This repository contains my solution for the [Kaggle Housing Prices Competition](https://www.kaggle.com/c/house-prices-advanced-regression-techniques).

## 🤖 Model Approach
I implemented a **Random Forest Regressor** to predict house prices. 
- **Preprocessing**
- **Model:** Random Forest Regressor Model
- **Validation:** Used a train-test split to monitor Mean Absolute Error (MAE) and the Root-Mean-Squared-Error (RMSE).

## 📊 Results

### Kaggle Leaderboard Scores
* **Submission 1 (Baseline):** `29,371.88`
    * *Approach:* Basic Random Forest with default parameters and simple imputation.
* **Submission 2 (Optimized):** `16,644.83`
    * *Approach:* Improved feature engineering, handled categorical variables, and tuned `n_estimators`.

## 📂 Project Structure
- `scripts`: The Python scripts used for training and prediction.
- `submissions`: My different predictions for the Kaggle leaderboard.
