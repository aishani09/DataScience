# **Bitcoin Price Prediction Using Machine Learning**

## **Overview**
This project predicts Bitcoin prices using machine learning techniques, specifically **LSTM (Long Short-Term Memory)** and **XGBoost** models. It incorporates time-series analysis, exploratory data analysis (EDA), and predictive modeling to understand and forecast Bitcoin's historical price movements.

---

## **Table of Contents**
1. [Problem Statement](#problem-statement)
2. [Data](#data)
3. [Technologies Used](#technologies-used)
4. [Project Workflow](#project-workflow)
5. [Results](#results)

---

## **Problem Statement**
Bitcoin, one of the most volatile cryptocurrencies, has seen significant price fluctuations since its inception. Accurate predictions of its price are valuable for traders, investors, and businesses. This project explores machine learning models to predict the closing price of Bitcoin based on historical data.

---

## **Data**
The dataset contains historical Bitcoin prices, including:
- **Date**
- **Open**, **High**, **Low**, **Close** prices
- **Adj Close** (Adjusted Close price)
- **Volume** (Trading volume)

### **Source**
The dataset used for this project can be found in the repository under `bitcoin.csv`.

---

## **Technologies Used**
1. **Python**: Core programming language.
2. **Libraries**:
   - **Pandas, NumPy**: Data manipulation and cleaning.
   - **Matplotlib, Seaborn**: Data visualization.
   - **Scikit-learn**: Data preprocessing and model evaluation.
   - **XGBoost**: Machine learning model for predictions.
   - **TensorFlow/Keras**: Deep learning framework for LSTM.
3. **Jupyter Notebook**: For interactive development and visualization.

---

## **Project Workflow**
1. **Data Cleaning**:
   - Handled missing or inconsistent values.
   - Parsed the `Date` column and set it as the index for time-series analysis.

2. **Exploratory Data Analysis (EDA)**:
   - Visualized Bitcoin trends over time.
   - Analyzed correlations between features.
   - Examined patterns in trading volume and price fluctuations.

3. **Feature Engineering**:
   - Created new features such as moving averages.
   - Normalized the data for model input.

4. **Model Building**:
   - **LSTM**:
     - Used deep learning for time-series forecasting.
     - Processed data into sequences for training.
   - **XGBoost**:
     - Built a regression model for prediction.
     - Tuned hyperparameters for performance improvement.

5. **Model Evaluation**:
   - Evaluated models using metrics **Root Mean Squared Error (MSE)**.
   - Compared the performance of LSTM and XGBoost.

---

## **Results**
- **LSTM**:
  - RMSE: 7965.10414908383
- **XGBoost**:
  - RMSE: 6085.620477619782

