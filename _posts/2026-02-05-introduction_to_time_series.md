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
math: true
---

Any metric that is measured over regular time intervals makes a Time Series. Some examples are:

* Weekly averages of atmospheric CO₂ concentrations in Hawaii from 1958 to 2001
* Quarterly inflation rate in the United States from 1959 Q1 to 2009 Q3

plotted in the figures below.

<figure>
  <img src="/images/posts/time_series/01_introduction_to_time_series/01_co2_time_series.png"
       alt="Weekly CO₂ concentration in Hawaii."
       style="width:70%; display:block; margin: 0 auto;">
  <figcaption style="text-align:center;">
    Weekly averages of atmospheric CO₂ concentrations in Hawaii from 1958 to 2001.
    Data source:
    <a href="https://www.statsmodels.org/stable/datasets/generated/co2.html"
       target="_blank" rel="noopener">
      Statsmodels CO₂ dataset
    </a>.
  </figcaption>
</figure>


<figure>
  <img src="/images/posts/time_series/01_introduction_to_time_series/01_infl_time_series.png"
       alt="Quarterly inflation rate in the United States."
       style="width:70%; display:block; margin: 0 auto;">
  <figcaption style="text-align:center;">
    Quarterly inflation rate in the United States from 1959 Q1 to 2009 Q3.
    Data source:
    <a href="https://www.statsmodels.org/stable/datasets/generated/macrodata.html"
       target="_blank" rel="noopener">
      Statsmodels macrodata dataset
    </a>.
  </figcaption>
</figure>


**Definition 1.** **Time series** is a dataset of observations indexed in time order

$$ \{x_t \} = \{x_t | t \in \{1, 2, ..., n\} \} = (x_1, x_2, ..., x_n)$$

where $$x_t$$ is an observation at the time step $$t$$.


**Example 1.** $$(1.2, -0.3, 2.0, 0.3, -0.2)$$ is a time series of $n = 5$ observations. We have:
$$
x_1 = 1.2 \\
x_2 = -0.3 \\
x_3 = 2.0 \\
x_4 = 0.3 \\
x_5 =-0.2
$$
