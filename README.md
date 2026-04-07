# Flight Delay Prediction – ENSF 444 Group 45

**Course:** ENSF 444 – Machine Learning Systems  
**Semester:** Winter 2026  
**Instructor:** Dr. Ioannou

## Overview

Binary classification model to predict whether a SkyWest Airlines flight will arrive 15+ minutes late, based on pre-departure information. Three models are compared: Logistic Regression (baseline), Random Forest, and XGBoost.

## Dataset

Flight Delay Dataset 2018–2024 — [Kaggle Link](https://www.kaggle.com/datasets/shubhamsingh42/flight-delay-dataset-2018-2024)  
Source: U.S. Bureau of Transportation Statistics (BTS)

A filtered subset (SkyWest, carrier code OO) is included in the `data/` folder.

## Project Structure

```
├── data/                  # Dataset files
├── EDA/                   # Exploratory data analysis
│   ├── eda.ipynb
│   └── plots/             # Saved EDA visualizations
├── notebooks/             # Jupyter notebook(s) with full ML pipeline
├── results/               # Model output plots and figures
├── requirements.txt       # Python dependencies
└── README.md
```

## Setup and Reproducing Results

1. Clone the repo:
   ```
   git clone https://github.com/corelogic-bit/ensf444-project-group45.git
   ```
2. Install dependencies (Python 3.10+):
   ```
   pip install -r requirements.txt
   ```
3. Run the notebook top to bottom:
   ```
   jupyter notebook notebooks/flight_delay_prediction.ipynb
   ```

## Models

| Model | Type |
|---|---|
| Logistic Regression | Linear (baseline) |
| Random Forest | Non-linear (ensemble) |
| XGBoost | Non-linear (boosting) |

## Team (Group 45)

- Adol Awan
- Noor Haj Yousef
- Mamoon Khan