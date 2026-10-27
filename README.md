# 📈 Stock Market Analysis Using Python

## 📌 Project Overview

This project focuses on Exploratory Data Analysis (EDA) of historical stock market data from 10 companies across two sectors: Information Technology (IT) and Banking.

The project explores stock price movements, trading volumes, daily price fluctuations, monthly trends, quarterly trends, and correlations using Python libraries and data visualizations.

## 🎯 Project Objectives

- Analyze historical stock price movements.
- Compare IT and Banking sector trends.
- Examine trading volumes across companies.
- Identify daily price fluctuations and volatility patterns.
- Analyze monthly and quarterly price trends.
- Explore correlations between numerical variables.
- Communicate findings through charts and observations.

## 🏢 Companies Analyzed

### Information Technology (IT)

- Infosys — `INFY.NS`
- Tata Consultancy Services — `TCS.NS`
- HCL Technologies — `HCLTECH.NS`
- Wipro — `WIPRO.NS`
- Tech Mahindra — `TECHM.NS`

### Banking

- HDFC Bank — `HDFCBANK.NS`
- ICICI Bank — `ICICIBANK.NS`
- State Bank of India — `SBIN.NS`
- Kotak Mahindra Bank — `KOTAKBANK.NS`
- Axis Bank — `AXISBANK.NS`

## 🛠️ Tools and Technologies

- **Python** — Data analysis and programming
- **Pandas** — Data manipulation and analysis
- **NumPy** — Numerical operations and feature engineering
- **Matplotlib** — Data visualization
- **Seaborn** — Statistical visualizations
- **Requests** — Retrieving stock market data through an API
- **Yahoo Finance Chart API** — Historical stock market data source
- **Google Colab / Jupyter Notebook** — Development environment

## 📂 Dataset Description

The project retrieves approximately one year of daily historical stock market data for the selected companies.

The original dataset includes:

| Column | Description |
|---|---|
| `ticker` | Stock symbol |
| `date` | Trading date |
| `open` | Opening price |
| `high` | Highest price during the trading day |
| `low` | Lowest price during the trading day |
| `close` | Closing price |
| `volume` | Number of shares traded |

The notebook's recorded output contains 2,490 rows and 7 original columns before feature engineering. The dataset may change when the API is queried again.

## 🔄 Project Workflow

1. **Data Collection:** Retrieved historical stock market data using the Yahoo Finance Chart API.
2. **Data Cleaning:** Checked data types, missing values, and duplicate records.
3. **Outlier Exploration:** Used box plots to examine price and trading-volume distributions.
4. **Feature Engineering:** Created additional columns to support analysis.
5. **Exploratory Data Analysis:** Compared price movements, trading volumes, sectors, and monthly trends.
6. **Data Visualization:** Created charts using Matplotlib and Seaborn.
7. **Interpretation:** Summarized findings, conclusions, and limitations.

## ⚙️ Feature Engineering

The following features were created in the notebook:

- `day` — Day of the week
- `month` — Month of the trading date
- `year` — Year of the trading date
- `sector` — IT or Banking classification
- `daily_change` — Difference between closing and opening prices
- `pct_change` — Percentage change calculated from consecutive closing-price rows
- `daily_range` — Difference between the day's high and low prices
- `return_range_ratio` — Daily price range divided by the closing price
- `quarter` — Calendar quarter
- `change_trend` — Positive or negative daily price change

## 📊 Key Analysis Areas

The notebook explores 19 analysis questions, including:

- Total trading volume by sector
- Trading volume by company and sector
- Daily price changes across sectors
- Closing-price trends by company
- Average high prices by year and sector
- Opening-price trends
- Monthly percentage-change patterns
- Correlation between numerical variables
- Low-price trends across sectors
- Daily price ranges by company
- Return range ratios by company
- Quarterly comparisons of opening, closing, high, and low prices
- Positive and negative daily price changes by company and sector

## 💡 Key Findings

- Banking companies recorded a higher combined trading volume than IT companies during the analyzed period.
- Several IT stocks showed greater price fluctuations in the notebook's visualizations.
- Price movements and trading activity varied across companies and months.
- Monthly and quarterly visualizations helped compare price patterns across the two sectors.
- Correlation analysis was used to explore relationships between numerical variables.

These findings describe the historical data analyzed and do not predict future stock performance.

## 📝 Conclusions

The analysis highlights differences in trading activity and price movements between the selected IT and Banking companies.

Price-range measures and visualizations help explore historical volatility. However, price volatility and the return-range ratio alone do not establish investment profitability or future returns.

## ⚠️ Limitations of the Analysis

- The analysis covers a limited historical period.
- Only 10 companies from two sectors were included.
- Market conditions, economic events, and company-specific factors were not fully investigated.
- Higher price volatility does not necessarily mean higher returns.
- Results depend on the data retrieved from the external API.
- The findings are based on exploratory data analysis and should not be considered investment advice.

## 🚀 How to Run the Project

1. Clone or download this GitHub repository.
2. Open the notebook in Google Colab or Jupyter Notebook.
3. Install the required libraries if they are not already available:

   ```bash
   pip install numpy pandas matplotlib seaborn requests beautifulsoup4
   ```

4. Run the notebook cells in sequence.
5. Ensure an internet connection is available for retrieving data from the Yahoo Finance Chart API.

## 📚 Learning Outcomes

Through this project, I practiced:

- API-based data collection
- Data cleaning and preprocessing
- Feature engineering with Pandas and NumPy
- Exploratory data analysis
- Data visualization
- Correlation analysis
- Comparing groups and identifying patterns
- Presenting analytical findings and limitations

## 👩‍💻 Author

**Lalitha Mekala**

GitHub: [lalitha28-mekala](https://github.com/lalitha28-mekala)

## ⚖️ Disclaimer

This project is for educational and analytical purposes only. The analysis is based on historical data and is not financial or investment advice.

