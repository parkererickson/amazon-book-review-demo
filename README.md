# Link Prediction with FastRP and TigerGraph
## TigerGraph ML Team

This repository contains the code for performing link prediction using FastRP embeddings and TigerGraph, using [this](http://snap.stanford.edu/data/amazon/productGraph/categoryFiles/ratings_Books.csv) dataset.
The `link_prediction.ipynb` notebook focuses on predicting if a User vertex and Book vertex have a Review edge between them.
The `predict_reviews.ipynb` notebook focuses on predicting the review score given a User and Book vertex. This doesn't perform well, as the graph schema does not provide enough information to make a good prediction.