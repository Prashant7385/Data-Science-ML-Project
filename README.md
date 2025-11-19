🌫️ Air Quality Index (AQI) Prediction — Machine Learning Project
Regression Modeling using Linear, Ridge & Lasso | Delhi Air Quality Dataset

This project predicts the Air Quality Index (AQI) using Delhi’s atmospheric pollution data.
The notebook includes data preprocessing, EDA, regression models, evaluation metrics, and insights — making it ideal for Machine Learning, Data Science, and Portfolio demonstration.

📌 Project Highlights

✔ Cleaned dataset (0 missing values, 0 duplicates)

✔ Extracted temporal features (Month, Year, Days, Holidays)

✔ Performed correlation analysis

✔ Built Linear, Ridge & Lasso regression models

✔ Achieved R² ≈ 0.88 on AQI prediction

✔ Plotted Actual vs Predicted AQI

✔ Analyzed feature importance using Lasso

📊 Dataset

Delhi Air Quality Dataset containing:

Date-based features: Month, Year, Days, Holiday Count

Pollutants: PM2.5, PM10, NO2, SO2, CO, Ozone

Output variable: AQI (Air Quality Index)

📌 Kaggle Notebook:
👉 https://www.kaggle.com/code/prashant7385/notebook9ecbfd3fa1

📂 Project Structure
air-quality-prediction/
│
├── data/
│   └── delhi_air_quality.csv          # dataset file (not included)
│
├── notebook/
│   └── aqi_prediction.ipynb           # jupyter notebook
│
├── images/                             # EDA & model plots
│   ├── heatmap.png
│   ├── actual_vs_pred.png
│   └── feature_importance.png
│
├── requirements.txt                    # dependencies
└── README.md                           # documentation

🧹 Data Cleaning & Preprocessing

Removed duplicates → 0 found

Checked NaN/missing values → 0 found

Dropped non-numeric Date column

Extracted Month, Year, and Number of Days

Ensured all columns are numeric

Prepared X (features) and y (target)

📈 Exploratory Data Analysis

Key observations:

PM2.5 and PM10 have high correlation with AQI

Ozone, NO2 also contribute significantly

Low multicollinearity → suitable for regression

Seasonal patterns across months

Visuals included:

🔥 Correlation heatmap

🔵 Actual vs Predicted scatterplot

🟩 Lasso feature importance chart

🤖 Machine Learning Models

Trained 3 regression models:

Model	R² Score	RMSE
Linear Regression	0.88186	39.15
Ridge Regression	0.88187	39.15
Lasso Regression (Best)	0.88189	39.14

📌 Lasso Regression performed best

🚀 How to Run the Notebook
1. Install dependencies
pip install -r requirements.txt

2. Start Jupyter Notebook
jupyter notebook

3. Open the file
notebook/aqi_prediction.ipynb

🧠 Skills Demonstrated

Data Preprocessing

Feature Engineering

Exploratory Data Analysis

Machine Learning (Regression)

Model Performance Evaluation

Visualization (Matplotlib, Seaborn)

GitHub Project Structuring

🔮 Future Improvements

Predict AQI for 2026–27 (Time-series forecasting)

Add ARIMA / Prophet forecasting models

Deploy app using Streamlit or FastAPI

Build a real-time dashboard

👨‍💻 Author

Prashant Pandey
Machine Learning Enthusiast

🔗 Kaggle: https://www.kaggle.com/prashant7385
