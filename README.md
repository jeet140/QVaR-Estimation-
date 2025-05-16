# Quantum-Enhanced Value-at-Risk (VaR) Estimation

This repository contains the full implementation and documentation of a quantum-enhanced VaR estimation framework for foreign-exchange portfolios, leveraging Quantum Amplitude Estimation (QAE) to achieve a quadratic speedup in tail-risk sampling.

## 📄 Abstract

We introduce a novel framework that reformulates VaR quantile estimation as an amplitude estimation problem on a quantum computer, reducing sample complexity from \(O(1/\varepsilon^2)\) to \(O(1/\varepsilon)\). Our modular quantum circuit encodes truncated normal distributions, imprints empirical correlations, and embeds a loss-threshold oracle. A classical bisection loop refines the VaR threshold to a precision of \(\delta=10^{-3}\). We benchmark this method against Parametric (Variance–Covariance), Historical Simulation, and Monte Carlo (Gaussian copula) on four major FX pairs (AUD/USD, EUR/USD, GBP/USD, USD/JPY) over 2007–2020 with a 250-day rolling window. Results show improved breach rates (2.31% at 95%, 0.70% at 99%) and lower Lopez loss, confirming accurate tail risk coverage and setting the stage for scalable, quantum‐accelerated risk management.

