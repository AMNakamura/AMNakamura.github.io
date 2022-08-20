---
layout: default
title: Creating, Organizing, and Graphing Models
parent: Time Series
nav_order: 2
---

[Organizing GLS Models](https://github.com/AMNakamura/miscellanea/blob/master/time_series/GLS_Scaled0.md) uses list processing and functions applied to lists to enable processing of a number of time series for OLS and GLS models, to consolidate diagnostic plots and other visualizations and reduce the lines of code (goal < 500 lines, with comments). 
Tables with model characteristics are coerced into data frames and formatted for quick review. 


[Quick Counterfactual Dashboard](https://github.com/AMNakamura/miscellanea/blob/master/time_series/CounterFactual_ITS_Dashboards.md) quickly gets a visual sense of the potential impact of an environmental change on a number of different time series. 
This example uses the CausalImpact package to create the models (Bayesian structural time series (BSTS)) and a set of graphs showing the difference between the what was expected to happen in the absence of the change (counterfactual) and what actually happened, accounting for trends and seasonality.



