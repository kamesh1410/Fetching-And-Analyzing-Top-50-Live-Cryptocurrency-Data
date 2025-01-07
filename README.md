# 🌟 **Fetching And Analyzing Top 50 Live Cryptocurrency Data** 🌟

This project leverages the CoinGecko API to fetch real-time data for the top 50 cryptocurrencies by market capitalization, perform detailed data analysis, and generate visually appealing reports and charts.

---

## 🚀 **Project Overview**

This project is aimed at providing a comprehensive overview of the cryptocurrency market by:
- Fetching live data for the top 50 cryptocurrencies.
- Performing data analysis to extract meaningful insights.
- Visualizing key metrics like market cap, price distribution, and price changes.

---

## 🛠️ **Steps to Execute the Project**

### 1. 📦 **Install Required Libraries**

Before running the project, you need to install the following libraries:


---

### 2. 🌐 **Fetch Live Data**

The script uses the CoinGecko API to retrieve the latest data for the Top 50 Cryptocurrencies by market capitalization.

Key metrics fetched include:
- **Cryptocurrency Name**
- **Symbol**
- **Current Price (USD)**
- **Market Capitalization**
- **24-Hour Trading Volume**
- **24-Hour Price Change (Percentage)**

---

### 3. 📊 **Perform Data Analysis**

The analysis includes:
- **Top 5 Cryptocurrencies by market capitalization.**
- **Average Price of the top 50 cryptocurrencies.**
- **Identification of the cryptocurrency with the highest and lowest 24-hour price change (percentage).**

---

### 4. 📈 **Visualize the Data**

The project generates several beautiful visualizations:
- **Top 5 Cryptocurrencies by Market Capitalization:** Bar Chart.
- **Distribution of Cryptocurrency Prices:** Histogram.
- **Highest and Lowest 24-Hour Price Change:** Bar Plot.

---

### 5. 💾 **Save the Data and Visualizations**

The live-updating Excel file (`top_50_cryptos.xlsx`) is saved, which updates every 5 minutes.  
Visualizations are saved as PNG files for sharing or reporting:
- `top_5_crypto_currencies.png`
- `Distributions_Of_Crypto_Currency_Prices.png`
- `Highest_and_Lowest_24-Hour_Price_Change.png`

---

### 6. 📑 **Generate PDF Report**

A PDF report (`Cryptocurrency_Analysis_Report.pdf`) is automatically generated and includes:
- A summary of the analysis.
- The visualizations created.

Run the script to generate the report and ensure the visualization PNG files are in the same directory as the script.

---

## 📂 **Output Files**

The following output files are generated:
- **Excel File:** `top_50_cryptos.xlsx` (Updates every 5 minutes)
- **PNG Visualizations:**
    - `top_5_crypto_currencies.png`
    - `Distributions_Of_Crypto_Currency_Prices.png`
    - `Highest_and_Lowest_24-Hour_Price_Change.png`
- **PDF Report:** `Cryptocurrency_Analysis_Report.pdf`

---

## ⚠️ **Notes for Reviewers**

- The live-updating Excel file may not work on Google Sheets due to API access limitations.
- Ensure you have set up your local environment and installed all dependencies before running the script.

---

## 💬 **Contact & Acknowledgments**

- Project by: G. Kamesh
- Email: kamesh743243@gmail.com

Special thanks to CoinGecko API for providing the data and Python Libraries like requests, pandas, matplotlib, seaborn, openpyxl, and fpdf for making the analysis and visualization seamless.

---

