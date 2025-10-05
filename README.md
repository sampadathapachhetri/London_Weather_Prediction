# London Weather Prediction 

This project predicts the **mean temperature** based on historical weather data using supervised machine learning. It explores different models and uses **MLflow** for experiment tracking and performance comparison.

---

## Project Overview

Commercial banks, industries, and researchers rely on accurate temperature prediction for decision-making and planning.  
In this project, we:
- Preprocessed and analyzed weather data
- Performed **feature selection** using correlation analysis
- Built and compared multiple **tree-based regression models**
- Used **MLflow** to track parameters, metrics, and results

---

## Features

- Data preprocessing and cleaning (handling missing values)
- Feature engineering and selection
- Model training with different `max_depth` values
- Performance tracking using MLflow
- Evaluation using RMSE (Root Mean Square Error)

---

## Technologies Used

- **Python 3.x**
- **Pandas** – Data manipulation  
- **NumPy** – Numerical operations  
- **Matplotlib & Seaborn** – Data visualization  
- **Scikit-learn** – Model building and evaluation  
- **MLflow** – Experiment tracking  

---

## Dataset

The dataset contains monthly weather metrics such as:
- Cloud cover  
- Sunshine duration  
- Precipitation  
- Pressure  
- Global radiation  
- Mean temperature (target variable)

---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/weather-mlflow-prediction.git
   cd weather-mlflow-prediction
