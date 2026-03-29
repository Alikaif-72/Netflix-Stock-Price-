# 📊 Netflix Stock Price Analysis:-

Dashboard URL on Claude Interface - https://claude.ai/public/artifacts/69cc4bc3-8f40-4fff-a3c9-9f28b1150786
                                   OR 
Dashboard URL on Netlify Interface - astonishing-torte-0b3aa4.netlify.app    

## 📌 Project Overview

This project focuses on analyzing Netflix stock price data using Python. The objective is to understand stock behavior, identify trends, measure risk, and generate meaningful insights for better decision-making.

---

## 📂 Dataset Information

The dataset contains historical stock price data with the following key columns:

* Date
* Open
* High
* Low
* Close
* Volume

Additionally, several new features were created to enhance analysis.

---

## ⚙️ Data Preprocessing & Feature Engineering

### 🔹 Data Cleaning

* Handled missing values
* Removed duplicate records
* Converted `date` column into datetime format
* Standardized column names for consistency

---

## 🔹 Feature Engineering (Created Columns & Logic)

### 1. 📈 Price Change

**Formula:**

```
price_change = close - open
```

**Logic:**
Measures the difference between opening and closing price to identify daily gain/loss.

---

### 2. 📊 Price Range

**Formula:**

```
price_range = high - low
```

**Logic:**
Represents intraday volatility (how much price moved in a day).

---

### 3. 📉 Percentage Gain/Loss

**Formula:**

```
pct_gain_loss = (close - previous_close) / previous_close * 100
```

**Logic:**
Shows percentage return compared to the previous day.

---

### 4. 📅 Time-Based Features

**Derived from date:**

* year → Extracted year
* month → Extracted month
* day → Day of month
* day_name → Name of the day

**Logic:**
Helps in identifying time-based patterns.

---

### 5. 📊 Moving Averages

**Formula:**

```
ma_7 = 7-day rolling mean of close
ma_30 = 30-day rolling mean of close
```

**Logic:**

* MA_7 → Short-term trend
* MA_30 → Long-term trend

---

### 6. ⚠️ Volatility

**Formula:**

```
volatility = rolling standard deviation of daily returns (7 days)
```

**Logic:**
Measures risk by calculating how much the stock price fluctuates.

---

### 7. 🚦 Risk Level

**Logic:**

```
High Risk → volatility > average volatility
Low Risk → volatility <= average volatility
```

**Purpose:**
Categorizes days based on risk level.

---

### 8. 📊 Volume (in Millions)

**Formula:**

```
volume_per_million = volume / 1,000,000
```

**Logic:**
Improves readability of large numbers.

---

### 9. 📈 Market Trend

**Logic:**

```
Bullish → close > open  
Bearish → close < open
```

**Purpose:**
Identifies daily market sentiment.

---

## 📊 Data Visualization

The following visualizations were created:

* Stock Price Trend (Date vs Close)
* Moving Average Comparison (MA_7 vs MA_30)
* Volatility Over Time
* Trading Volume Analysis
* Daily Return Distribution
* Market Trend Distribution
* Volatility vs Return
* Day-wise Performance

---

## 🔍 Observations

* The stock price shows continuous fluctuations over time
* Both profit and loss days are present, indicating active trading
* Volatility varies across different periods
* Trading volume is inconsistent, reflecting changing market activity
* Moving averages highlight both short-term and long-term trends

---

## 💡 Insights

* High volatility periods indicate increased market risk
* Short-term trends react faster compared to long-term trends
* Frequent switching between profit and loss indicates active trading behavior
* High trading volume often aligns with significant price changes
* Market exhibits both stable and unstable phases

---

## 📈 Recommendations

* Investors should be cautious during high volatility periods
* Short-term traders can use moving averages for quick decisions
* Long-term investors should focus on stable trends
* High volume periods can help identify entry and exit points
* Combining volatility and trend indicators improves decision-making

---

## 🛠️ Tools & Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## 🚀 Conclusion

This analysis provides a comprehensive understanding of Netflix stock behavior, including trends, volatility, and market sentiment. The insights derived can assist both short-term traders and long-term investors in making informed decisions.

---

## 📌 Author

**Your Name**

---


## 📌 Project Overview

This project focuses on analyzing Netflix stock price data using Python. The objective is to understand stock behavior, identify trends, measure risk, and generate meaningful insights for better decision-making.

---

## 📂 Dataset Information

The dataset contains historical stock price data with the following key columns:

* Date
* Open
* High
* Low
* Close
* Volume

Additionally, several new features were created to enhance analysis.

---

## ⚙️ Data Preprocessing & Feature Engineering

### 🔹 Data Cleaning

* Handled missing values
* Removed duplicate records
* Converted `date` column into datetime format
* Standardized column names for consistency

---

## 🔹 Feature Engineering (Created Columns & Logic)

### 1. 📈 Price Change

**Formula:**

```
price_change = close - open
```

**Logic:**
Measures the difference between opening and closing price to identify daily gain/loss.

---

### 2. 📊 Price Range

**Formula:**

```
price_range = high - low
```

**Logic:**
Represents intraday volatility (how much price moved in a day).

---

### 3. 📉 Percentage Gain/Loss

**Formula:**

```
pct_gain_loss = (close - previous_close) / previous_close * 100
```

**Logic:**
Shows percentage return compared to the previous day.

---

### 4. 📅 Time-Based Features

**Derived from date:**

* year → Extracted year
* month → Extracted month
* day → Day of month
* day_name → Name of the day

**Logic:**
Helps in identifying time-based patterns.

---

### 5. 📊 Moving Averages

**Formula:**

```
ma_7 = 7-day rolling mean of close
ma_30 = 30-day rolling mean of close
```

**Logic:**

* MA_7 → Short-term trend
* MA_30 → Long-term trend

---

### 6. ⚠️ Volatility

**Formula:**

```
volatility = rolling standard deviation of daily returns (7 days)
```

**Logic:**
Measures risk by calculating how much the stock price fluctuates.

---

### 7. 🚦 Risk Level

**Logic:**

```
High Risk → volatility > average volatility
Low Risk → volatility <= average volatility
```

**Purpose:**
Categorizes days based on risk level.

---

### 8. 📊 Volume (in Millions)

**Formula:**

```
volume_per_million = volume / 1,000,000
```

**Logic:**
Improves readability of large numbers.

---

### 9. 📈 Market Trend

**Logic:**

```
Bullish → close > open  
Bearish → close < open
```

**Purpose:**
Identifies daily market sentiment.

---

## 📊 Data Visualization

The following visualizations were created:

* Stock Price Trend (Date vs Close)
* Moving Average Comparison (MA_7 vs MA_30)
* Volatility Over Time
* Trading Volume Analysis
* Daily Return Distribution
* Market Trend Distribution
* Volatility vs Return
* Day-wise Performance

---

## 🔍 Observations

* The stock price shows continuous fluctuations over time
* Both profit and loss days are present, indicating active trading
* Volatility varies across different periods
* Trading volume is inconsistent, reflecting changing market activity
* Moving averages highlight both short-term and long-term trends

---

## 💡 Insights

* High volatility periods indicate increased market risk
* Short-term trends react faster compared to long-term trends
* Frequent switching between profit and loss indicates active trading behavior
* High trading volume often aligns with significant price changes
* Market exhibits both stable and unstable phases

---

## 📈 Recommendations

* Investors should be cautious during high volatility periods
* Short-term traders can use moving averages for quick decisions
* Long-term investors should focus on stable trends
* High volume periods can help identify entry and exit points
* Combining volatility and trend indicators improves decision-making

---

## 🛠️ Tools & Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## 🚀 Conclusion

This analysis provides a comprehensive understanding of Netflix stock behavior, including trends, volatility, and market sentiment. The insights derived can assist both short-term traders and long-term investors in making informed decisions.

---

## 📌 Author

**Your Name**

---


## 📌 Project Overview

This project focuses on analyzing Netflix stock price data using Python. The objective is to understand stock behavior, identify trends, measure risk, and generate meaningful insights for better decision-making.

---

## 📂 Dataset Information

The dataset contains historical stock price data with the following key columns:

* Date
* Open
* High
* Low
* Close
* Volume

Additionally, several new features were created to enhance analysis.

---

## ⚙️ Data Preprocessing & Feature Engineering

### 🔹 Data Cleaning

* Handled missing values
* Removed duplicate records
* Converted `date` column into datetime format
* Standardized column names for consistency

---

## 🔹 Feature Engineering (Created Columns & Logic)

### 1. 📈 Price Change

**Formula:**

```
price_change = close - open
```

**Logic:**
Measures the difference between opening and closing price to identify daily gain/loss.

---

### 2. 📊 Price Range

**Formula:**

```
price_range = high - low
```

**Logic:**
Represents intraday volatility (how much price moved in a day).

---

### 3. 📉 Percentage Gain/Loss

**Formula:**

```
pct_gain_loss = (close - previous_close) / previous_close * 100
```

**Logic:**
Shows percentage return compared to the previous day.

---

### 4. 📅 Time-Based Features

**Derived from date:**

* year → Extracted year
* month → Extracted month
* day → Day of month
* day_name → Name of the day

**Logic:**
Helps in identifying time-based patterns.

---

### 5. 📊 Moving Averages

**Formula:**

```
ma_7 = 7-day rolling mean of close
ma_30 = 30-day rolling mean of close
```

**Logic:**

* MA_7 → Short-term trend
* MA_30 → Long-term trend

---

### 6. ⚠️ Volatility

**Formula:**

```
volatility = rolling standard deviation of daily returns (7 days)
```

**Logic:**
Measures risk by calculating how much the stock price fluctuates.

---

### 7. 🚦 Risk Level

**Logic:**

```
High Risk → volatility > average volatility
Low Risk → volatility <= average volatility
```

**Purpose:**
Categorizes days based on risk level.

---

### 8. 📊 Volume (in Millions)

**Formula:**

```
volume_per_million = volume / 1,000,000
```

**Logic:**
Improves readability of large numbers.

---

### 9. 📈 Market Trend

**Logic:**

```
Bullish → close > open  
Bearish → close < open
```

**Purpose:**
Identifies daily market sentiment.

---

## 📊 Data Visualization

The following visualizations were created:

* Stock Price Trend (Date vs Close)
* Moving Average Comparison (MA_7 vs MA_30)
* Volatility Over Time
* Trading Volume Analysis
* Daily Return Distribution
* Market Trend Distribution
* Volatility vs Return
* Day-wise Performance

---

## 🔍 Observations

* The stock price shows continuous fluctuations over time
* Both profit and loss days are present, indicating active trading
* Volatility varies across different periods
* Trading volume is inconsistent, reflecting changing market activity
* Moving averages highlight both short-term and long-term trends

---

## 💡 Insights

* High volatility periods indicate increased market risk
* Short-term trends react faster compared to long-term trends
* Frequent switching between profit and loss indicates active trading behavior
* High trading volume often aligns with significant price changes
* Market exhibits both stable and unstable phases

---

## 📈 Recommendations

* Investors should be cautious during high volatility periods
* Short-term traders can use moving averages for quick decisions
* Long-term investors should focus on stable trends
* High volume periods can help identify entry and exit points
* Combining volatility and trend indicators improves decision-making

---

## 🛠️ Tools & Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## 🚀 Conclusion

This analysis provides a comprehensive understanding of Netflix stock behavior, including trends, volatility, and market sentiment. The insights derived can assist both short-term traders and long-term investors in making informed decisions.

---

## 📌 Author

**Alikaif jafri**

---

