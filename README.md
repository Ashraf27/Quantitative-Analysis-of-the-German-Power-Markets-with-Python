# Quantitative Analysis of the German Power Markets
### Day-ahead–intraday spreads: market structure, forecasting and execution controls

This notebook analyses the difference between German day-ahead prices and the later intraday reference index, ID-AEP. It explores historical patterns and tests whether forecasting models improve on simple benchmarks.

The dataset covers **1 September 2024–31 August 2026**, using DE-LU day-ahead prices and published ID-AEP values at 15-minute delivery resolution. Models are evaluated across twelve monthly test windows using data excluded from training.

### What this analysis covers

- How spread patterns changed after the introduction of 15-minute day-ahead prices.

- How wind, solar and demand forecast errors relate to spreads.

- Whether forecasting models outperform a zero-spread benchmark.

- How forecast accuracy and uncertainty vary across months and extreme-price events.

The analysis uses real historical market data. ID-AEP is calculated from trades rather than an executable quote, so its difference from day-ahead prices is treated as a spread, not as trading profit.
