## Fetching-And-Analyzing-Top-50-Live-Cryptocurrency-Data
## Project Overview
- This project fetches live cryptocurrency data using the CoinGecko API, performs data analysis, and visualizes the results.
## Steps to Execute the Project
## 1. Install Required Libraries:
- requests,pandas,matplotlib,seaborn,openpyxl,fpdf
## 2. Fetch Live Data:
- The script uses the CoinGecko API to fetch live data for the top 50 cryptocurrencies by market capitalization.
- Key metrics fetched include:
- Cryptocurrency Name
- Symbol
- Current Price (USD)
- Market Capitalization
- 24-Hour Trading Volume
- 24-Hour Price Change (Percentage)
## 3. Perform Data Analysis:
- The analysis includes:
- Identifying the top 5 cryptocurrencies by market capitalization.
- Calculating the average price of the top 50 cryptocurrencies.
- Finding the cryptocurrency with the highest and lowest 24-hour percentage price change.
## 4. Visualize the Data:
- Visualizations generated:
- Top 5 Cryptocurrencies by Market Capitalization (bar chart).
- Distribution of Cryptocurrency Prices (histogram).
- Highest and Lowest 24-Hour Percentage Price Change (highlighted bar plot).
## 5. Save the Data and Visualizations:
- The data is saved to an Excel file (top_50_cryptos.xlsx) that updates every 5 minutes.
- Visualizations are saved as PNG image files for easy sharing and inclusion in reports.
## 6. Generate PDF Report:
- A PDF report (Cryptocurrency_Analysis_Report.pdf) is generated that includes:
- A summary of the analysis.
- The visualizations created.
- To create the PDF:
- Run the script to automatically generate the report.
- Ensure the saved visualization files are in the same directory as the script.
## Output Files:
- Excel File: top_50_cryptos.xlsx (updates every 5 minutes).
## PNG Visualizations:
- top_5_crypto-currencies.png
- Distributions_Of_Crypto-Currency_Prices.png
- Highest_and_Lowest_24-Hour_Price_Change.png
- PDF Report: Cryptocurrency_Analysis_Report.pdf.
## Notes for Reviewers
- The live-updating Excel file may not work on Google Sheets due to API access limitations.
- Make sure to set up your local environment and install all dependencies before running the script.
