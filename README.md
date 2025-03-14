# Air Quality Index Prediction Model with Python
📌 Project Overview

This project uses Python and Machine Learning to analyze air quality data and predict the Air Quality Index (AQI). The goal is to identify key pollutants and provide early warnings for pollution control.

🚀 Features

Data Preprocessing: Handling missing values and normalizing pollutant levels.

Exploratory Data Analysis (EDA): Visualizing pollutant distribution and correlations.

AQI Prediction: Using Linear Regression, Decision Tree, Random Forest, and KNN models.

Performance Evaluation: Comparing models using MSE and R-squared values.

📊 Dataset

Includes pollutant levels from various cities:

PM2.5, PM10 – Particulate matter affecting respiratory health.

NO, NO2, NH3, CO, SO2, O3 – Key air pollutants.

Benzene, Toluene, Xylene – Harmful VOCs.

🛠 Technologies Used

Python, Jupyter Notebook

Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

🔍 Methodology

Data Collection & Preprocessing: Dropped non-numeric columns, handled missing values.

Data Visualization: Heatmaps and correlation analysis.

Outlier Detection: Used Interquartile Range (IQR) Method.

Model Training & Prediction:

Trained Linear Regression, Decision Tree, Random Forest, and KNN models.

Evaluated and selected the best-performing model.

📈 Results

Identified key pollutants affecting AQI.

Classified air quality as Good, Moderate, or Hazardous.

🔮 Future Enhancements

Real-time Data Integration

Deep Learning Models

Mobile/Web Application

🏗 How to Run

Clone this repository:

git clone https://github.com/yourusername/air-quality-prediction.git

Install dependencies:

pip install pandas numpy scikit-learn matplotlib seaborn

Run the Jupyter Notebook.
