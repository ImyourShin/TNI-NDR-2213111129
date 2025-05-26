# 📈 TradingLite - Advanced Stock Analysis Platform

## ✨ Key Features

### 📊 Real-Time Market Data

* Live stock prices and market data
* Multiple time intervals (1 minute to maximum available data)
* Volume analysis and trade statistics
* Customizable historical price data

### 📈 Advanced Technical Analysis

* **Interactive Charts**: Candlestick and Line charts with zoom and pan functionality
* **Technical Indicators**:

  * Customizable Moving Averages (SMA/EMA)
  * RSI (Relative Strength Index)
  * MACD (Moving Average Convergence Divergence)
  * Bollinger Bands

### 💡 Trading Recommendations

* Buy / Sell / Hold suggestions based on multiple indicators
* Support and Resistance level analysis

### 📋 Company and Market Insights

* Fundamental company information
* Business summaries and industry data
* Volatility and performance analysis

## 🚀 Installation and Usage

### 1. Clone the Repository from GitHub

```bash
# Clone repository
git clone https://github.com/YOUR_USERNAME/TradingLite.git

# Navigate to the project folder
cd TradingLite
```

### 2. Install Dependencies

```bash
# Create a virtual environment (recommended)
python -m venv tradingLite_env

# Activate the virtual environment
# For Windows:
tradingLite_env\Scripts\activate
# For macOS/Linux:
source tradingLite_env/bin/activate

# Install required packages
pip install -r requirements.txt
```

### 3. Run the Application

```bash
streamlit run app.py
```

The application will open in a browser at `http://localhost:8501`.

## 📦 Dependencies

```bash
pip install -r requirements.txt
```

## 📱 How to Use

### 1. Search for Stocks

* Enter a stock symbol (e.g., AAPL, GOOGL, TSLA) in the Stock Symbol field.
* The system will automatically validate the symbol.

### 2. Configure Analysis Settings

* Choose a time period for analysis (1 day to maximum available).
* Select data frequency (1 minute to monthly).
* Pick a chart type (Candlestick or Line Chart).

### 3. Use Technical Indicators

* Toggle Volume chart on/off.
* Select and customize Moving Averages.
* Enable RSI, MACD, and Bollinger Bands.
* Adjust the chart's height.

### 4. View Analysis Results

* **Chart Analysis Tab**: View charts and technical indicators.
* **Technical Indicators Tab**: See trading recommendations and advanced analysis.
* **Market Data Tab**: Access company data and market statistics.

### Enhanced Metrics Dashboard

* Live market dashboard with comprehensive data.
* Performance comparisons across multiple timeframes.
* Volume pattern analysis.
* Key technical levels (Support/Resistance).

### Advanced Statistical Analysis

* Volatility analysis
* Risk metrics (Beta, Sharpe ratio)
* Drawdown analysis
* Performance comparison

## 🛠️ Development and Customization

### Adding New Technical Indicators

1. Add the calculation function in `app.py`.
2. Add UI controls in the sidebar.
3. Integrate the indicator into the main chart.

### UI/UX Customization

* Modify CSS in `st.markdown()` sections.
* Adjust layout with `st.columns()` and `st.container()`.
* Add themes and color schemes.

## 📊 Data Sources

* **Yahoo Finance API** via the `yfinance` library
* Real-time and historical data
* Global stock market support
* Company information and financial metrics

## ⚠️ Limitations and Usage Notes

* Data from Yahoo Finance may have delays.
* Excessive usage may be limited by API restrictions.
* Trading recommendations are for reference only, not investment advice.
* Always conduct additional analysis before making investment decisions.

## 👨‍💻 Developer

**Teshin Bubpha**
TNI-NDR-2213111129

## 📄 License

This project is open source and intended for educational and development purposes.

## 🆘 Troubleshooting

### Common Issues

1. **ModuleNotFoundError**: Check that dependencies are installed.
2. **Data loading errors**: Verify your internet connection.
3. **Symbol not found**: Use valid stock symbols.

## Links

* **Website**: [TradingLite](https://tradinglite.streamlit.app/)
* **Presentation**: [TradingLite Presentation](https://gamma.app/docs/TradingLite-Advanced-Stock-Analysis-Platform-vlxr5x4tt2pes20)

💡 **Note**: This application is developed for educational and stock data analysis purposes. It is not intended as investment advice. Please exercise discretion when making investment decisions.
