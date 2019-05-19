
# Distributed_ML

This repository contains a time series analysis of the [Bike Sharing in Washington D.C. Dataset](https://www.kaggle.com/marklvl/bike-sharing-dataset), as well as the development of a model that is capable of determining the varying demands of the service.

The main aspect of this project is to implement the functionalities of the [Dask Library](https://dask.org/) which "provides advanced parallelism for analytics, enabling performance at scale".

Dask allows us to work with data in a distributed fashion, and with [Dask-ML](https://github.com/dask/dask-ml) we are able to produce models that take advantage the full processing capabilities of our environment.

### Outline

The project is separated in 3 steps:

* **Data Loading and Exploratory Data Analysis:** Load the data and analyze it to obtain an accurate picture of it, its features, its values (and whether they are incomplete or wrong), its data types among others. Also, the creation of different types of plots in order to help us understand the data and make the model creation easier.

* **Feature Engineering / Pipeline and Hyperparameter Tuning:** Once we have the data, we create some features and then create a pipeline with different transformers, we will hopefully produce a model that fits our expectations of performance. Once we have that model, a process of tuning it to the training data would be performed.

* **Results and Conclusions:** Finally, with our tuned model, we  predict against the test set we decided to separate initially, then we review those results against their actual values to determine the performance of the model, and finally, outlining our conclusions. 

### Notes
This project uses [Black](https://github.com/python/black) for formatting and optionally requires having a Kaggle account in order to use its API to download the datasets.