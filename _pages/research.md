---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My main research line is the use of machine learning techniques to analyze data captured with IoT devices. I am currently working on ensuring an adequate level of quality in the data captured by low-cost sensor networks (LCS). The challenge of deploying LCS is to maintain the best possible quality of the measured data. For this purpose, LCS are calibrated in-situ with machine learning algorithms.

## Machine learning models for air pollution modelling
The raw data streams of the network are combined to train a model that estimates the pollutant concentration at a point of interest. Different regression supervised machine learning models can be used (MLR, SVR, RF, KNN, ANN)

**Black carbon proxy:** Black carbon (BC) is a product of incomplete combustion, present in urban aerosols and sourcing mainly from road traffic. Epidemiological evidence reports positive associations between BC and cardiovascular and respiratory disease. Unfortunately, BC is currently not regulated by the EU Air Quality Directive, which makes the availability of BC measurements operationally expensive and difficult with not enough available data in urban areas from reference air quality monitoring networks in many countries. When there is no sensor available, a ML proxy acts as a specific type of virtual sensor that estimates a target pollutant from indirect sensor measurements. [Find our related research here](https://www.sciencedirect.com/science/article/pii/S0013935122005965)

**A robust BC pipeline**:  Data gaps, measurement noise, and outliers limit the quality of the model estimate. Instead of deploying expensive models we enhance the data quality of low-cost monitoring stations for an affordable monitoring network. [Find more about the topi here](https://www.sciencedirect.com/science/article/pii/S0013935122005965).

**Air quality forecast:**  A dispersion model provides air quality forecasts of airborne pollutants which is then combined with sensor measurements. This process corrects the modeled concentration field so that simulated values are adjusted in magnitude to match observations both in the local vicinity and globally across the domain. This data fusion has the potential to provide insight into the spatial patterns far from the measuring site. 

**Sensor location:** For a given pollution source, the dispersion model computes the concentration gradient at the sensor location which is weighted with properties of the LCS network to obtain an observable area for it components. A strategy for placing sensors can be obtained such taht the coverage area is maximized.
