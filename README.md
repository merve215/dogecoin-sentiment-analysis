# 🚀 Dogecoin Sentiment Analysis & Return Prediction

This project explores the relationship between Reddit sentiment and Dogecoin returns, analyzing whether public sentiment from different subreddits can help explain or predict Dogecoin price movements. The study includes word cloud visualizations, sentiment scoring using NLP, and regression analysis using historical return data.

## 📊 Project Overview

We collected Reddit posts from Dogecoin-related and broader crypto subreddits, performed sentiment analysis using **FinBERT**, and combined this with historical price data to:

- Visualize sentiment trends using word clouds.
- Calculate Dogecoin returns.
- Compare sentiment scores with returns.
- Run a regression analysis to explore potential predictors of Dogecoin price movements.

## 🧠 Methods

- **Data Source**: Reddit posts from Dogecoin and cryptocurrency subreddits (2021), price data from Yahoo Finance.
- **Sentiment Analysis**: FinBERT and custom sentiment scoring.
- **Regression**:
Doge Return_t = β₀ + β₁ Sentiment Scoreᵢ + X_t β + ε_t

Where:
- `Sentiment Scoreᵢ`: Score from either Doge or Crypto subreddit.
- `X_t`: Includes lagged returns, Bitcoin and S&P returns, and lagged sentiment.
