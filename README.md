![Listen to Renner Worship on Spotify](https://github.com/user-attachments/assets/314cc537-4dc3-458d-9c3e-45bd6a8f31ee)

![aumento-spotify-premium-trucco-pagarlo-meno-2120x840](https://github.com/user-attachments/assets/c115ae51-e275-4261-be13-5b8249cce137)



# work in progress

# Multi-Label Recommendation of Spotify Music Genres Using Content-Based Filtering

# Introduction
The project focuses on developing a multi-label recommendation system to categorize Spotify music tracks into multiple genres using the content-based method. In today’s vast music streaming ecosystem, accurately recommendating tracks into genres helps improve user experience by providing better recommendations and playlist suggestions.

# Background
Spotify offers a diverse range of music genres and subgenres. Traditional genre recommendation models often handle single-label recommendation, where each track is associated with only one genre. However, music tracks often belong to multiple genres simultaneously. This project addresses this challenge by employing a multi-label recommendation approach with the content-based approach  to recommend music tracks into several genres.

# Goal
The primary goal of this project is to create an efficient multi-label recommendation model that can accurately predict multiple genres for a given music track. This model will be built using the content-based techniques , a simple yet effective method for recommending tasks.

# Objective
- Data Collection: Gather a dataset of Spotify music tracks, including features such as tempo, danceability, energy, and other audio features relevant to genre recommendation.
- Data Preprocessing: Clean and preprocess the data to handle missing values, normalize features, and prepare it for multi-label recommendation.
- Model Development: Implement the content-based filtering to recommend music tracks into multiple genres.
- Model Evaluation: Assess the performance of the content-based model using appropriate evaluation metrics for multi-label recommendation, such as F1 score
- Results Interpretation: Analyze the results to understand the strengths and limitations of the content based approach for multi-label music genre recommendation.
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
