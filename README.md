# work in progress

# Multi-Label Recommendation of Spotify Music Genres Using Content-Based Filtering

# Introduction
The project focuses on developing a multi-label classification system to categorize Spotify music tracks into multiple genres using the K-Nearest Neighbors (KNN) method. In today’s vast music streaming ecosystem, accurately classifying tracks into genres helps improve user experience by providing better recommendations and playlist suggestions.

# Background
Spotify offers a diverse range of music genres and subgenres. Traditional genre classification models often handle single-label classification, where each track is associated with only one genre. However, music tracks often belong to multiple genres simultaneously. This project addresses this challenge by employing a multi-label classification approach with the KNN algorithm to classify music tracks into several genres.

# Goal
The primary goal of this project is to create an efficient multi-label classification model that can accurately predict multiple genres for a given music track. This model will be built using the KNN algorithm, a simple yet effective method for classification tasks.

# Objective
- Data Collection: Gather a dataset of Spotify music tracks, including features such as tempo, danceability, energy, and other audio features relevant to genre classification.
- Data Preprocessing: Clean and preprocess the data to handle missing values, normalize features, and prepare it for multi-label classification.
- Model Development: Implement the KNN algorithm to classify music tracks into multiple genres.
- Model Evaluation: Assess the performance of the KNN model using appropriate evaluation metrics for multi-label classification, such as Hamming Loss, Precision, Recall, and F1 Score.
- Results Interpretation: Analyze the results to understand the strengths and limitations of the KNN approach for multi-label music genre classification.
- Documentation and Reporting: Document the process, results, and insights gained from the project, providing a clear guide for future improvements and applications.

# Dataset Overview

The dataset includes information on songs/tracks (100 per year) from Top Hit playlists from 2010 to 2023 created by Spotify.

- 2400 attributes
- 23 variables
- 2 playlist related (playlist_url, year)
- 3 track related (track_id, track_name, track_popularity)
- 13 track's audio features (danceability, energy, key, loudness, mode, speechiness, acousticness, instrumentalness, liveness, valence, tempo, duration_ms, time_signature)
- 1 album related (album)
- 4 artist related (artist_id, artist_name, artist_genre, artist_popularity)
