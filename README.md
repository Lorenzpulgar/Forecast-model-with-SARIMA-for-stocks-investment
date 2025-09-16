# 📈 SARIMA Stock Forecasting Model for Investment Analysis

A comprehensive time series forecasting model using SARIMA (Seasonal AutoRegressive Integrated Moving Average) to predict NASDAQ index trends for strategic investment decisions in technology stocks.

## 🎯 Project Overview

This project implements advanced time series forecasting techniques to analyze and predict NASDAQ index movements, providing valuable insights for ETF (Exchange-Traded Fund) investment strategies. By leveraging historical data from 1990 to 2022, the model identifies cyclical patterns and trends in the technology sector's performance.

The SARIMA model excels at capturing both trend and seasonal components in financial time series data, making it particularly suitable for stock market analysis where patterns repeat over different time horizons.

## ✨ Features

- **Historical Data Analysis**: Comprehensive analysis of NASDAQ index data spanning over 30 years (1990-2022)
- **SARIMA Model Implementation**: Advanced seasonal time series forecasting with optimal parameter selection
- **Seasonal Decomposition**: Breaks down time series into trend, seasonal, and residual components
- **Data Visualization**: Interactive plots showing historical trends, forecasts, and confidence intervals
- **Model Validation**: Train/test split validation with performance metrics
- **Investment Insights**: Actionable forecasts for ETF investment strategies
- **Automated Data Pipeline**: Real-time data fetching from Yahoo Finance API

## 🛠️ Technologies Used

### Core Libraries
- **Python 3.7+**: Primary programming language
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computing and array operations
- **Matplotlib**: Data visualization and plotting

### Financial Data & Analysis
- **yfinance**: Yahoo Finance API for real-time and historical stock data
- **pandas_datareader**: Additional financial data sources

### Time Series & Machine Learning
- **statsmodels**: SARIMA model implementation and statistical analysis
- **scikit-learn**: Data preprocessing (MinMaxScaler, LabelEncoder)

### Development Environment
- **Jupyter Notebook**: Interactive development and analysis
- **Google Colab**: Cloud-based execution environment

## 📊 Model Specifications

- **Target Index**: NASDAQ Composite (^IXIC)
- **Data Period**: February 8, 1990 - November 11, 2022
- **Model Type**: SARIMA(1,1,1)(1,1,0)[12]
- **Seasonal Period**: 12 months
- **Validation Method**: Time series split (last 200 observations for testing)

## 🚀 Getting Started

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Lorenzpulgar/Forecast-model-with-SARIMA-for-stocks-investment.git
cd Forecast-model-with-SARIMA-for-stocks-investment
```

2. Install required dependencies:
```bash
pip install yfinance pandas_datareader pandas numpy matplotlib statsmodels scikit-learn
```

### Usage

1. Open the Jupyter notebook:
```bash
jupyter notebook SARIMA_for_ETL.ipynb
```

2. Run all cells to:
   - Fetch historical NASDAQ data
   - Perform exploratory data analysis
   - Apply seasonal decomposition
   - Train the SARIMA model
   - Generate forecasts with confidence intervals
   - Validate model performance

## 📈 Results

The SARIMA model successfully captures:
- **Long-term trends** in technology sector growth
- **Seasonal patterns** in market behavior
- **Cyclical components** related to economic cycles
- **Forecast accuracy** with statistical confidence intervals

Key performance insights:
- Effective trend identification for long-term investment strategies
- Seasonal pattern recognition for timing market entries/exits
- Risk assessment through confidence interval analysis
- Validation against historical test data

## 🎓 Academic Context

This project was developed as the final capstone project for the Machine Learning Diploma program at Universidad EAFIT, demonstrating the practical application of time series analysis in financial markets.

## 👥 Contributors

- **Laura Maria Martinez** - Data Analysis & Model Development
- **Lorenz Pulgar Velásquez** - Project Lead & SARIMA Implementation
- **Lesly Pamela Lopez** - Validation & Documentation

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

### Development Guidelines
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Contact

For questions or collaboration opportunities:
- **Lorenz Pulgar Velásquez** - Project Maintainer
- **Institution**: Universidad EAFIT
- **Program**: Machine Learning Diploma

## 🙏 Acknowledgments

- Universidad EAFIT Machine Learning Diploma Program
- Yahoo Finance for providing comprehensive financial data APIs
- The open-source community for developing robust time series analysis tools

---

*This project demonstrates the power of SARIMA models in financial forecasting and serves as a foundation for AI-driven investment strategies in the technology sector.*
