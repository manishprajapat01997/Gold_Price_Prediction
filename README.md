# Gold Price Prediction 📉💰

## 📚 Project Overview
This project predicts **gold prices (GLD)** using various financial data, including stock market indices, oil prices, silver prices, and currency exchange rates. The goal is to build accurate models that can forecast gold price trends based on historical data.

### 🏅 Key Features:
- **SPX**: S&P 500 Index (Stock market indicator)
- **GLD**: Gold Price (target variable)
- **USO**: Oil Prices (Crude oil index)
- **SLV**: Silver Prices
- **EUR/USD**: Euro to USD exchange rate

## 🧹 Data Preprocessing
- **No missing values**: All data is complete.
- **No duplicates**: Dataset is cleaned.
- **Outliers**: Detected and managed for better model accuracy.
- **Feature Correlation**: Strong relationships found between gold prices and stock indices (SPX, SLV).

## 📊 Visualizations:
1. **Gold Price Trend**: Line chart showing gold price fluctuations over time.
2. **Gold Price Distribution**: Histogram to see how gold prices are distributed (with a smooth KDE curve).
3. **30-Day Rolling Average**: Smoothing technique to highlight long-term price trends.
4. **Interactive Gold Price Trend**: Interactive plot using Plotly for users to zoom and explore data in more detail.



## Conclusion 🔑
- **Best Features**: SPX, SLV, EUR/USD are strong predictors for gold prices.
- **Model Selection**: Random Forest outperforms Decision Tree in terms of stability and prediction time.

### ⚖️ Model Comparison:
- Both models are highly accurate, with **Random Forest** slightly outperforming **Decision Tree** due to better handling of complex data patterns and faster prediction times.

## 🔑 Key Insights:
- **Best Predictors for Gold Price**: SPX, SLV, EUR/USD have the strongest influence on gold price movements.
- **Model Recommendation**: **Random Forest** is recommended for more stable and accurate predictions.

## 🚀 How to Run:
1. **Clone the repository**:
   ```bash
   git clone https://github.com/username/gold-price-prediction.git
   ```
2. **Install necessary packages**:
   ```bash
   pip install -r requirements.txt
   ```
3. **Run the Jupyter Notebook**:
   ```bash
   jupyter notebook
   ```

## 📦 Libraries Used:
- **pandas**: Data manipulation
- **numpy**: Numerical computations
- **matplotlib** & **seaborn**: Data visualization
- **plotly**: Interactive plots
- **scikit-learn**: Machine learning models


### 🚀 Summary:
This project provides a detailed approach to predicting gold prices using machine learning models. It includes data cleaning, exploratory analysis, feature selection, and model building. The interactive visualizations and model performance metrics allow users to easily explore the relationships in the data and gain insights into gold price movements.

Feel free to experiment with the code and models to improve predictions!
