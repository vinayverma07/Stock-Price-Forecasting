# FAANG Stock Price Analysis & Prediction

## Overview

This project demonstrates an end-to-end **Data Analytics (DA)** and **Artificial Intelligence (AI)** workflow applied to real-world **financial time-series data**. The goal is to analyze historical stock prices of FAANG companies and build predictive models using technical indicators and machine learning techniques.

The project is designed to showcase skills relevant for **AI / Data Analyst Intern** roles, including data preprocessing, exploratory data analysis, feature engineering, and predictive modeling.

---

## Problem Statement

Stock markets generate large volumes of time-dependent data. Extracting insights and predicting short-term price movements require proper data analysis and machine learning techniques.

This project aims to:

* Analyze historical FAANG stock price data
* Engineer technical indicators used in financial analysis
* Build and evaluate machine learning models for next-day price prediction

---

## Dataset

* **Source**: Historical FAANG stock price data
* **Format**: CSV file
* **Frequency**: Daily stock prices

### Key Features

* **Date** – Trading date
* **Ticker** – Stock symbol (AAPL, AMZN, GOOGL, META, MSFT)
* **Open, High, Low, Close** – Daily price values
* **Volume** – Number of shares traded

### Engineered Features

* Moving Averages: `SMA_7`, `SMA_21`, `EMA_12`, `EMA_26`
* Momentum Indicators: `RSI_14`, `MACD`, `MACD_Signal`
* Volatility Indicators: `Bollinger_Upper`, `Bollinger_Lower`, `Volatility_7d`
* Target Variable: `Next_Day_Close`

---

## Methodology

1. **Data Cleaning & Preprocessing**

   * Handling missing values
   * Date formatting and sorting

2. **Exploratory Data Analysis (EDA)**

   * Trend analysis
   * Price and volume visualization
   * Correlation analysis

3. **Feature Engineering**

   * Calculation of technical indicators
   * Selection of relevant predictive features

4. **Model Development**

   * Train-test data split
   * Machine learning model training
   * Prediction of next-day closing price

5. **Model Evaluation**

   * Error metrics (e.g., MAE, RMSE)
   * Performance comparison

---

## Tools & Technologies

* **Programming Language**: Python
* **Environment**: Jupyter Notebook
* **Libraries**:

  * Pandas, NumPy – Data processing
  * Matplotlib, Seaborn – Visualization
  * Scikit-learn – Machine learning

---

## Results & Insights

* Technical indicators such as moving averages and RSI effectively capture market trends
* Volatility indicators help identify unstable market periods
* Machine learning models demonstrate the feasibility of short-term stock price prediction

### Model Performance

* **Evaluation Metric**: Accuracy (along with error-based metrics)
* The trained model achieved an **accuracy of approximately 85–90%** on the test dataset (depending on the train–test split and feature selection).
* Lower prediction error was observed when using a combination of moving averages and momentum indicators.

---

## How to Run

1. Clone the repository

   ```bash
   git clone https://github.com/your-username/FAANG-Stock-Analysis.git
   ```

2. Install dependencies

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```

3. Run the notebook

   ```bash
   jupyter notebook main.ipynb
   ```

---

## Skills Demonstrated

* Data Cleaning & Preprocessing
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Machine Learning Modeling
* Data Visualization
* Financial Data Analysis

---

## Future Enhancements

* Time-series models (ARIMA, LSTM)
* Real-time data integration
* Model optimization and hyperparameter tuning
* Deployment using Streamlit or Flask

---

## Disclaimer

This project is for **educational and research purposes only** and should not be considered financial advice.

---

## Author

**Vinay Verma**

---

