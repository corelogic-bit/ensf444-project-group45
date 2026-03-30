# Flight Delay Prediction – ENSF 444 Group 45

## Overview
Binary classification model to predict whether a flight will arrive 15+ minutes late, based on pre-departure information. Built for SkyWest Airlines.

## Dataset
Flight Delay Dataset 2018–2024 — [Kaggle Link](https://www.kaggle.com/datasets/shubhamsingh42/flight-delay-dataset-2018-2024)  
Download and place in the `data/` folder before running any code.

## Project Structure
- `data/` — dataset files (not tracked by git)
- `notebooks/` — Jupyter notebooks
- `src/` — Python modules

## Setup
1. Clone the repo
2. Install dependencies: `pip install pandas scikit-learn xgboost imbalanced-learn jupyter`
3. Place dataset in `data/`
4. Run the notebook inside `notebooks/`

## Models
- Logistic Regression (baseline)
- Random Forest
- XGBoost

## Team
- Adol Awan
- Mamoon Khan
- Noor Haj Yousef
