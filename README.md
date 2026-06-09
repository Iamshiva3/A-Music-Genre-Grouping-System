# SoundSort — A Music Genre Grouping System

A Flask-based web application that leverages machine learning (K-Means clustering) and rule-based classification to organize music tracks by their rhythmic and acoustic features.

## Features
- **Intelligent Clustering**: Automatically finds the optimal number of music groups using silhouette scoring.
- **Dynamic Genre Assignment**: Maps tracks to genres like EDM, Rock, Pop, and Chill based on energy, tempo, and danceability.
- **Data Visualization**: Generates real-time cluster plots and genre distribution charts.
- **CSV Export**: Allows users to download the processed dataset with predicted labels.

## Tech Stack
- **Backend**: Python (Flask)
- **ML/Analysis**: Pandas, Scikit-learn, NumPy
- **Visualization**: Matplotlib

## Getting Started
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Launch the app:
   ```bash
   python app.py
   ```
