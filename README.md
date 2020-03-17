# Predictive Maintainance

## Introduction:

The project objective is to enhance the maintenance operations and planning of time-based preventive maintenance by applying data science techniques and machine learning algorithms for predicting more accurate maintenance requirements.

## Problem:

Failure prediction is a major topic in predictive maintenance in many industries. Airlines are particularly interested in predicting equipment failures in advance so that they can enhance operations and reduce flight delays.

Observing engine's health and condition through sensors and telemetry data is assumed to facilitate this type of maintenance by predicting Time-To-Failure (TTF) or Remaining Useful Life (RUL) of in-service equipment. Using aircraft engine's sensors measurements, The project attempt to provide the following predictions:

* Engine's TTF
* Which engines will fail in the current period or cycle window
* Maintenance plan based on prediction of engines failure per period   


## Data:

Text files contain simulated aircraft engine run-to-failure events, operational settings, and 21 sensors measurements are provided by Microsoft. It is assumed that the engine progressing degradation pattern is reflected in its sensor measurements.

**Training Data:** The aircraft engine run-to-failure data. download trianing data<br />
**Test Data:** The aircraft engine operating data without failure events recorded. download test data<br />
**Ground Truth Data:** The true remaining cycles for each engine in the testing data. download truth data
