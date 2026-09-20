# MMRA Mandelbrot Reseach

### Summary

This project investigates the long term dependence and scaling properties of financial time series using the estimation of the Hurst exponent.

The idea was inspired by Benoit Mandelbrot's book <<The (Mis)Behaviour of Markets>>, which challenges the classical assumption that financial markets can be correclty described by simple Gaussian random walks. Mandelbrot's work emphasizes the importance of scaling, long-range dependence, volatility clustering, and heavy tailed distributions when analyzing financial markets.

This repository focuses on one of these concepts: the Hurst exponent, using it as a quantitative tool to investigate whether financial time series exhibit characteristics associated with persistence, anti-persistence, or behavior closer to a random walk.

The objective is not to use the Hurst exponent as a standalone trading signal, but to develop a quantitative framework for understanding the statistical structure of financial markets.

### Motivation

Classical financial models often rely on assumptions such as independent returns and random-walk behavior. However, as explained above, Mandelbrot's research proposed a different perspective: financial time series can exhibit complex statistical properties that are not fully captured by classical Gaussian models.

One of the questions that motivates this project is: Do financial markets exhibit measurable long range dependence and scaling behavior that changes across assets and time periods?

The Hurst exponent provides one possible framework for investigating this question. For a process characterized by a Hurst exponent (H):

* $H \approx 0.5$: is commonly associated with behavior consistent with a random walk,

[
H > 0.5
]

is associated with persistence, while

[
H < 0.5
]

is associated with anti-persistence.

These interpretations should be treated carefully, since the estimated Hurst exponent can be affected by finite samples, non-stationarity, volatility clustering, structural breaks, and the estimation method itself.
