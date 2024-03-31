# Time Series Forecasting with Deep Learning

This repository contains code and resources for time series forecasting using deep learning techniques, focusing on Bitcoin price prediction as a case study.

## Contents

1. [Getting Time Series Data](#getting-time-series-data)
2. [Loading Time Series Data](#loading-time-series-data)
3. [Formatting Data](#formatting-data)
4. [Creating Training and Test Sets](#creating-training-and-test-sets)
5. [Visualizing Time Series Data](#visualizing-time-series-data)
6. [Turning Time Series Data into a Supervised Learning Problem](#turning-time-series-data-into-a-supervised-learning-problem)
7. [Preparing Univariate and Multivariate Data](#preparing-univariate-and-multivariate-data)
8. [Evaluating a Time Series Forecasting Model](#evaluating-a-time-series-forecasting-model)
9. [Setting up Deep Learning Modeling Experiments](#setting-up-deep-learning-modeling-experiments)
10. [Dense (Fully-Connected) Networks](#dense-fully-connected-networks)
11. [Sequence Models (LSTM and 1D CNN)](#sequence-models-lstm-and-1d-cnn)
12. [Ensembling](#ensembling)
13. [Multivariate Models](#multivariate-models)
14. [Replicating the N-BEATS Algorithm](#replicating-the-n-beats-algorithm)
15. [Creating a Modeling Checkpoint](#creating-a-modeling-checkpoint)
16. [Making Predictions](#making-predictions)
17. [Creating Prediction Intervals](#creating-prediction-intervals)
18. [Discussing Uncertainty in Machine Learning](#discussing-uncertainty-in-machine-learning)

## Getting Time Series Data

Retrieve historical Bitcoin price data from a reliable source such as cryptocurrency exchanges or financial data APIs.

## Loading Time Series Data

Load the time series data into Python using Pandas or Python's CSV module.

## Formatting Data

Format the loaded data for time series forecasting, ensuring it contains appropriate timestamps and target variables.

## Creating Training and Test Sets

Avoid common pitfalls in creating training and test sets, ensuring proper chronological splitting for time series data.

## Visualizing Time Series Data

Visualize the time series data to understand its patterns and trends using libraries like Matplotlib.

## Turning Time Series Data into a Supervised Learning Problem

Transform time series data into a supervised learning problem using windowing techniques.

## Preparing Univariate and Multivariate Data

Prepare both univariate and multivariate data for modeling, incorporating additional features alongside Bitcoin price.

## Evaluating a Time Series Forecasting Model

Evaluate the performance of time series forecasting models using appropriate evaluation metrics and cross-validation techniques.

## Setting up Deep Learning Modeling Experiments

Conduct a series of deep learning modeling experiments to explore different architectures and techniques for time series forecasting.

## Dense (Fully-Connected) Networks

Implement fully-connected neural networks using frameworks like TensorFlow or PyTorch.

## Sequence Models (LSTM and 1D CNN)

Utilize sequence models such as Long Short-Term Memory (LSTM) or 1D Convolutional Neural Networks (CNN) for capturing temporal dependencies.

## Ensembling

Combine multiple forecasting models using techniques like model averaging or stacking to improve overall prediction performance.

## Multivariate Models

Develop models capable of handling multivariate time series data by incorporating multiple input features into the architecture.

## Replicating the N-BEATS Algorithm

Replicate the N-BEATS algorithm using TensorFlow's layer subclassing to create a flexible and scalable forecasting model.

## Creating a Modeling Checkpoint

Create checkpoints during training to save the best performing model and avoid losing progress in case of interruptions.

## Making Predictions

After training the models, make forecasts for future time steps.

## Creating Prediction Intervals

Estimate prediction intervals to quantify uncertainty associated with the forecasts using techniques like bootstrapping or Bayesian inference.

## Discussing Uncertainty in Machine Learning

Discuss two different types of uncertainty in machine learning: data uncertainty and model uncertainty, and their implications in time series forecasting applications.

---

Feel free to contribute to this repository by adding new models, techniques, or improving existing implementations. Pull requests are welcome.
