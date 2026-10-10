# Equity Return Prediction

Equity signals and portfolio research for a Master's project in Applied Investments at HEC Lausanne, University of Lausanne.

## Objective

Investigate signal-based US equity strategies and evaluate factor-adjusted alpha.

## Data

Data sources presented in the course, accessed through **WRDS (Wharton Research Data Services)**:

- **CRSP (Center for Research in Security Prices):** historical US stock prices, returns, and trading volumes for NYSE, AMEX, and NASDAQ securities.
- **Compustat:** company financial statements and annual and quarterly accounting fundamentals.

Data files remain local and are excluded from version control.

## Research principles

Respect historical information availability and avoid look-ahead bias, information leakage, survivorship bias, and test-set optimization.

## Repository structure

```text
data/       Local datasets (excluded from Git)
docs/       Project scope and documentation
src/        Future implementation
results/    Local generated outputs (excluded from Git)
```

See [Project scope](docs/PROJECT_SCOPE.md) for confirmed requirements and decisions still pending.
