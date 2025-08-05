# 🚗 Car Price Prediction using Machine Learning

Welcome to the **Car Price Prediction** project! This repository demonstrates how machine learning can be used to estimate car prices based on various features like brand, year, mileage, engine size, and more.

---

## 📁 Files in this Repository

- `car_price _prediction.ipynb` – Main Jupyter notebook with full code.
- `README.md` – You're here!
- `used-cars-data.csv` *(required)* – Source dataset (ensure it’s placed in the same folder).

---

## 🧠 Objective

A Chinese automobile company is entering the U.S. market and wants to **predict optimal car prices** using historical data. This project:
- Preprocesses raw car data.
- Removes outliers using statistical techniques.
- Selects meaningful features.
- Trains multiple regression models.
- Evaluates models using industry-standard metrics.
- Tunes models with `GridSearchCV`.
- Saves the best model for future use.

---

## 🔧 Technologies & Libraries

```python
pandas         numpy
matplotlib     seaborn
sklearn (linear_model, tree, ensemble, svm, metrics, model_selection)
joblib         PowerTransformer

📊 Data Overview

    📌 File: (https://data.world/data-society/used-cars-data)

    🔢 Features include:

        Brand, Model, Year

        Mileage

        Engine Size

        Fuel Type

        Transmission

        Price (Target)

🧼 1. Data Preprocessing
✅ Tasks Performed:

    Load and inspect data

    Drop irrelevant or null columns

    Outlier Removal: Using IQR Method

    Feature Selection: Using SelectKBest and f_regression

    Scaling: Using StandardScaler

    Split data using train_test_split

from sklearn.preprocessing import StandardScaler
from sklearn.feature_selection import SelectKBest, f_regression

🤖 2. Model Building
Algorithm	Library
Linear Regression	sklearn.linear_model
Decision Tree Regressor	sklearn.tree
Random Forest Regressor	sklearn.ensemble
Gradient Boosting Regressor	sklearn.ensemble
Support Vector Regressor	sklearn.svm
🧪 3. Model Evaluation

Metrics used:

    ✅ R² Score

    📉 MAE – Mean Absolute Error

    📉 MSE – Mean Squared Error

    📉 RMSE – Root Mean Squared Error

Evaluation code sample:

from sklearn.metrics import r2_score, mean_squared_error, mean_absolute_error

🔍 4. Hyperparameter Tuning

Used GridSearchCV to find the best combination of model parameters.

from sklearn.model_selection import GridSearchCV

💾 5. Model Saving

Trained model saved using:

import joblib
joblib.dump(best_model, 'car_price_model.pkl')

📈 Visualizations Included

    📌 Boxplots for outlier detection

    🔥 Heatmaps for correlation analysis

    📊 Distribution plots

    🧮 Regression result comparisons

Example:

sns.heatmap(df.corr(), annot=True)

🚀 How to Run the Project

    Clone this repo:

git clone https://github.com/your-username/car-price-prediction.git
cd car-price-prediction

    Install dependencies:

pip install -r requirements.txt

    Launch the notebook:

jupyter notebook

    Open car_price _prediction.ipynb and run all cells.

🔮 Future Improvements

    Add deep learning models (TensorFlow, Keras)

    Include location-based price predictions

    Deploy the model with a web app (Flask or Streamlit)
