Real-Time Stock Analyzer and Predictor

It is an end-to-end system for real-time stock market analysis and forecasting using Machine Learning and a decoupled data pipeline.

My Role: Data Pipeline & Backend Developer
In this project, I was responsible for the core data infrastructure, ensuring that the system could handle live market data efficiently.

Key Contributions:
* Real-Time Data Ingestion: Built a background process to fetch live OHLCV data from financial APIs at 60-second intervals.
* ETL Pipeline: Engineered the logic to clean raw data and compute technical indicators like RSI, MACD, and Moving Averages.
* High-Performance Storage: Implemented DuckDB with Parquet for fast, low-latency data storage and retrieval.
* System Reliability: Designed error-handling to manage API rate limits and ensure continuous data flow.

Tech Stack
* Language: Python
* Data Handling: Pandas, DuckDB, Parquet
* Machine Learning: Random Forest, Gradient Boosting, Logistic Regression
* Dashboard: Streamlit
