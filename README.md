# Predicting Stock Analytics for African Markets
# Overview
This project seeks to develop a predictive model that forecasts stock price direction and identifies correlated trends to support informed investment strategies.

## Problem Statement
- Predictive stock modeling has become a cornerstone of investment strategy in Western markets, yet African markets continue to face a gap in accessible, data-driven forecasting tools. 
- This project addresses that gap by developing a model that analyzes market data to identify correlated stocks and predict whether prices will rise or fall. By transforming complex financial information into clear, actionable insights, the model empowers investors to make smarter, evidence-based decisions

## Technical Approach
- Use **time series analysis** to track stock values and identify performance patterns.
- Use **statistical correlation methods** to cluster stocks that move together, revealing interdependencies and co-movement trends.

## Dataset
- For this project, we scraped data from [TradingView](https://www.tradingview.com/) using TradingViewAPI.
- Supplementary data was then fetched manually from [Trading Economics](https://tradingeconomics.com/kenya/indicators)

## Tech Stack
- **Python**: Pandas, Scikit-learn, NumPy, Matplotlib, Seaborn.
- **Model Techniques**: Logistic Regression, Random Forest Classifier, XGBoost 
- **Model Deployment**: Streamlit
- **IDE/Notebook**: Jupyter Notebook, Visual Studio Code

## Conclusion
- The analysis showed clear and consistent patterns in how different stocks move over time, with many companies in the same sector displaying similar price behaviors. 
- Market performance varies notably across industries, with some sectors showing stronger growth and trading activity than others. 
- Historical data revealed that stock prices tend to follow identifiable trends rather than random fluctuations, indicating that past performance can provide meaningful insights into future movements.

## Recommendations
- Investors should diversify their portfolios by combining stocks with lower correlations to reduce risk and improve long-term returns.
- Pay close attention to sector trends, as companies within the same industry often react similarly to economic and market events.
- Continuously track price patterns and correlations, since market relationships evolve over time with changing economic conditions.
- Encourage wider adoption of data-driven decision-making tools in emerging markets to strengthen investor confidence and market transparency.
- Future improvements could include real-time data integration to provide more responsive insights and enhance forecasting accuracy.
