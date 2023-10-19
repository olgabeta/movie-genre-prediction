# Movie genre prediction

*[Wikipedia Movie Plots](https://www.kaggle.com/datasets/jrobischon/wikipedia-movie-plots)*

This dataset contains features from 34,886 movies from around the world. The goal of this project was to predict the genre of a movie based on its plot summary.

- Machine Learning approach:
Multi-label classification using LinearSVC algorithm and OneVsRest classifier, with manual preprocessing of the genre data.
  
- Deep Learning approach:
Single-label classification using a sequential LSTM RNN classification model, with either manual preprocessing of the genre data or k-means approach to the genre clustering.

--------

This repository contains:
- Deep Learning approach (.ipynb file)
- Machine Learning approach (.ipynb file)
