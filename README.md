
# Exploring Time Series Data - Introduction

## Introduction
In this section, you will learn about working with an important and ever-present type of data: time series! Stock market prices, weather, and economic indicators like GDP are a few examples of time series data.


## Time Series Data

"Time series" data refers to datasets where the progress of time is an important dimension in the dataset. For example, working with the changes in stock prices, oil flow through a pipeline or even climate data over time requires an understanding of how to work with time series data. We introduce the concept of time series data, look at how to manage and visualize time series data, introduce the types of trends and the idea of "time series decomposition". In the next section, we'll introduce techniques for modeling time series data.

### Introduction to Time Series

We start by importing daily minimum temperatures for Melbourne, Australia and introduce the importance of using dates as index values when importing time series data into Pandas. We then go through how to downsample and upsample a dataset and show some of the built-in methods for easily selecting and slicing time series data. We also provide an introduction to some of the most common plots for time series such as a line plot and a dot plot, and approaches to grouping and visualizing time series data.

We also introduce the use of time series histograms and density plots for visualizing the distribution of the values without considering the times at which the values were measured and suggest time series box and whisker plots on a per-year basis to get a sense of trends over time. Finally, we introduce time series heat maps which can be a great way of getting a sense of how time series data changes across a couple of dimensions (e.g. month to month and year to year).


### Types of Trends

Basic regression tests are often not capable of capturing and predicting time-dependent patterns, so we introduce the concept of trends and stationarity, and explain the Dickey-Fuller test for performing statistical testing for time series stationarity.


### Removing Trends

Most time series modeling techniques assume stationarity, so we look at some of the techniques available for removing (or reducing) trends and/or seasonality using techniques such as a log transformation, rolling means, and differencing.


### Time Series Decomposition

Finally, we end the section by introducing the concept of decomposition - another approach to removing trends and seasonality from a time series dataset.


## Summary

This section will provide you with the foundational knowledge for loading and working with time series data, so you'll have the skills required to start to perform time series modeling!
