# Unsuperviesd_ML_project
Creating playlists on Moosic:  an analysis involving music, data and machine learning

Welcome to the Moosic Playlist Clustering project! This repository contains an unsupervised machine learning project aimed at clustering songs playlists for the company Moosic. In this project, we utilized the K-Means algorithm to group songs based on their Spotify features. The project involved the analysis of a dataset consisting of 5000 songs, leveraging various techniques and steps to achieve meaningful clusters.

# Introduction
 Moosic, a cutting-edge music company, is constantly seeking innovative ways to enhance user experience. This project aimed to explore unsupervised machine learning techniques to cluster songs playlists, enabling Moosic to gain insights into music preferences and create personalized recommendations.

#Data Preparation
 We began by preparing the dataset for analysis. The following steps were taken:

 1-Reading the Data: The Spotify features data for 5000 songs was collected and loaded into the project environment.
 2-Initial Quick Exploration: Basic exploratory data analysis was conducted to gain an understanding of the dataset's structure and content.
 3- Dropping Unwanted Features: Features deemed irrelevant or redundant were removed to streamline the dataset for clustering.

# Modelling
To achieve meaningful clusters, we followed these steps:

 1- Data Scaling: Prior to clustering, the data was scaled to ensure that each feature contributed equally to the analysis. Other transformations were also considered to enhance model performance.
 2- K-Means Exploration: We employed the elbow method and silhouette coefficient to determine an optimal number of clusters for K-Means.
 3- K-Means Final Model: Based on our exploration, we implemented the K-Means algorithm with the selected number of clusters, creating a robust model for playlist clustering.

# Cluster Exploration
 After clustering, we delved into cluster analysis:

 1- Univariate and Bivariate Exploration: We conducted thorough analysis of the clusters, exploring individual features and relationships between features within each cluster.
 2- Manual Labelling: Each cluster was manually labeled based on the characteristics of the songs it contained, providing interpretability to the clusters.

#Results
 The results of this project provide Moosic with valuable insights into song preferences and playlist composition. By categorizing songs into clusters, Moosic can enhance its recommendation system and tailor playlists to individual users' tastes.

#Usage
 If you wish to replicate or build upon this project, follow these steps:

 1- Clone this repository to your local machine.
 2- Ensure you have the necessary dependencies installed (list them in a requirements.txt file).
 3- Run the provided Jupyter Notebook or Python script to reproduce the analysis and clustering.
