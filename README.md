# Horseshoe_regression
Horseshoe regression that minimizes Stein's expected loss, with simulations and comparisons to popular shrinkage regressions (ridge, lasso, adaptive lasso, principal component regression, MCP and SCAD.)

# Dependency
Runs in R. Requires libraries `MASS`, `glmnet`, `parcor`, `sparsenet`, and `ncvreg` for random data generation and competing methods.

The horseshoe regression function that minimies Stein's expected loss is based on numerical integration and the `optimize` function in base R, and does not require libraries.
