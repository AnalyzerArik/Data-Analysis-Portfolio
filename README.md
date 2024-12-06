# Spotify Song Data Analysis

## Overview
This project represents my second deep dive into Spotify song data, aimed at exploring audio features, playlist dynamics, and their impact on song popularity and streaming performance. Leveraging improved data analysis and visualization skills acquired through previous projects, this analysis provides actionable insights into trends over time, key audio features, and the factors that drive playlist success. The goal is to understand the elements that make songs engaging and popular while honing my data storytelling capabilities. This is a completely different dataset with information directly from the Spotify API.

[Previous Analysis](https://github.com/AnalyzerArik/Spotify-Song-Data-Exploratory-Data-Analysis/blob/main/exploratory-data-analysis-of-spotify-song-data.ipynb)
[Updated (Better) Analysis](https://github.com/AnalyzerArik/Spotify-Song-Data-Exploratory-Data-Analysis/blob/main/spotify-songs-data-analysis_v2.ipynb)
## Data Overview

### Dataset: Spotify Song Data
- **Rows**: 953
- **Columns**: 25 (e.g., `Track Name`, `Artist`, `Danceability`, `BPM`, `Valence`, `Streams`, `Playlist Inclusion`)
- **Source**: Spotify's API request and Kaggle-hosted Spotify datasets. [Kaggle Dataset](https://www.kaggle.com/datasets/ashishak3000/spotify-dataset)

---

## Methodology

### Data Preprocessing
- Cleaned the dataset by handling missing values and normalizing numerical fields for consistency.
- Reformatted and categorized certain features.
- Added a "duration" column by connecting to the Spotify API.

### Exploratory Data Analysis (EDA)
- Examined relationships between audio features (e.g. `Danceability`, `Tempo`, `Danceability`) and their influence on streams and playlist inclusion.
- Conducted statistical analysis of trends over time for audio characteristics.

### Data Visualization
- Visualized key insights with Spotify-themed plots for clarity and branding.
- Clustered songs into distinct groups based on audio feature similarities using advanced statistical methods.

### Categorization and Summary
- Summarized correlations between song attributes and streaming performance.
- Identified actionable patterns, such as audio feature combinations that align with playlist success.

### Features
- **Exploratory Data Analysis (EDA)**: Insights into energy, danceability, tempo, and other key audio features.
- **Trends Over Time**: Analysis of how audio characteristics have evolved over decades.
- **Playlist Dynamics**: Correlation analysis between playlist inclusion, audio features, and streams.
- **Clustering Analysis**: Identification of distinct groups of songs based on their audio features.
- **Visualization**: Clear, Spotify-themed plots and charts to make findings visually compelling.

### Key Findings
1. **Energy and Danceability**: High-energy, danceable songs dominate popularity metrics.
2. **Playlist Inclusion**: Being featured in playlists significantly impacts streams.
3. **Trends Over Time**: Modern music shows increasing energy and danceability, reflecting listener preferences.
4. **Clustering**: Distinct audio feature clusters reveal the diversity of music styles and genres.
5. **Streams vs. BPM**: Tempo alone does not drive streams but complements other features.

### Tools and Technologies
- **Python**: Core programming language used for analysis.
- **Libraries**: 
  - `pandas` for data manipulation
  - `matplotlib` and `seaborn` for visualization
  - `numpy` for statistical calculations
- **Kaggle Notebook**: Interactive environment for running and presenting the analysis.

---

## Final Thoughts
This project demonstrates how much I’ve grown as a data analyst since my initial exploration of Spotify data. Revisiting this dataset allowed me to apply new skills, offering a deeper and more actionable analysis. I hope this work inspires others to explore the intersection of data and creativity, showing how powerful insights can emerge from careful exploration and visualization.

## Future Work
- Integrate machine learning models to predict song popularity based on audio features.
- Analyze listener demographics and regional preferences for a more personalized view.
- Expand the dataset to include global streaming trends and other platforms.

## Acknowledgments
Special thanks to Spotify for providing publicly available data and to the data analysis community for inspiring continuous growth and learning.
