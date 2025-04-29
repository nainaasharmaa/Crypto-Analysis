# Cryptocurrency Market Analysis 🚀

## Project Overview
This project fetches live cryptocurrency data for the top 50 coins using the **CoinGecko API**.  
It processes the data, saves it to an Excel file, and automatically updates every 5 minutes for 30 minutes, enabling real-time analysis.

---

## 📋 Problem Statement
Analyze the live cryptocurrency market by:
- Fetching live prices, market caps, and trading volumes.
- Storing the data in an Excel sheet.
- Updating the data at regular intervals.
- Performing statistical analysis on the collected data.

---

## 🛠 Technologies Used
- **Python**
- **Pandas** — for data manipulation
- **Requests** — for API calls
- **Schedule** — to automate data fetching
- **OpenPyXL** — to handle Excel files

---

## 🔥 Key Features
- Real-time data fetching from CoinGecko API
- Automatic update every 5 minutes
- Excel sheet export with live data
- Statistical analysis including:
  - Price distribution
  - Market cap insights
  - Trading volume distribution
  - Volatility measurement
- Clean dataset with no missing values

---

## 📊 Metrics Collected
- Cryptocurrency Name
- Symbol
- Current Price (USD)
- Market Capitalization
- 24h Trading Volume
- 24h Price Change (%)

---

## ⚙️ How It Works
1. **Import Libraries**  
   Required libraries are imported (`requests`, `pandas`, `schedule`, `time`).

2. **Fetch Crypto Data**  
   The `fetch_crypto_data()` function:
   - Sends a request to CoinGecko API
   - Collects the latest data for the top 50 cryptocurrencies
   - Structures the data into a Pandas DataFrame

3. **Save to Excel**  
   The data is saved into an Excel file for future analysis.

4. **Automate Updates**  
   The data fetching function is scheduled to run **every 5 minutes for 30 minutes**.

---

## 📈 Analysis Highlights
- **Mean cryptocurrency price**: \$5,674.13
- **Standard deviation**: Extremely high (\$21,491), showing wide price variation.
- **Median price**: \$7.52 (most cryptocurrencies are low-valued).
- **Top market cap**: \$1.79 trillion (likely Bitcoin).
- **High trading volume**: Up to \$99.20 billion in 24h.
- **24h Price Change**: Max gain +47.51%, max drop -4.04%.

---

## 🧹 Data Quality
- No missing values detected.
- Data is clean and ready for advanced modeling or visualization.

---
## 📢 Final Conclusion
- The crypto market is dominated by a few large players like Bitcoin and Ethereum.
- Most coins are relatively low in price and market cap.
- Volatility is high, with large 24-hour price swings.
- Continuous live updating provides a dynamic dataset ready for further insights.

> ✨ *This project was built using live data from the [CoinGecko API](https://www.coingecko.com/en/api).*
