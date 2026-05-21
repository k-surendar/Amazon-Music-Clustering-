# Amazon-Music-Clustering-

## Project Overview
This project groups Amazon Music songs into clusters based on audio features using unsupervised machine learning.

## Features Used
- danceability
- energy
- loudness
- speechiness
- acousticness
- instrumentalness
- liveness
- valence
- tempo
- duration_ms

## Algorithms Used
- K-Means Clustering
- PCA
- DBSCAN
- Hierarchical Clustering

## Evaluation Metrics
- Silhouette Score
- Davies-Bouldin Index

## Technologies
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Streamlit

## Results
Successfully grouped songs into meaningful clusters such as:
- Party Songs
- Chill Acoustic
- Instrumental
- Relaxing Tracks

## How to Run

```bash
pip install -r requirements.txt
streamlit run streamlit_app.py
