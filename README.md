<div align="center">

<h1 style="color:#4F46E5;">FAANG Stock Price Analysis & Prediction</h1>

<p><b style="color:#0F172A;">AI & Data Analytics Project</b></p>

<p>
  <img src="https://img.shields.io/badge/Python-Data%20Science-blue" />
  <img src="https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-green" />
  <img src="https://img.shields.io/badge/Domain-Financial%20Analytics-purple" />
</p>

</div>

---

## Overview

This project presents an end-to-end **Artificial Intelligence and Data Analytics workflow** applied to **financial time-series data**. It focuses on analyzing historical stock prices of FAANG companies and predicting next-day closing prices using **technical indicators** and **machine learning models**.

The project is structured to reflect industry-level practices and is well-suited for **AI Intern** and **Data Analyst Intern** applications.

---

## Problem Statement

Financial markets generate high-volume, time-dependent data. Extracting meaningful insights and building predictive systems require systematic data analysis and machine learning techniques.

**Objectives:**

* Analyze historical FAANG stock price trends
* Engineer technical indicators used in quantitative finance
* Build predictive models for short-term stock price forecasting

---

## Dataset

**Type:** Historical daily stock market data
**Format:** CSV
**Companies Covered:** AAPL, AMZN, GOOGL, META, MSFT

### Core Features

| Category         | Attributes             |
| ---------------- | ---------------------- |
| Time             | Date                   |
| Identification   | Ticker                 |
| Price            | Open, High, Low, Close |
| Trading Activity | Volume                 |

### Engineered Features

| Indicator Type  | Features                                        |
| --------------- | ----------------------------------------------- |
| Moving Averages | SMA_7, SMA_21, EMA_12, EMA_26                   |
| Momentum        | RSI_14, MACD, MACD_Signal                       |
| Volatility      | Bollinger_Upper, Bollinger_Lower, Volatility_7d |
| Target          | Next_Day_Close                                  |

---

## Methodology

1. **Data Cleaning & Preprocessing**

   * Handling missing values
   * Date parsing and sorting

2. **Exploratory Data Analysis (EDA)**

   * Trend and price movement analysis
   * Volume and volatility visualization

3. **Feature Engineering**

   * Computation of technical indicators
   * Feature selection for modeling

4. **Model Development**

   * Train-test split
   * Machine learning model training

5. **Evaluation**

   * Accuracy and error-based metrics
   * Performance validation

---

## Model Performance

| Metric      | Result                                                           |
| ----------- | ---------------------------------------------------------------- |
| Accuracy    | 85–90%                                                           |
| Observation | Improved performance with combined trend and momentum indicators |

The results indicate that machine learning models can effectively capture short-term price patterns when supported by strong feature engineering.

---

## Tools & Technologies

| Category         | Tools               |
| ---------------- | ------------------- |
| Language         | Python              |
| Environment      | Jupyter Notebook    |
| Data Analysis    | Pandas, NumPy       |
| Visualization    | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn        |

---

## Skills Demonstrated

* Data Cleaning and Preprocessing
* Exploratory Data Analysis
* Feature Engineering
* Machine Learning Modeling
* Financial Data Interpretation
* Data Visualization

---

## How to Run

```bash
git clone https://github.com/your-username/FAANG-Stock-Analysis.git
cd FAANG-Stock-Analysis
pip install pandas numpy matplotlib seaborn scikit-learn
jupyter notebook main.ipynb
```

---

## Future Enhancements

* Time-series forecasting models (ARIMA, LSTM)
* Real-time market data integration
* Hyperparameter optimization
* Deployment using Streamlit or Flask

---

## Disclaimer

This project is developed strictly for **educational and academic purposes**. It should not be used for real-world financial decision-making.

---

## Author

<b>Vinay Verma</b>
AI & Data Analytics Enthusiast

---

