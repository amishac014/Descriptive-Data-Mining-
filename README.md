# Descriptive-Data-Mining-
Clustering and descriptive analysis of Spotify–YouTube song data using K-Means to identify patterns in popularity based on audio features and engagement metrics.
Descriptive Data Mining on Spotify–YouTube Music Dataset
Project Overview

This project performs descriptive data mining on a Spotify–YouTube dataset to understand how audio features and user engagement metrics describe song popularity. The goal is to uncover natural groupings of songs based on similarity and identify key attributes that influence listening behavior.

Dataset

The dataset contains information about top songs and their corresponding YouTube videos, including features such as:

Danceability, Energy, Loudness, Valence, Tempo

Acousticness, Instrumentalness, Liveness, Speechiness

Views, Likes, Comments, and Streams

Methodology

Unsupervised learning was applied using K-Means Clustering to group songs based on their audio characteristics and popularity indicators.

Steps included:

Data cleaning (handling missing values and duplicates)

Feature scaling using MinMaxScaler and StandardScaler

Correlation analysis using heatmaps

Optimal cluster selection using Elbow Method and Silhouette Score

Dimensionality reduction using PCA for visualization

Cluster interpretation using mean feature values

Key Findings

The optimal number of clusters was found to be k = 3.

One cluster represents highly popular songs with high energy, danceability, and loudness.

Another cluster contains less popular, more acoustic and instrumental tracks.

The third cluster shows moderate popularity with balanced audio attributes.

Tools & Technologies

Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Google Colab

Outcome

This analysis demonstrates how descriptive data mining and clustering can be used to segment music based on listener behavior and audio features, providing insights useful for music recommendation systems and popularity prediction models.
