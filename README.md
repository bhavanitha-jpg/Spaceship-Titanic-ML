# Spaceship Titanic - Machine Learning Project

## Overview

This project predicts whether passengers aboard the Spaceship Titanic were transported to an alternate dimension. The solution follows a complete machine learning workflow, including data exploration, feature engineering, preprocessing, model training, evaluation, hyperparameter tuning, and Kaggle submission.

---

## Dataset

The dataset contains passenger information such as:

- HomePlanet
- CryoSleep
- Cabin
- Destination
- Age
- VIP
- RoomService
- FoodCourt
- ShoppingMall
- Spa
- VRDeck
- Name

**Target Variable:**
- `Transported` (True / False)

---

## Project Workflow

### 1. Exploratory Data Analysis (EDA)

- Dataset inspection
- Missing value analysis
- Statistical summary
- Target distribution
- Data visualization

### 2. Feature Engineering

Created additional features to improve model performance:

- Deck
- Cabin Number
- Cabin Side
- Passenger Group
- Family Size
- Total Spend
- No Spending Indicator

Final feature count: **16**

---

### 3. Data Preprocessing

- Missing value imputation
  - Median (Numerical)
  - Most Frequent (Categorical)
- One-Hot Encoding
- Scikit-learn Pipeline
- ColumnTransformer

---

### 4. Models Evaluated

| Model | Validation Accuracy |
|--------|--------------------:|
| Random Forest | 79.41% |
| XGBoost | 81.31% |
| CatBoost | 80.33% |
| Tuned XGBoost | **81.54%** |

Hyperparameter tuning was performed using **RandomizedSearchCV** to improve the XGBoost model.

---

## Model Evaluation

| Metric | Value |
|---------|-------|
| Cross Validation (Mean) | 0.8016 |
| Cross Validation (Std) | 0.0105 |
| Validation Accuracy | 0.8154 |
| Kaggle Public Score | 0.80126 |

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- CatBoost
- Joblib

---

## Project Structure

```
Spaceship_Titanic_Project/
│
├── data/
│   ├── train.csv
│   ├── test.csv
│   └── sample_submission.csv
│
├── notebook/
│   └── Spaceship_Titanic.ipynb
│
├── outputs/
│   └── submission.csv
│
├── models/
│
├── README.md
│
└── requirements.txt
```

---

## Results

- Built and compared multiple machine learning models.
- Improved performance through feature engineering and hyperparameter tuning.
- Achieved a **validation accuracy of 81.54%**.
- Achieved a **Kaggle public leaderboard score of 0.80126**.

---

## Future Improvements

- Advanced feature engineering
- Ensemble learning
- Bayesian hyperparameter optimization
- Native categorical handling with CatBoost

---

## Author

**Bhavanitha R**

Machine Learning Project – Spaceship Titanic Classification