# sales-forecasting-baseline-vs-models
Monthly sales forecasting with strong baseline comparison
# Monthly Sales Forecasting: Baseline vs Statistical Models

## Overview
This project analyzes monthly sales forecasting using historical transactional data.
The main goal is to evaluate whether statistical time-series models can outperform a strong business baseline.

## Methodology
- Aggregation of transactional data into monthly sales
- Train/Test split for fair evaluation
- Definition of a Year-over-Year baseline
- Evaluation of SARIMA and Log-SARIMA models
- Comparison using MAE, RMSE, and MAPE

## Models Evaluated
- SARIMA
- Log-SARIMA
- Year-over-Year Baseline

## Results

| Model | MAE | RMSE | MAPE (%) |
|------|-----|------|----------|
| SARIMA | 8181 | 9179 | 72.7 |
| Log-SARIMA | 5635 | 6631 | 38.6 |
| **Baseline (YoY)** | **3747** | **4473** | **24.0** |

## Key Insights
- Annual seasonality dominates sales behavior
- Simple baselines can outperform complex models
- Model complexity without additional features does not guarantee better performance

## Conclusion
This project highlights the importance of strong baselines and data understanding over blind model complexity in real-world forecasting problems.

## Future Work
- Incorporate exogenous features such as promotions or product categories
- Extend forecasting to product-level or customer-level analysis
