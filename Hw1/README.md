# Assignment 1: Statistical Analysis

## Objective
Perform simple analysis to examine monthly and daily portfolio returns from the stock market, to assess the statistical properties of both monthly and weekly market returns over various portfolios. Including descriptive statistics and measures of dispersion and shape, while also analyzing seasonal effects and the reliability of return distributions. 

## Dataset
- Monthly data of portfolio returns from the combined NYSE/AMEX/Nasdaq

## Methods Used
- Scipy's stats library for skewness, kurtosis, and normality tests
- pandas and numpy for dataset manipulation and statistics calculation

## Results
Analysis emphasizes that investors should be aware that market returns are not normally distributed, meaning that traditional risk models may underestimate extreme risks like tail risk especially in smaller-cap portfolios, which we can see exhibit higher volatility.
Additionally, the “January Effect” presents a period of time where returns tend to be higher but more volatile; however, this anomaly should not be used as an informed investment decision.
