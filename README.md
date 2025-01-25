# [portfoliomodels](https://VanekPetr.github.io/portfoliomodels/book)

[![PyPI version](https://badge.fury.io/py/portfoliomodels.svg)](https://badge.fury.io/py/portfoliomodels)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE.txt)
[![CI](https://github.com/VanekPetr/portfoliomodels/actions/workflows/ci.yml/badge.svg)](https://github.com/VanekPetr/portfoliomodels/actions/workflows/ci.yml)
[![Coverage Status](https://coveralls.io/repos/github/VanekPetr/portfoliomodels/badge.svg?branch=main)](https://coveralls.io/github/VanekPetr/portfoliomodels?branch=main)
[![Created with qCradle](https://img.shields.io/badge/Created%20with-qCradle-blue?style=flat-square)](https://github.com/tschm/package)

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/VanekPetr/portfoliomodels)

## Technologies and Models

This python package brings together various optimization models for asset allocation,
machine learning (ML) methodologies for feature selection, and algorithms for
scenario generation.

### Portfolio optimization models

1. Conditional Value at Risk (CVaR) model - [read more](https://docs.mosek.com/portfolio-cookbook/riskmeasures.html#conditional-value-at-risk)
2. Mean-Variance (Markowitz) model - [read more](https://docs.mosek.com/portfolio-cookbook/markowitz.html)

### ML models

1. Minimum Spanning Tree (MST) model - [read more](https://en.wikipedia.org/wiki/Minimum_spanning_tree)
2. Hierarchical Clustering (HCA) model - [read more](https://en.wikipedia.org/wiki/Hierarchical_clustering)

### Scenario generation algorithms

1. Monte Carlo scenario simulation - [read more](https://en.wikipedia.org/wiki/Monte_Carlo_method)
2. Bootstrap scenario simulation - [read more](https://en.wikipedia.org/wiki/Bootstrapping_(statistics))

To further enhance your knowledge on mathematical optimization in finance, we highly
recommend the [MOSEK Portfolio Optimization Cookbook](https://github.com/MOSEK/PortfolioOptimization).

## Getting Started

### **Set Up Environment**

```bash
make install
```

This installs/updates [uv](https://github.com/astral-sh/uv),
creates your virtual environment and installs dependencies.

For adding or removing packages:

```bash
uv add/remove requests  # for main dependencies
uv add/remove requests --dev  # for dev dependencies
```

### **Configure Pre-commit Hooks**

```bash
make fmt
```

Installs hooks to maintain code quality and formatting.

## Run test suite

```bash
make tests   # Run test suite
```

## Contributing

- Fork the repository
- Create your feature branch (git checkout -b feature/amazing-feature)
- Commit your changes (git commit -m 'Add some amazing feature')
- Push to the branch (git push origin feature/amazing-feature)
- Open a Pull Request
