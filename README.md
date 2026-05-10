News Sentiment Analysis & Stock Market Correlation

A Week 1 AI Mastery project focused on analyzing financial news sentiment and its relationship with stock market behavior using exploratory data analysis and technical indicators.

 Project Objective

This project builds a data-driven pipeline to:

Analyze financial news headlines for patterns and trends
Explore relationships between news activity and stock price movements
Apply technical indicators for quantitative financial analysis
Prepare foundational insights for sentiment-based market prediction


Task 1 — Exploratory Data Analysis (EDA)

Financial news data was analyzed to extract patterns and insights.

Key Work Completed:
Data loading and cleaning of financial news dataset
Date parsing and time-series preparation
Headline length distribution analysis
Publisher frequency analysis
Daily news volume trend analysis
NLP-based keyword extraction from headlines
Key Insights:
Financial news is highly concentrated among a small number of publishers
News volume shows strong time-based variation
Common keywords reflect market activity and short-term trading focus
 Task 2 — Stock Market Analysis

Historical stock data was analyzed for the following companies:

AAPL
AMZN
GOOG
META
NVDA
Technical Indicators Implemented:
Simple Moving Average (SMA)
Exponential Moving Average (EMA)
Relative Strength Index (RSI)
Moving Average Convergence Divergence (MACD)
TA-Lib integration (selected indicator enhancement)
Enhancements:
Missing value handling before indicator computation
Structured indicator pipeline for reuse across stocks
Visualization of trend and momentum signals
🛠️ Tools & Libraries
Python
Pandas
NumPy
Matplotlib
Seaborn
TA-Lib
Jupyter Notebook

 How to Run
# Clone repository
git clone https://github.com/redietwogayehu/news-sentiment-analysis.git

# Navigate into project
cd news-sentiment-analysis

# Create virtual environment
python -m venv venv
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Launch notebooks
jupyter notebook

# Key Highlights
 
End-to-end exploratory data analysis on financial news
Technical indicator implementation for stock market analysis
Reusable structure for multi-stock analysis workflow
Clean CI/CD setup and reproducible environment

# Future Improvements
Sentiment scoring using NLP models (VADER / FinBERT)
Correlation analysis between sentiment and stock returns
Predictive modeling for short-term price movement
Dashboard visualization (Streamlit / Power BI)