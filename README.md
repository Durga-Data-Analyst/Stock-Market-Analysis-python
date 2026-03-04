# 📈 Stock Market Time Series Analysis

## 📌 Project Overview

This project analyzes historical stock market data to identify price trends, volatility patterns, and return behavior using Python. The analysis focuses on understanding how stock prices move over time and how statistical indicators such as daily returns, moving averages, and volatility can help interpret market behavior.

The project demonstrates time-series data handling, financial metric calculation, and visualization using Python.

---

## 🎯 Objectives

* Analyze historical stock price trends.
* Calculate daily returns to measure price fluctuations.
* Use moving averages to identify long-term and short-term trends.
* Measure market volatility using rolling statistics.
* Identify days with unusually high trading volume.

---

## 🛠 Tools & Technologies

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Jupyter Notebook / VS Code**

---

## 📂 Dataset

The dataset contains historical stock market data with the following columns:

* **Date** – Trading date
* **Open** – Opening price
* **High** – Highest price during the day
* **Low** – Lowest price during the day
* **Close** – Closing price
* **Adj Close** – Adjusted closing price
* **Volume** – Number of shares traded

---

## 📊 Analysis Performed

### 1️⃣ Stock Price Trend Analysis

Visualized the closing price over time to understand long-term price movement.

### 2️⃣ Daily Return Calculation

Daily return was calculated using percentage change in closing price to measure day-to-day price fluctuations.

Formula:

Daily Return = (Today's Close − Yesterday's Close) / Yesterday's Close

### 3️⃣ Moving Average Analysis

Calculated:

* **20-Day Moving Average**
* **50-Day Moving Average**

These indicators smooth short-term fluctuations and highlight longer-term trends.

### 4️⃣ Volatility Analysis

Used **rolling standard deviation of daily returns** to measure market volatility.

Higher volatility indicates greater uncertainty and risk in the market.

### 5️⃣ Trading Volume Analysis

Identified the days with the highest trading volume to analyze unusual market activity.

---

## 📈 Key Insights

* The stock shows identifiable long-term trends over time.
* Daily returns reveal periods of higher and lower market volatility.
* Moving averages help identify trend reversals and momentum shifts.
* Increased trading volume often aligns with significant price movements.
* Volatility spikes typically occur during periods of market uncertainty.

---

## 📁 Project Structure

```
Stock-Market-Analysis/
│
├── stock_analysis.ipynb
├── stock_data.csv
└── README.md
```

---

## 🚀 How to Run the Project

1. Clone this repository
2. Install required libraries

```
pip install pandas numpy matplotlib seaborn
```

3. Open the notebook:

```
stock_analysis.ipynb
```

4. Run the cells to reproduce the analysis and visualizations.

---

## 💡 Skills Demonstrated

* Time series data analysis
* Data cleaning and preprocessing
* Financial metric calculation
* Rolling window analysis
* Data visualization
* Analytical storytelling

---

## 👨‍💻 Author

**Durga Prasad Keshri**
Aspiring Data Analyst | Python | SQL | Excel | Data Visualization
