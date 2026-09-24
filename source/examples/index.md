---
title: Examples
eyebrow: Reproducible case studies
description: Each example is framed as a concrete quantitative question with clear inputs, outputs, benchmarks and failure conditions.
---

## 1. Can sparse American quotes form a consistent surface?

**Input:** a fixed-time call/put option chain with strike, expiry, bid/ask, spot, rates and clearly documented dividend assumptions.

**Show:** raw quotes and violations on the left; adjusted price/IV surfaces on the right; below that, quote adjustments, weighted error and the fraction remaining inside bid/ask.

**Validate:** constraint residuals, deviation from observed quotes, sparse-input failure rate and runtime.

## 2. What downside distribution is embedded in option prices?

Use a single European option chain to recover a risk-neutral CDF, density and selected quantiles. Visually separate the strike region supported by observed quotes from extrapolated tails.

**Validate:** CDF monotonicity, density non-negativity and normalization, repricing error and quantile residuals.

## 3. Why does barrier monitoring frequency change value?

Hold the model and contract terms fixed while switching between monthly, weekly and daily monitoring. Compare contract value, mechanism explanation and numerical cost.

**Important:** continuous and discrete monitoring define different contracts. Their price difference is not automatically numerical error.

## 4. What changes when SPX and VIX are calibrated jointly?

Use a small set of precomputed market snapshots. Display the two market surfaces vertically, then compare equity-only and joint calibration results.

**Report:** separate RMSEs, bid/ask coverage, constraint residuals, runtime, solver status, initialization and maturity conventions.

## 5. How do VIX-linked annuity fees affect contract value and model-implied surrender?

Fix one contract and behavior model, then compare a fixed fee, VIX-linked fee and capped fee under the same guarantee level.

### Standard case-study template

| Step | Required content |
|---|---|
| 1 | One-sentence user problem |
| 2 | Data, date, contract and model scope |
| 3 | Raw input versus technical output |
| 4 | Benchmark, error, runtime and failure status |
| 5 | What can be concluded and what is not covered |
| 6 | Research basis and contact / controlled-trial entry |
