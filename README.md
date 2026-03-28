# 📊 Market Sentiment vs Trader Behavior: A Data Analysis Approach

## 📌 Overview

This project analyzes how market sentiment (Fear vs Greed) impacts trader behavior and performance. By combining sentiment data with historical trading records, the goal is to uncover patterns that can help design smarter trading strategies.

---

## 🎯 Objective

* Understand the relationship between market sentiment and trading outcomes
* Analyze trader behavior under different market conditions
* Generate actionable insights and strategy recommendations

---

## 📂 Dataset

The project uses two datasets:

1. **Market Sentiment Data**

   * Contains daily classification: Fear or Greed

2. **Trader Data (Hyperliquid)**

   * Includes trade-level details such as:

     * Account
     * Execution price
     * Trade size
     * Side (Long/Short)
     * Closed PnL
     * Leverage
     * Timestamp

---

## ⚙️ Methodology

### 1. Data Cleaning

* Removed duplicate records
* Handled missing values
* Converted timestamps into a standard date format

### 2. Data Merging

* Combined sentiment and trading datasets using the date field

### 3. Feature Engineering

* Daily Profit and Loss (PnL)
* Win rate (profit vs loss trades)
* Trade frequency
* Average leverage
* Long/Short ratio

### 4. Exploratory Data Analysis

* Compared trader performance across Fear and Greed periods
* Visualized patterns using boxplots, bar charts, and count plots

---

## 📊 Key Insights

* Traders achieve higher profitability during **Greed periods**
* Trading activity and leverage increase when market sentiment is positive
* Fear periods lead to conservative trading behavior
* High leverage amplifies both gains and losses

---

## 🚀 Strategy Recommendations

* Reduce leverage during Fear periods to manage risk
* Increase trading activity during Greed to capitalize on opportunities
* Use sentiment as a signal for adjusting trading strategies

---

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn (optional for clustering)

---

## ▶️ How to Run

1. Install required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```

2. Open the notebook:

   ```bash
   notebook.ipynb
   ```

3. Run all cells to reproduce results

---

## 📁 Project Structure

```
primetrade-assignment/
│
├── notebook.ipynb
├── README.md
├── report.md
└── data/
```

---

## 🏆 Conclusion

This project demonstrates how market sentiment influences both trading performance and behavior. By leveraging sentiment-driven insights, traders can improve decision-making and manage risk more effectively.

---
