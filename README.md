# Tesla-Stock-Movement-Prediction
Part of the GovTech Girls in Tech Mentorship Programme

Project Goal:
To predict Tesla’s daily and weekly stock price movements (up/down) using machine learning and historical data.

Data & Tools:
Data: Yahoo Finance (TSLA stock, 2022–present)
Tools: Python, Pandas, NumPy, yFinance, XGBoost, Scikit-learn, Matplotlib

Methodology:
Downloaded historical Tesla price data using yfinance
Engineered 19 technical indicators (e.g., RSI, MACD, Bollinger Width, Moving Averages)
Defined daily and weekly “up/down” targets
Scaled features with StandardScaler
Tuned XGBoost model using GridSearchCV
Evaluated accuracy and confusion matrices for both models

Results:
Daily Model Accuracy: ~52%
Weekly Model Accuracy: ~59%

Future Work:
Add sentiment analysis from news headlines
Build an interactive Streamlit dashboard
Backtest predictions with trading simulations

