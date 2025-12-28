# XRP Time Series Forecasting in Volatile Cryptocurrency Markets

## Applied AI Project
**An End-to-End Forecasting Framework Using LSTM, Attention Mechanism, and Improved Grey Wolf Optimization (iGWO)**

---

## Author
**Akram Hosseini-Nejad**  
MSc Artificial Intelligence  
Specialization: Applied AI, Time Series Forecasting, Decision Support Systems

---

## Problem Overview
Cryptocurrency markets are characterized by extreme volatility, non-linear dynamics, and sudden regime shifts driven by external events such as regulatory actions and market sentiment.

In such environments, the primary challenge is not achieving high point-forecast accuracy, but rather developing **stable and reliable predictive models** that can support informed decision-making under uncertainty.

Ripple (XRP) was selected as a case study due to its **event-driven price behavior** and sensitivity to legal and regulatory developments.

---

## Motivation
From an applied AI perspective, many existing forecasting approaches suffer from at least one of the following limitations:

- Sensitivity to abrupt market shocks  
- Instability across different market regimes  
- Manual and non-reproducible hyperparameter tuning  

This project addresses these challenges by focusing on **robustness, interpretability, and reproducibility**, rather than purely optimizing for accuracy.

---

## Methodology
A hybrid forecasting framework was designed, consisting of:

- **Long Short-Term Memory (LSTM)** networks for modeling temporal dependencies  
- **Attention mechanism** for dynamically emphasizing informative time periods  
- **Improved Grey Wolf Optimization (iGWO)** for automated and stable hyperparameter tuning  

Each component was selected based on its practical contribution to improving model reliability in volatile environments.

---

## End-to-End Pipeline
1. Collection of real-world financial time series data (daily XRP prices)  
2. Data cleaning, normalization, and sliding window generation  
3. Baseline model implementation and error analysis  
4. Integration of attention mechanism  
5. Hyperparameter optimization using iGWO  
6. Out-of-sample evaluation and performance comparison  

---

## Evaluation Strategy
Model performance is evaluated using:

- RMSE (sensitivity to large errors)  
- MAE (average prediction deviation)  
- Stability across unseen data segments  

---

## Practical Applications
- Risk-aware financial forecasting  
- Decision-support systems under uncertainty  
- Volatile time series modeling beyond cryptocurrency markets  

---

## Project Philosophy
- Every technical decision is explainable  
- Every visualization communicates a clear message  
- Every result supports a practical decision  
