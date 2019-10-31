# Bike Sharing Demand

## Introduction

In this project, we are going to take part to the ['Bike Sharing Demand' Kaggle competition](https://www.kaggle.com/c/bike-sharing-demand/overview).

We are going to use bike rental data from the Capital Bikeshare program in Washington, D.C.
The dataset contains hourly rental data spanning two years (2011 and 2012).

Our goal is to combine historical usage patterns with weather data in order to forecast bike rental demand.

## Method

Here are the steps we are going to follow:

1. Data cleaning and first feature engineering
2. We will test 3 to 5 algorithms with all the features and we will very loosely optimize hyperparameters, just to make sure we don't assign extremely bad values to some hyperparameters. We will pick the best 2 to 3 of them.
3. After that, might will re-explore the data to find new patterns in the data and apply a secound round of feature engineering.
4. Thereafter, we will select the best-performing features. We will keep the same set of features for the remaining algorithms or select different sets.
5. We will tune our algorithms through an hyperparametrization procedure.
6. Finally, we will select our best algorithm.
