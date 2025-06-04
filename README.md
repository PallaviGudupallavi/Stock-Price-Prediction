# 📊 Stock Price Prediction Using TSLA.csv Dataset

This project involves predicting Tesla's stock price using various supervised machine learning models. The goal is to compare multiple regression techniques and determine the most accurate model based on historical TSLA stock data.

## 📁 Dataset
- Source: `TSLA.csv` (Tesla stock data)
- Features used: `Open`, `High`, `Low`, `Close`, `Volume`
- Target: Adjusted Close Price or Next Day's Closing Price

## 🤖 ML Models Used
1. Linear Regression
2. Logistic Regression (as classification baseline)
3. Support Vector Machine (SVM)
4. Decision Tree Regressor
5. Naive Bayes (on transformed categorical/quantized features)
6. Random Forest Regressor
7. Gradient Boosting Regressor
8. Bagging Regressor

## 🛠️ Tech Stack
- Python
- scikit-learn
- Pandas, NumPy
- Matplotlib & Seaborn (for visualization)

## 📈 Evaluation Metrics
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score
![image](https://github.com/user-attachments/assets/393fd0c8-302d-496c-a311-a5c2b6e1e18b)

## 🔍 Key Steps
- Data preprocessing and feature engineering
- Model training, cross-validation
- Model comparison using error metrics
- Visualization of predictions vs actual prices

## ✅ Results
- Tabular comparison of model metrics
- Visual graphs showing how each model performs on TSLA data
- Found [Best Performing Model: Insert your best result model here]

## 📸 Sample Plots
*(Add line graphs comparing actual vs predicted for top 3 models)*

## 🚀 How to Run
```bash
python stock_prediction.py
