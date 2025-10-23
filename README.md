🎵 Spotify Tracks Data Analysis 📘 Overview

This project explores and analyzes Spotify tracks data to uncover trends in music over the years. The dataset includes information such as track name, artist, release year, and various audio features like danceability, energy, and tempo. The analysis involves Exploratory Data Analysis (EDA) with visualizations such as histograms, doughnut charts, and line charts to understand patterns in music characteristics.

📂 Dataset Description

The dataset includes 22 columns. Below are a few key attributes:

Column Name Description track_id A unique identifier for each track on Spotify track_name The title of the song artist_name The name of the artist(s) year The release year of the track popularity A score (0–100) representing how popular a track is danceability Describes how suitable a track is for dancing energy Represents the intensity and activity of a track tempo The overall speed or pace of the track liveness, valence, acousticness, instrumentalness, loudness, speechiness, etc. Various audio characteristics describing the track’s sound profile

(See spotify_data_description.xlsx for the full list of columns.)

⚙️ Requirements

Make sure you have the following installed:

pip install pandas matplotlib seaborn plotly

Optional:

pip install jupyter

🚀 How to Run the Notebook

Upload or open the notebook (spotify_eda.ipynb) in Google Colab or Jupyter Notebook.

Import the dataset:

import pandas as pd df = pd.read_csv('spotify_data.csv')

Run the EDA cells to generate:

Histograms for distributions (e.g., popularity, tempo, energy)

Doughnut charts for categorical summaries

Line charts for year-wise or trend analysis

View insights — interpret charts to find patterns in music popularity, audio features, and artist trends.

📊 Example Visualizations

Histogram: Track popularity distribution

Doughnut Chart: Share of genres or artist frequency

Line Chart: Trends of average tempo or energy over years

📈 Goals of the Project

Understand how musical characteristics have evolved over time.

Identify the relationship between audio features and popularity.

Visualize the most common traits in successful Spotify tracks.

📁 Files in This Project File Description spotify_data_description.xlsx Contains column names and their descriptions spotify_data.csv Main dataset (to be used for analysis) spotify_eda.ipynb Jupyter Notebook with EDA code README.md Project documentation (this file) 🧠 Author

Developed by Snehal Basu as part of a data analysis learning project on Spotify music trends.# spotify-dataset-analysis