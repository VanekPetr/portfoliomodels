# [portfoliomodels](https://VanekPetr.github.io/portfoliomodels/book)

[![PyPI version](https://badge.fury.io/py/portfoliomodels.svg)](https://badge.fury.io/py/portfoliomodels)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE.txt)
[![CI](https://github.com/VanekPetr/portfoliomodels/actions/workflows/ci.yml/badge.svg)](https://github.com/VanekPetr/portfoliomodels/actions/workflows/ci.yml)
[![Coverage Status](https://coveralls.io/repos/github/VanekPetr/portfoliomodels/badge.svg?branch=main)](https://coveralls.io/github/VanekPetr/portfoliomodels?branch=main)
[![Created with qCradle](https://img.shields.io/badge/Created%20with-qCradle-blue?style=flat-square)](https://github.com/tschm/package)

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/VanekPetr/portfoliomodels)

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

### **Update Project Info**

- Edit `pyproject.toml` to update authors and email addresses
- Configure GitHub Pages (branch: gh-pages) in repository settings

## Development Commands

```bash
make tests   # Run test suite
make marimo  # Start Marimo notebooks
```

## Contributing

- Fork the repository
- Create your feature branch (git checkout -b feature/amazing-feature)
- Commit your changes (git commit -m 'Add some amazing feature')
- Push to the branch (git push origin feature/amazing-feature)
- Open a Pull Request
