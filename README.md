# Genetic Algorithm Portfolio Optimization

## Author

Matheus Nogueira  
📧 Contact: matnogueira@gmail.com

## About this Repository

This repository contains the final project developed for the course **ELE2395 – Evolutionary Computing** at PUC-Rio, completed in 2021.

The project implements a **portfolio optimization framework using Genetic Algorithms**, where the optimization is driven by forecasted stock returns obtained through two different models:
- A **Naïve Predictor** based on the Random Walk assumption.
- The **Facebook Prophet** time series forecasting model.

Both predictors were used to estimate one-week-ahead returns for 20 assets from the Brazilian stock exchange (BOVESPA), including a risk-free asset (SELIC). These forecasts were then passed to the genetic algorithm, which optimizes the portfolio allocation subject to realistic constraints such as maximum volatility and no short selling.

The models were trained on **10 years of historical weekly return data** and tested on a rolling-window basis over a **2-year out-of-sample period**. The results show that using Prophet-based forecasts led to significantly superior cumulative returns compared to both the benchmark (BOVESPA Index) and the naïve model.

The full paper describing the methodology, experiments, and results is available in this repository.

## Academic Integrity Notice

This repository is intended strictly for **educational and archival purposes**. Any use of its contents for assignments in the course *ELE2395 – Evolutionary Computing* or similar academic contexts is strictly prohibited. **Plagiarism or derivative submissions will be treated as academic misconduct**.

The project was made public **after course completion** and does not aim to serve as a financial recommendation or production-grade investment tool.
