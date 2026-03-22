# APEX Trading Platform - Interactive Showcase

[![GitHub Pages](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-00e5ff?style=for-the-badge&logo=github)](https://axumweyane.github.io/apex-showcase/)
[![Python](https://img.shields.io/badge/Python-3.12-3776ab?style=flat-square&logo=python&logoColor=white)](https://python.org)
[![Tests](https://img.shields.io/badge/Tests-970%20passing-76ff03?style=flat-square)](https://axumweyane.github.io/apex-showcase/system.html)
[![Models](https://img.shields.io/badge/ML%20Models-10-e040fb?style=flat-square)](https://axumweyane.github.io/apex-showcase/guide.html)
[![Strategies](https://img.shields.io/badge/Strategies-12-ffd740?style=flat-square)](https://axumweyane.github.io/apex-showcase/guide.html)

Interactive documentation for the **APEX multi-strategy algorithmic trading platform** — a production-grade system with 10 ML models, 12 trading strategies, 5 safety guardrails, and full microservices infrastructure.

## Live Demo

**https://axumweyane.github.io/apex-showcase/**

## Screenshots

### Landing Page with Backtest Performance
![Landing Page](screenshots/landing-hero.png)
![Performance Metrics](screenshots/landing-performance.png)

### Animated System Tour
![10 ML Models](screenshots/system-models.png)
![12 Strategy Sliders](screenshots/system-strategies.png)
![Safety Guardrails](screenshots/system-guardrails.png)

## Pages

| Page | Description |
|------|-------------|
| [Landing Page](https://axumweyane.github.io/apex-showcase/) | Platform overview with animated metrics, backtest performance, tech stack |
| [Animated System Tour](https://axumweyane.github.io/apex-showcase/system.html) | 10-scene interactive journey through the entire APEX pipeline |
| [Visual Architecture Guide](https://axumweyane.github.io/apex-showcase/guide.html) | Printable reference with tables, diagrams, and the 17-step pipeline |
| [One-Page Summary](https://axumweyane.github.io/apex-showcase/summary.html) | Print-to-PDF executive summary for investors and employers |

## Features

### Animated System Tour
- 10 animated scenes: Data Flow, Models, Ensemble, Strategies, Guardrails, Testing, Execution, Database, Monitoring, Daily Cycle
- Clickable model cards with expandable details (purpose, data, accuracy)
- Toggle switches on safety guardrails showing failure scenarios
- Draggable strategy weight sliders with live pie chart
- Full-text search with keyword highlighting
- Live data panel connecting to the paper trader API
- Play/Pause, speed control, scene selector, confetti finale

### Platform Metrics
- **10 ML models** across 4 asset classes (stocks, forex, options, cross-asset)
- **12 trading strategies** with regime-adaptive Bayesian ensemble
- **5 safety guardrails** for automated pre-trade risk checks
- **970 tests** across 30 test modules
- **179 Python files** with full production infrastructure
- **5 microservices** coordinated via Kafka with DLQ

## Tech Stack

Python 3.12, PyTorch, FastAPI, PostgreSQL, TimescaleDB, Redis, Kafka, Docker, Prometheus, Grafana, MLflow, Alpaca API

## Source Code

The main APEX codebase is at [github.com/axumweyane/lastcode10](https://github.com/axumweyane/lastcode10).

## License

This showcase is for demonstration purposes.
