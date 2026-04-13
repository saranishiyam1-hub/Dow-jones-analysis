# Dow-jones-analysis
Machine learning-based financial forecasting and risk analysis using Dow Jones stock data. The study combines statistical modeling techniques with financial theory to better understand both predictive accuracy and market risk behavior.

This project analyzes weekly stock performance for companies in the Dow Jones Industrial Average to evaluate the effectiveness of machine learning models in predicting stock returns. The study combines statistical modeling techniques with financial theory to better understand both predictive accuracy and market risk behavior.

Objective
The goal of this project was to:
  Predict weekly stock returns using historical financial data
  Compare the performance of multiple machine learning models
  Evaluate how well models capture market risk during periods of volatility
  Apply financial theory (CAPM) to analyze systematic risk
Tools & Technologies
  R (data analysis & modeling)
  Machine Learning Models:
    Linear Regression
    Support Vector Regression (SVR)
    Decision Trees
  Statistical Metrics: RMSE (Root Mean Squared Error)
  Financial Model: Capital Asset Pricing Model (CAPM)
Dataset
  700+ observations across 30 Dow Jones companies
  Weekly stock data including price changes, trading volume, and returns
  Data split into training (Q1) and testing (Q2) sets
Key Steps
  Cleaned and prepared financial data (handled missing values, converted formats)
  Engineered features including lagged price changes
  Built and compared predictive models (Linear Regression, SVR, Decision Trees)
  Evaluated model performance using RMSE
  Applied CAPM to calculate beta and assess systematic risk
  Analyzed model performance during high-volatility market events
Results & Insights
  Linear Regression showed weaker predictive performance (higher RMSE ~6.76)
  SVR and Decision Tree models significantly improved accuracy (RMSE ~2.91)
  Nonlinear models better captured patterns in stock returns
  Models struggled during “black swan” events (e.g., May 2011 market crash)
  Defensive stocks exhibited unexpected volatility, highlighting limitations of traditional risk assumptions
Key Takeaways
  Machine learning models improve prediction accuracy but are still vulnerable to market anomalies
  Financial forecasting must account for both systematic and unsystematic risk
  Combining statistical models with financial theory provides more meaningful insights
  Real-world financial data presents challenges that require both technical and analytical judgment
