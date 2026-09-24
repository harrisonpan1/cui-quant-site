---
title: Technology
eyebrow: Research-to-industry capabilities
description: Four connected research tracks organized around quantitative workflows, with explicit assumptions, diagnostics and maturity levels.
---

## Option Surface & Implied Risk Analytics {#surface}

This track turns option quotes into structured, diagnosable market information.

| Capability | Research basis | Intended output | Initial boundary |
|---|---|---|---|
| Joint American call/put surface smoothing | Joint arbitrage-free smoothing | Adjusted price/IV surface, constraint diagnostics, quote-deviation report | Start from validated non-dividend settings |
| Implied-volatility inversion | Delta-family and bound methods | IV, residual, bounds, failure status | Shared computational primitive |
| Risk-neutral density & distribution | Risk-neutral density representations and Fourier-cosine methods | Density, CDF, skew and maturity comparisons | European-price input; tail and positivity checks |
| Option-implied quantiles | Model-free option-implied quantiles | Quantile curve, identifiable probability range, sensitivity | Clearly labeled under the risk-neutral measure |

> The site should never turn a risk-neutral quantity into a physical-probability forecast without additional modeling assumptions.

## Derivative Pricing & Risk Engine {#pricing}

A modular pricing stack built from continuous-time Markov chain approximations, transforms, semi-analytical methods and simulation.

### Initial model and contract scope

- One reproducible base model plus one stochastic-volatility / stochastic-local-volatility model.
- European benchmark plus one discretely monitored barrier contract as a validated path-dependent example.
- Price, selected Greeks, parameter scenarios, numerical settings and explicit error states.
- Benchmark each method on a common hardware and accuracy target before making performance claims.

### Longer-term expansion

Asian, Bermudan/American, occupation-time, timer, VIX/variance products, rough volatility and selected multi-asset claims can be added only as the corresponding implementations are validated.

## Equity–Volatility Joint Calibration {#joint}

The distinctive research direction here is simultaneous information extraction from the equity option market and the volatility-derivative market.

A flagship research preview can compare:

1. a calibration using equity options only;
2. a joint SPX/VIX calibration;
3. errors for both markets separately;
4. constraint residuals, runtime and solver failure flags.

The first public version should use precomputed market snapshots until sparse-data behavior, non-standard maturities and initialization are robust enough for controlled programmatic access.

## Insurance & Annuity Analytics {#insurance}

Research on variable annuities and actuarial risk naturally forms a separate solution area because the contracts, data and validation criteria differ from trading-desk workflows.

Representative capabilities include VIX-linked fee design, GLWB/LTC valuation, multi-asset annuity Greeks, surrender analysis and risk measures. Any public example should fix the contract specification, mortality/health assumptions, surrender behavior and economic scenario set.
