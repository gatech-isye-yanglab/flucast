# FluSight Forecasts 
Methodology for the CDC FluSight Forecast Competition: 2024–2025 Season

Contributors (Georgia Tech)
- Shihao Yang
- Candice Djorno
- Jiecheng Lu

## Overview

This repository contains the implementation of ensemble methods for influenza forecasting as part of the CDC FluSight competition. The methods utilize both probabilistic and point estimate forecasting models, integrating deep learning, machine learning and statistical techniques, incorporating Google Trends data.

## Methodology

### 1. Ensemble of Attention-based Time Series Probabilistic Forecasts
Ensemble of deep learning attention-based probabilistic prediction architecture with different core time-series predictors, including ARM, CATS, and ICTS.

- CATS (Construct Auxiliary Time Series): https://arxiv.org/pdf/2403.01673 \
Lu, J., Han, X., Sun, Y., & Yang, S. (2024). CATS: Enhancing Multivariate Time Series Forecasting by Constructing Auxiliary Time Series as Exogenous Variables. arXiv preprint arXiv:2403.01673.

- ARM (Multivariate temporal-contextual adaptive learning method): https://arxiv.org/pdf/2310.09488 \
Lu, J., Han, X., & Yang, S. (2023). ARM: Refining multivariate forecasting with adaptive temporal-contextual learning. arXiv preprint arXiv:2310.09488.

- ICTS (In-context Time Series Predictor): https://arxiv.org/pdf/2405.14982 \
Lu, J., Sun, Y., & Yang, S. (2024). In-context time series predictor. arXiv preprint arXiv:2405.14982.

### 2. Ensemble of Statistical and Machine Learning-based Time Series Point Forecasts
Ensemble of statistical and ML time series model predictions, including ARIMA, ARGO, ARGO2, and deep learning models.

- ARGO (AutoRegression with GOogle search data): https://www.pnas.org/doi/abs/10.1073/pnas.1515373112 \
Yang, S., Santillana, M., & Kou, S. C. (2015). Accurate estimation of influenza epidemics using Google search data via ARGO. Proceedings of the National Academy of Sciences, 112(47), 14473-14478.

- ARGO2 (2-step Augmented Regression with GOogle data): https://www.nature.com/articles/s41598-019-41559-6 \
Ning, S., Yang, S., & Kou, S. (2019). Accurate regional influenza epidemics tracking using Internet search data. Scientific reports, 9(1), 5238.

### 3. Google Trends Data 

- Statistically Preprocessed Google Trends Data: https://arxiv.org/pdf/2504.07032 \
Djorno, C., Santillana, M., & Yang, S. (2025). Restoring the Forecasting Power of Google Trends with Statistical Preprocessing. arXiv preprint arXiv:2504.07032.
