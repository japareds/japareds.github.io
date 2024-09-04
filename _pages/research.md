---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My main research line is the use of advanced statistical techniques and machine learning to analyze data captured with IoT devices. Here is a list of some research topics I have worked on.

## Machine learning models for black carbon exposure modelling
Black carbon (BC) is a product of incomplete combustion, present in urban aerosols and sourcing mainly from road traffic. Epidemiological evidence reports positive associations between BC and cardiovascular and respiratory disease. Despite this, BC is currently not regulated by the Air Quality Directives, and as a result BC data are not available in urban areas from reference air quality monitoring networks in many countries. One solution is to use proxies, which consist of creating a mathematical model that infers the measurement of the pollutant from indirect measurements of other pollutants.\

To fill this gap, a machine learning approach is proposed to develop a BC proxy using air pollution and meteorological variables datasets as an input. Experimental data were collected from a reference station in Barcelona (Spain) over a 2-year period (2018–2019).\

BC concentrations estimated by SVR showed a high degree of correlation with the measured BC concentrations (R2 = 0.828) with a relatively low error (RMSE = 0.48 μg/m3). Model performance was dependent on seasonality and time of the day, due to the influence of new particle formation events. From the analysis it was possible to infer that new particle formation events critically impacted model performance, suggesting that its application would be optimal in environments where traffic is the main source of ultrafine particles. Due to its flexibility, it is concluded that the model can act as a BC proxy, even based on EU-regulatory air quality parameters only, to complement experimental measurements for exposure assessment in urban areas.\

[Find out more about the topic here](https://www.sciencedirect.com/science/article/pii/S0013935122005965)

## A robust Black Carbon estimation pipeline

This research topic focuses on building a robust machine learning proxy (RMLP) framework for estimating BC based on nonlinear machine learning methods. Instead of deploying expensive ML models we enhance the data quality of low-cost monitoring stations for an affordable monitoring network.\

We show the impact of data aggregation, denoising and missing imputation on BC estimation, and how the concentrations estimated by the BC proxy approximate the values obtained by a reference instrument with an accurate BC sensor.  [Find out more about the topic here](https://digital.csic.es/bitstream/10261/331330/1/3597064.3597316.pdf).

##Sensor placement
For a given pollution source, the dispersion model computes the concentration gradient at the sensor location which is weighted with properties of the LCS network to obtain an observable area for it components. A strategy for placing sensors can be obtained such taht the coverage area is maximized.
