# Horseshoe_regression
Horseshoe regression that minimizes Stein's expected loss, with simulations and comparisons to popular shrinkage regressions (ridge, lasso, adaptive lasso, principal component regression, MCP and SCAD.)

Expression for Stein's expected loss in horseshoe regression and further simulation results can be seen in Bhadra et al. (2019)

# Dependency
Runs in R. Requires libraries `MASS`, `glmnet`, `parcor`, `sparsenet`, and `ncvreg` for random data generation and competing methods.

The horseshoe regression function that minimies Stein's expected loss is based on numerical integration and the `optimize` function in base R, and does not require libraries.

Bhadra, Anindya, et al. "Prediction Risk for the Horseshoe Regression." Journal of Machine Learning Research 20.78 (2019): 1-39.
