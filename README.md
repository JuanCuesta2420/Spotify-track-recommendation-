# Spotify Recommendation System Project

Project Overview: 
   
    This project focuses on building a Spotify Recommendation System that suggests songs based on their musical characteristics such as BPM (beats per minute), energy, and other audio          features. The system takes a given track and recommends a list of 10 similar songs that match the musical preferences derived from a dataset of 30,000 tracks.

Data Source:
  
  The dataset used contains information on Spotify tracks, including:
   
    - Track ID
    - Artist Name
    - Album Name
    - Track Popularity
    - Duration
    - Explicit Content
    - Audio Features (e.g., BPM, Energy, Danceability, Valence, Acousticness)


Key Steps & Methodologies Used: 
   
    - Data Cleaning & Preprocessing
    - Removed unnecessary columns (e.g., Unnamed: 0).
    - Handled missing values by dropping incomplete records.
    - Converted categorical values (like explicit content) into boolean values for easy analysis.
    - Feature Selection

Used musical attributes such as:
    - Beats Per Minute (BPM)
    - Energy
    - Danceability
    - Valence (happiness/sadness of a song)
    - Acousticness
  These features were used to determine song similarity.


Machine Learning Models Used
   
    - K-Means Clustering: Grouped songs into clusters based on their audio features.
    - Cosine Similarity: Measured the similarity between songs based on feature vectors.
    - Nearest Neighbors (KNN Algorithm): Identified the top 10 most similar songs for a given track.
    - Principal Component Analysis (PCA): Reduced dimensionality to visualize relationships between songs.


Recommendation Process
    
    - User inputs a song they like.
    - The system finds the closest matching cluster.
    - Using KNN and Cosine Similarity, it recommends 10 similar tracks.
    - The system returns a personalized playlist.

Visualization & Analysis:     
   
    - Built scatter plots and heatmaps to visualize the relationships between different audio features.
    - Cluster visualizations to showcase how similar songs are grouped.

Results & Impact
   
    - The recommendation system effectively suggests songs with similar moods, energy levels, and styles.
    - Users receive playlists that match their listening preferences based on objective musical traits rather than subjective tagging.
