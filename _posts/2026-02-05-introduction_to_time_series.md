---
title: "Introduction to Time Series"
collection: posts
permalink: /posts/introduction_to_time_series/
date: 2026-02-05
excerpt: "An intuitive introduction to time series with examples."
tags:
  - time series
  - stochastic process
  - sampling
---

Any metric that is measured over regular time intervals makes a Time Series.

Some examples include:
* Weekly averages of atmospheric CO2 concentrations in Hawaii. Data source: [statsmodels](https://www.statsmodels.org/stable/datasets/generated/co2.html)

<figure style="text-align: center;">
  <img src="/images/posts/time_series/01_introduction_to_time_series/01_co2_time_series.png" style="width:50%;">
  <figcaption>
    Weekly averages of atmospheric CO2 concentrations in Hawaii from 1958 to 2001.
  </figcaption>
</figure>

* Quarterly inflation rate in the United States from 1959 Q1 to 2009 Q3
  <figure style="text-align: center;">
  <img src="/images/posts/time_series/01_introduction_to_time_series/01_infl_time_series.png" width="300">
  <figcaption>
    Quarterly inflation rate in the United States from 1959 Q1 to 2009 Q3. Data source: [statsmodels](https://www.statsmodels.org/stable/datasets/generated/macrodata.html).
  </figcaption>
</figure>
