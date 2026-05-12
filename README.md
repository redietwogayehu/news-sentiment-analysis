 News Sentiment Analysis & Stock Market Correlation

A Week 1 AI Mastery project focused on analyzing financial news sentiment and its relationship with stock market behavior using exploratory data analysis, technical indicators, and statistical correlation analysis.

 Project Objective

This project builds an end-to-end data pipeline to:

Analyze financial news headlines to extract patterns and sentiment signals
Explore relationships between news activity and stock price movements
Apply technical indicators for quantitative financial analysis
Evaluate whether news sentiment can be used as a signal for market behavior
Develop foundational insights for sentiment-based trading strategies
 Project Structure
Task 1 — Exploratory Data Analysis (EDA)
Task 2 — Technical Stock Analysis
Task 3 — Sentiment & Correlation Analysis
  Task 1 — Exploratory Data Analysis (EDA)

Financial news data was analyzed to understand publishing behavior and textual patterns.

Key Work Completed
Data loading and cleaning of financial news dataset
Date parsing and time-series preparation
Headline length distribution analysis
Publisher frequency analysis
Daily news volume trend analysis
NLP-based keyword extraction from headlines
Key Insights
Financial news is highly concentrated among a small number of publishers
News volume shows strong time-based variation
Keywords reflect earnings, trading activity, and market updates
  Task 2 — Stock Market Analysis

Historical stock data was analyzed for the following companies:

AAPL
AMZN
GOOG
META
NVDA
Technical Indicators Implemented
Simple Moving Average (SMA)
Exponential Moving Average (EMA)
Relative Strength Index (RSI)
Moving Average Convergence Divergence (MACD)
TA-Lib integration for validation of selected indicators
Enhancements
Missing value handling before indicator computation
Chronological sorting of time-series data
Reusable indicator pipeline across multiple stocks
Visualization of trend and momentum signals
 Task 3 — Sentiment & Correlation Analysis

This stage evaluates the relationship between financial news sentiment and stock market movements.

Methodology
Applied sentiment analysis using VADER for financial headlines
Aggregated daily sentiment scores per trading day
Aligned news dates with stock market trading dates
Calculated daily stock returns using percentage change
Performed Pearson correlation analysis between sentiment and returns
Visualized relationships using scatter plots and category-based comparisons
Key Outputs
Daily sentiment score time series
Stock return calculations
Sentiment vs return correlation analysis
Scatter plot visualization of relationship strength
Sentiment classification (Positive / Neutral / Negative)
  Tools & Libraries
Python
Pandas
NumPy
Matplotlib
Seaborn
TA-Lib
VADER Sentiment Analysis
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
   Key Highlights
End-to-end financial news sentiment analysis pipeline
Integration of NLP and technical stock indicators
Statistical correlation between sentiment and market returns
Reusable multi-stock analytical framework
Clean, modular structure with reproducible workflow
