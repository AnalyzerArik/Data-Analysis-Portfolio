# Spotify Song Data Analysis

---

## **Table of Contents**
1. [Introduction](#introduction)  
2. [Dataset Description](#dataset-description)  
3. [Project Objectives](#project-objectives)  
4. [Installation and Setup](#installation-and-setup)  
5. [Project Workflow](#project-workflow)  
6. [Key Findings](#key-findings)  
7. [Tools and Technologies](#tools-and-technologies)  
8. [Future Work](#future-work)  
9. [Acknowledgments](#acknowledgments)  

---

## **Introduction**
This project represents my second deep dive into Spotify song data, aimed at exploring audio features, playlist dynamics, and their impact on song popularity and streaming performance. Leveraging improved data analysis and visualization skills acquired through previous projects, this analysis provides actionable insights into trends over time, key audio features, and the factors that drive playlist success.  

The goal is to understand the elements that make songs engaging and popular while honing my data storytelling capabilities. This project uses a new dataset sourced directly from Spotify's API and a Kaggle-hosted dataset.  

[Previous Analysis](https://github.com/AnalyzerArik/Spotify-Song-Data-Exploratory-Data-Analysis/blob/main/exploratory-data-analysis-of-spotify-song-data.ipynb) / 
[Updated (Better) Analysis](https://github.com/AnalyzerArik/Spotify-Song-Data-Exploratory-Data-Analysis/blob/main/spotify-songs-data-analysis-2.ipynb)

---

## **Dataset Description**
- **Source**: Spotify's API request and Kaggle-hosted Spotify datasets. [Kaggle Dataset](https://www.kaggle.com/datasets/ashishak3000/spotify-dataset)  
- **Rows**: 953  
- **Columns**: 25  
  - Example columns: `Track Name`, `Artist`, `Danceability`, `BPM`, `Valence`, `Streams`, `Playlist Inclusion`.  
- **Preprocessing**: Handled missing values, normalized numerical fields, and added a "duration" column using the Spotify API.  

---

## **Project Objectives**
- Explore the relationship between audio features and song popularity.  
- Understand trends in music characteristics over time.  
- Identify key factors driving playlist inclusion and streaming performance.  
- Develop clear visualizations to communicate findings effectively.  

---

## **Installation and Setup**
1. Clone the repository:
   ```bash
   git clone https://github.com/AnalyzerArik/Spotify-Song-Data-Exploratory-Data-Analysis.git
2. Navigate to the project directory:
   ```bash
   cd Spotify-Song-Data-Exploratory-Data-Analysis
3. Install the required libraries:
   ```bash
   pip install -r requirements.txt
4. Run the jupyter notebook:
   ```bash
   jupyter notebook


## **Project Workflow**

### **Data Preprocessing**
- Cleaned and reformatted the dataset.  
- Handled missing values and normalized fields.  
- Added a "duration" column via Spotify API integration.  

### **Exploratory Data Analysis (EDA)**
- Analyzed correlations between audio features (e.g., `Danceability`, `Tempo`) and streaming performance.  
- Conducted trend analysis of music characteristics over decades.  

### **Visualization**
- Used Spotify-themed visualizations to highlight insights.  
- Clustered songs based on audio features using advanced statistical methods.  

### **Summary**
- Generated actionable patterns and key insights to understand song popularity and playlist dynamics.  

---

## **Key Findings**
1. **Energy and Danceability**: High-energy, danceable songs dominate popularity metrics.  
2. **Playlist Inclusion**: Being featured in playlists significantly boosts streams.  
3. **Trends Over Time**: Modern music trends show increasing energy and danceability.  
4. **Clustering**: Audio feature clusters reveal diverse music styles and genres.  
5. **Streams vs. BPM**: Tempo complements other features but isn’t the sole driver of popularity.  

---

## **Tools and Technologies**
- **Programming Language**: Python  
- **Libraries**:  
  - `pandas` for data manipulation  
  - `numpy` for statistical calculations  
  - `matplotlib` and `seaborn` for visualizations  
- **Platforms**: Kaggle Notebook for analysis and presentation.  

---

## **Future Work**
- Integrate machine learning models to predict song popularity.  
- Analyze listener demographics and regional preferences.  
- Expand the dataset to include global streaming trends and data from other platforms.  

---

## Final Thoughts
This project demonstrates how much I’ve grown as a data analyst since my initial exploration of Spotify data. Revisiting this dataset allowed me to apply new skills, offering a deeper and more actionable analysis. I hope this work inspires others to explore the intersection of data and creativity, showing how powerful insights can emerge from careful exploration and visualization.

---

## **Acknowledgments**
Special thanks to Spotify for providing publicly available data and to the data analysis community for inspiring continuous growth and learning.  
