🚗 Car Price Prediction

This project aims to predict car prices using various regression algorithms. It is built to support a Chinese automobile company entering the U.S. market by helping determine competitive pricing strategies using machine learning.
📁 Project Structure

car_price_prediction/
│
├── car_price _prediction.ipynb  # Main Jupyter notebook with full pipeline
├── README.md                    # Project documentation
└── requirements.txt             # (Optional) Dependencies list

📊 Dataset

The dataset includes car attributes like:

    Brand

    Model

    Engine Size

    Fuel Type

    Transmission

    Mileage

    Year

    Price (target variable)

⚙️ Steps Performed
1. Data Preprocessing

    Handled missing values and cleaned data

    Removed outliers using IQR method

    Feature selection with SelectKBest

    Scaled features using StandardScaler

    Train-test split using train_test_split

2. Model Building

    Linear Regression

    Decision Tree Regressor

    Random Forest Regressor

    Gradient Boosting Regressor

    Support Vector Regressor (SVR)

3. Evaluation Metrics

Models were evaluated using:

    R² Score

    Mean Absolute Error (MAE)

    Mean Squared Error (MSE)

    Root Mean Squared Error (RMSE)

4. Hyperparameter Tuning

Used GridSearchCV to fine-tune model parameters for better performance.
5. Model Deployment

Trained models were saved using joblib for future use and predictions.
📈 Visualizations Included

    Feature importance charts

    Pair plots and heatmaps

    Distribution of price

    Regression plots for model predictions

🧪 How to Run the Notebook

    Clone this repository:

git clone https://github.com/your-username/car_price_prediction.git

    Navigate into the project directory:

cd car_price_prediction

    Install dependencies:

pip install -r requirements.txt

    Launch Jupyter Notebook:

jupyter notebook

    Open car_price _prediction.ipynb and run all cells.

✅ Results

The best performing model was: Random Forest Regressor (or whichever model actually performed best).
