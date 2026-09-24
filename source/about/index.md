---
title: Our Story
eyebrow: Zhenyu Cui · Financial Engineering
description: From quantitative finance research to reproducible analytics for derivatives, volatility, risk and insurance.
---

## From mathematical finance to computational tools

Zhenyu Cui is an Associate Professor with tenure in Financial Engineering at Stevens Institute of Technology and Director of the Financial Engineering Ph.D. program.

His work has developed across quantitative finance, statistics and actuarial science, with a recurring focus on a practical question:

**How can mathematically rigorous models be turned into numerical methods that are accurate, transparent and usable in real financial problems?**

He received his Ph.D. in Statistics and M.S. in Quantitative Finance from the University of Waterloo, following a B.S. in Actuarial Science from the University of Hong Kong.

Over the years, this research has expanded across derivatives pricing, volatility modeling, stochastic simulation, portfolio optimization, risk measurement and insurance analytics.

## Where the research has focused

Several themes have appeared repeatedly across this research program.

### Option markets and implied information

A substantial part of the work studies what can be extracted from option markets: implied volatility, arbitrage-consistent option surfaces, risk-neutral distributions and option-implied measures of risk.

The objective is not only to recover a number such as an implied volatility, but to understand what information is embedded in a full set of market prices and how reliably that information can be extracted.

### Derivative pricing and computational finance

Another major research direction develops numerical methods for pricing derivatives under increasingly realistic models.

This includes continuous-time Markov chain approximations, transform methods, simulation techniques and semi-analytical approaches for products such as barrier options, Asian options, American-style contracts and volatility derivatives.

A recurring goal is to combine mathematical structure with computational methods that can be benchmarked, diagnosed and reproduced.

### Equity and volatility markets

Research on equity and volatility derivatives has increasingly focused on relationships across markets rather than treating each market independently.

This includes methods for jointly modeling and calibrating information from equity options and volatility products such as VIX derivatives.

The broader question is how multiple related markets can be used together to construct more informative and internally consistent models.

### Insurance and actuarial applications

The same computational ideas also extend beyond trading markets.

Research in variable annuities, embedded guarantees, long-term-care features, dynamic fees and actuarial risk measurement applies quantitative finance methods to long-horizon insurance contracts where path dependence and behavioral assumptions play an important role.

## The problem

Academic research often stops at the point where a method has been proved, simulated or demonstrated in a paper.

For an institutional quantitative team, that is only the beginning.

A method still needs to answer practical questions:

- What data does it require?
- What assumptions does it rely on?
- What exactly does it return?
- How does it behave under difficult market conditions?
- How accurate is it relative to a trusted benchmark?
- When does it fail?
- Can another researcher reproduce the result?

Many useful research ideas never become easy to evaluate because this layer between the paper and the implementation is missing.

## Why this site exists

This site is an effort to organize selected research around those practical questions.

Rather than presenting more than a decade of work only as a publication list, related papers are grouped into a smaller set of quantitative capabilities:

- option surface and implied-risk analytics;
- derivative pricing and risk engines;
- equity-volatility joint calibration;
- insurance and annuity analytics.

Each capability is intended to connect the underlying research with concrete inputs, outputs, diagnostics, numerical limitations and reproducible examples.

The objective is not to claim that every paper is already a production-ready product.

The objective is to make it easier for quantitative researchers and institutional teams to determine which methods are relevant, what evidence supports them, and what would be required to test them in a real workflow.

## From research to collaboration

The next step for many of these methods is not another static description.

It is evaluation.

That may mean reproducing a published result, benchmarking an algorithm against an existing system, testing a method on institutional data, or developing a more complete research prototype around a specific use case.

The long-term goal is simple:

**make rigorous quantitative research easier to test, compare and use.**