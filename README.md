# Movie-Rating-prediction
# 🎬 Movie Rating Prediction using Regression Analysis

## Project Overview

This project implements a machine learning model to **predict the IMDb rating** of a movie based on its attributes. This is a **regression problem**, aiming to determine the relationship between various features (like Genre, Director, Actors, Revenue, Runtime) and the final score.

This work was completed as part of an internship at **Arch Technologies**.

## 🎯 Methodology and Steps

1.  **Exploratory Data Analysis (EDA):** Cleaned the dataset, handled missing values, and analyzed the distributions of key variables (like Runtime and Revenue).
2.  **Feature Engineering:** Converted categorical data (like 'Genre' and 'Director') into numerical format suitable for modeling.
3.  **Feature Selection:** Identified features strongly correlated with the `Rating` (the target variable).
4.  **Model Training:** Applied a **Regression Model** (e.g., Linear Regression, Random Forest Regressor, etc., based on what you used in the notebook) to train on the prepared data.

## 📊 Data Source

The project uses the `IMDB-Movie-Data.csv` dataset (with 1000 entries), which contains features such as:
* `Title`, `Genre`, `Director`, `Actors`
* `Runtime (minutes)`
* `Revenue (Millions)`
* **`Rating` (Target Variable)**


## 🛠️ Tech Stack

* **Language:** Python
* **Core Libraries:** Pandas, NumPy
* **Machine Learning:** Scikit-learn (for Regression models, training, and evaluation)
* **Visualization:** Matplotlib, Seaborn
