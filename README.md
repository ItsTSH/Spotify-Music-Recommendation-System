# Spotify Recommendation System

This project explores building a **music recommendation system** inspired by Spotify’s recommendation engine. The system leverages **audio features, metadata, and machine learning techniques** to provide song recommendations based on user preferences.

## Features

- **Audio Feature Extraction**: Uses Spotify API to fetch track attributes like danceability, energy, tempo, and more.  
- **Dimensionality Reduction**: Applies **PCA** to reduce feature space while retaining meaningful patterns.  
- **Clustering & Similarity**: Implements **K-Nearest Neighbors (KNN)** to find songs most similar to the user’s liked tracks.  
- **Metadata Integration**: Considers additional details such as **genre** and **artist names** for improved recommendation accuracy.  

## Tech Stack

- **Python** (NumPy, Pandas, Matplotlib, Seaborn, Plotly)  
- **Scikit-learn** (PCA, KNN, clustering methods)  
- **Spotify API** for track data  

## How It Works

1. Import your playlist or liked songs from Spotify.  
2. Extract audio features and metadata.  
3. Reduce feature space using PCA for efficient clustering.  
4. Use KNN to recommend similar songs to your playlist.  

## Future Work

- Build a **production-ready implementation** with a backend API and interactive frontend.  
- Experiment with **deep learning models** (e.g., autoencoders) for more sophisticated recommendations.  
- Enhance personalization using user behavior data.  

## Notes

- This repository currently contains a **Jupyter Notebook (`SpotifyRecommendationSystem.ipynb`)** demonstrating the idea.  
- The **actual system implementation** (full-stack with backend + frontend) will be developed in the future.  

---