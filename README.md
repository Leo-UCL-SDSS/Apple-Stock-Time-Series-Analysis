# Apple Stock Time Series Analysis

An academic project analysing Apple (AAPL) stock returns and
volatility using ARIMA and GARCH models in R.

**Author:** Haofan (Leo) Liao  
**Institution:** University of California, Santa Barbara (UCSB)  
**Course:** PSTAT 174 — Time Series Analysis  
**Completed:** June 2026

## Project Overview

This project examines the statistical properties of Apple stock
prices and returns, with a focus on modelling return dynamics,
volatility clustering and short-term forecasts.

## Dataset

- Company: Apple Inc. (NASDAQ: AAPL)
- Period: January 2010 – June 2026
- Approximately 4,100 daily observations
- Source: Yahoo Finance

Adjusted closing prices were transformed into daily log returns.

## Methodology

### 1. Stationarity Testing
- Augmented Dickey-Fuller (ADF) test
- Comparison of price levels and log returns

### 2. ARIMA Modelling
- Box-Jenkins methodology
- Model selection and residual diagnostics
- ARIMA(0,0,1) model for daily returns

### 3. GARCH Modelling
- ARCH effect testing
- GARCH(1,1) conditional volatility model
- Analysis of volatility clustering and persistence

### 4. Forecasting
- Short-term return forecasts
- 12-step volatility forecasts

## Key Findings

- Apple stock prices were nonstationary, while daily log
  returns were stationary.
- ARIMA modelling indicated limited predictability in
  daily returns.
- GARCH(1,1) captured volatility clustering and persistence.
- Estimated volatility persistence was approximately 0.948.
- Volatility forecasts showed elevated short-term risk
  followed by gradual mean reversion.

## Limitations

Historical statistical relationships do not guarantee
future market performance.

ARIMA and GARCH models simplify complex market dynamics
and may not fully capture structural breaks, unexpected
events or nonlinear dependencies.

## Project Files

- `Pstat174-final.html` — Full analytical report, including
  model fitting, diagnostic results and visualisations.

## Technologies

R, Time Series Analysis, ARIMA, GARCH, ADF Testing.

## Author

**Haofan (Leo) Liao**

Developed at the University of California, Santa Barbara
during my 2025–2026 exchange year.

Home institution: University College London (UCL)  
BSc Social Sciences with Data Science
