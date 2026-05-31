# M2R-Score-driven-Filtering

In the context of score-driven filtering of time series, the innovation term of the filter considered here for the dynamic location $\mu$ (observed with heavy tailed noise) form a sequence of independent random variables with well-understood properties, such as sub-Gaussianity and limit Gaussianity. More generally, they can be interpreted as some scaled score of a location-scale student-t random variable, and are shown to robustify the filtering of unobserved dynamic parameters by reducing the impact that outliers / extreme observations deliver throughout updates.

To investigate the utility of this score-driven filtering framework, two time series applications using real world data (S&P 500) are presented: 
1. an unobserved location model robustified by the combination of heavy-tailed measurement noise and sub-Gaussian state noise (which yields the classical Kalman filter when all degrees of freedom tend to infinity), and
2. a conditional variance GARCH-type model with limit-Gaussian innovations optimized for tracking volatility clustering in data without extreme outliers, such as macroeconomic or biostatistical data.
