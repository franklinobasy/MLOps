# Developing end-to-end pipeline in MLflow

## Stock Prediction Project

We will prototype a simple stock prediction project in this section with MLflow and will
document the different files and phases of the solution. You will develop it in your local
system using the MLflow and Docker installed locally.

**Important Notice**: MLflow and Docker are installed locally

The task in this illustrative project is to create a basic MLflow project and produce a
working baseline ML model to predict, based on market signals over a certain number of
days, whether the stock market will go up or down.

### Description

In this section, we will use a Yahoo Finance dataset available for quoting the BTC-USD
pair in `https://finance.yahoo.com/quote/BTC-USD/` over a period of 3
months. We will train a model to predict whether the quote will be going up or not on a
given day. A REST API will be made available for predictions through MLflow.
