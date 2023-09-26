# Sentiment-Driven Portfolio Optimization Using Neural Stochastic Differential Equations: A Case Study During the 2008 Recession

## Introduction
This GitHub repository houses an innovative and highly specialized stock portfolio optimization strategy, combining neural stochastic differential equations, sentiment analysis, and financial metrics. The project's focus is on four major tech stocks—Amazon, Apple, Microsoft, and NVIDIA—during the critical period of the 2008 financial crisis.

## Novel Features

### Fine-Tuned Sentiment Analysis
In a radical departure from traditional methods, the sentiment scores for the stocks are generated using a large language model that has been fine-tuned with annotated financial articles. This bestows the model with an extraordinary level of accuracy in capturing sentiment, tailored specifically for financial applications, unlike common NLP techniques.

### Neural Stochastic Differential Equations (SDEs)
This strategy is pioneering in its use of Neural Stochastic Differential Equations for portfolio optimization. Neural SDEs provide a mathematical framework that leverages machine learning to approximate complex stochastic processes. This enhances the model's predictive power, allowing it to adapt swiftly to market conditions, thereby optimizing portfolio returns.

## In-Depth Overview

1. **Data Gathering and Preprocessing**: 
    - **Stock Price Data**: Historical stock prices for Amazon, Apple, Microsoft, and NVIDIA are collected.
    - **Sentiment Data**: Sentiment scores are generated using a fine-tuned large language model.

2. **Feature Engineering**: 
    - **Financial Metrics**: Includes volatility, momentum, and mean reversion, among others.
    - **Sentiment Scores**: Mined using the specialized language model.

3. **Model Architecture**: 
    - A neural network trained to mimic a stochastic differential equation (SDE) is used.
    - The SDE models the stock prices as a function of various features, including sentiment.

4. **Portfolio Optimization**:
    - The neural SDE outputs are fed into an optimization algorithm.
    - Real-world constraints like slippage are considered.
    - The portfolio is rebalanced based on these optimized weightings.

5. **Performance Metrics**:
    - The portfolio's performance is measured using metrics like Annualized Return, Sharpe Ratio, and Max Drawdown.

## Tech Stack
- Python 3.x
- PyTorch for Neural SDEs
- Pandas for data manipulation
- NumPy for numerical computations

## Contributions
- Contributions are welcome! Feel free to submit pull requests or create issues.

## Disclaimer
This codebase is for educational and research purposes only. Past performance is not indicative of future returns. Use at your own discretion.
