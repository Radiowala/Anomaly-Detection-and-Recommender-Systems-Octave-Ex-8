# Anomaly-Detection-and-Recommender-Systems-Octave-Ex-8
Build Recommender Systems by Implementing Collaborative Filtering Learning algorithm and apply it to a dataset of movie ratings.
My solutions to Stanford Machine Learning Course

<h2>Anomaly Detection using Gaussian Distribution</h2>

Initial dataset is 2D allowing you to visualize what the algorithm is doing. 

![](https://raw.githubusercontent.com/Radiowala/Anomaly-Detection-and-Recommender-Systems-Octave-Ex-8/master/ex8/Fig2.PNG)

To perform anomaly detection, we will first need to fit a model to the data's distribution. After that you can select a probability threshold and identify outliers


<h2>Recommender Systems</h2>

The first part of the script ex8cofi.m will load the dataset ex8 movies.mat, providing the variables Y and R in your Octave/MATLAB environment.

The matrix Y (a num movies num users matrix) stores the ratings y (from 1 to 5). The matrix R is an binary-valued indicator matrix, where R(i; j) = 1 if user j gave a rating to movie i, and R(i; j) = 0 otherwise. The objective of collaborative filtering is to predict movie ratings for the movies that users have not yet rated, that is, the entries with R(i; j) = 0. 

![](https://raw.githubusercontent.com/Radiowala/Anomaly-Detection-and-Recommender-Systems-Octave-Ex-8/master/ex8/Fig3.PNG)

Dataset from [MovieLens 100K Dataset](https://grouplens.org/datasets/movielens/)

We start by implementing the Collaborative filtering Cost Function and Gradients and start training your algorithm to make movie recommendations for yourself. 
