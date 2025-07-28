# 🚗 Used Car Price Prediction

This project builds a machine learning model to predict the selling price of used cars based on their attributes such as brand, vehicle type, fuel type, gearbox, power, and mileage. The pipeline includes data preprocessing, exploratory data analysis, feature engineering, model training, evaluation, and price prediction.
📘 Notebook

Used_Car_Price_Prediction.ipynb
The notebook contains the complete workflow:

    📥 Data Loading (CSV/Excel)

    🔍 Exploratory Data Analysis (EDA)

    🧹 Data Cleaning & Preprocessing

    🧠 Feature Engineering (e.g., Car Age)

    🤖 Model Training (Linear Regression, Random Forest)

    📊 Model Evaluation (R², MAE, RMSE)

    📈 Visualizations (Boxplots, Correlation Heatmap, Feature Importance)

    🔮 Price Predictions and Comparisons

📊 Dataset

    Source: Uploaded custom dataset (Used_Cars_Dataset.csv)

    Total Records: 11,111 entries

    Key Features:

        brand, vehicleType, fuelType, gearbox

        powerPS, kilometer, notRepairedDamage

        carAge (engineered from year of registration)

    Target: price (selling price in EUR)

⚙️ Technologies Used

    Python 3.8+

    Jupyter Notebook

    Libraries:

        pandas, numpy – Data manipulation

        seaborn, matplotlib – Visualization

        scikit-learn – Model building & evaluation

🚀 How to Run the Project

    Clone this repository or download the files.

    Make sure you have Python and Jupyter installed.

    Install the required libraries:

pip install -r requirements.txt

Open the notebook:

    jupyter notebook Used_Car_Price_Prediction.ipynb

📦 Output

    Model performance metrics (R², MAE, RMSE)

    Feature importance visualization

    Actual vs Predicted Price comparison
