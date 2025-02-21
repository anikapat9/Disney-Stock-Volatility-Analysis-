# Disney Stock Volatility Analysis

This project analyzes the stock price volatility of Disney (ticker: `DIS`) using historical data from 2022 to 2023. The analysis includes feature engineering, rolling volatility computation, and machine learning-based predictions for stock price direction.

## Features
- **Data Acquisition**: Fetches historical stock data using `yfinance`.
- **Volatility Analysis**: Computes daily returns, rolling volatility, and moving averages.
- **Machine Learning**: Implements logistic regression with SMOTE for class balancing.
- **Visualization**: Uses `matplotlib` and `seaborn` for plotting trends and insights.

## Tools & Libraries
- Python 3.13
- Jupyter Notebook
- Libraries:
  - `yfinance`
  - `scikit-learn`
  - `imbalanced-learn`
  - `matplotlib`
  - `seaborn`

## How to Run
1. Clone the repository
2. Install dependencies:
pip install -r requirements.txt
3. Open the notebook:
jupyter notebook DisneyVolatility.ipynb
4. Run the cells sequentially.

## Results
- **Volatility**: Daily volatility of Disney stock is calculated as ~2.34%.
- **Rolling Volatility**: 30-day rolling standard deviation highlights trends over time.
- **Model Performance**: Logistic regression achieved a balanced F1-score of ~46% after addressing class imbalance.