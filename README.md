# Aayush Parashar

I build quantitative research systems at the intersection of market
microstructure, causal inference, structural econometrics, and machine-learning
infrastructure. The projects below are small enough to audit end to end and
include automated tests, continuous integration, and explicit methodological
limits.

## Selected projects

| Project | Focus | Methods |
| --- | --- | --- |
| [Liquidity Arbitrage Engine](https://github.com/meowcat234of-a11y/liquidity-arb-engine) | Event-driven market simulation | Price-time priority, Avellaneda–Stoikov quoting, OU signals, Hawkes arrivals |
| [Algorithmic Auction Dynamics](https://github.com/meowcat234of-a11y/algorithmic-auction-dynamics) | Structural auction analysis | GPV inversion, kernel density estimation, adaptive bidding |
| [Macro Labor Automation Evaluation](https://github.com/meowcat234of-a11y/macro-labor-automation-eval) | Policy evaluation | Group-time DiD, low-rank counterfactuals, robust inference |
| [Venture Graph Transformer](https://github.com/meowcat234of-a11y/venture-graph-transformer) | Systems ML and graph analytics | RoPE, SwiGLU, KV caching, asynchronous collection, PageRank |

## Engineering approach

- Reproducible environments through package metadata, Conda, or dev containers.
- Deterministic tests and GitHub Actions checks for every repository.
- Mathematical assumptions documented next to the implementation.
- Research prototypes labeled clearly instead of being presented as production
  trading or policy systems.
