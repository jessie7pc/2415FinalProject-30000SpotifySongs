# 2415FinalProject-30000SpotifySongs 🎵
2024 Fall Information Visualization Final Report using dataset 30000 Spotify Songs

# Spotify Songs Analysis and Visualization 🎧

## 🌟 Overview
This repository contains the analysis and visualizations of **30,000 Spotify songs**, focusing on song popularity, artist trends, genre distributions, and audio features. The project provides data-driven insights into music preferences, helping to inform playlist curation, music production, and marketing strategies. The analysis is divided into two parts, with detailed visualizations for each.

---

## 🎤 Part 1: Popular Artists, Songs, and Genres 👩‍🎤👨‍🎤🎶

### **Figure 1: Popularity Distribution of Top 50 Artists in Pop Genre**
   <img width="847" alt="image" src="https://github.com/user-attachments/assets/9cf47b82-052d-46b7-8acc-afed134a7f73">
   - **Legend**: 📈 Boxplot showing the distribution of track popularity per artist, with medians (blue line) and outliers (purple diamonds)  
   - **X-axis**: Artists sorted by upper quartile popularity
   - **Y-axis**: Track popularity (0-100 scale)

### **Figure 2: Top 100 Most Popular Tracks by Artist**
   <img width="1361" alt="image" src="https://github.com/user-attachments/assets/9669543d-6ef2-440d-bf47-e8faed0b6388">
   - **Legend**: 🗂️ Treemap with block size proportional to track popularity and color-coded by artist
   - **Hierarchy**: Artist → Track

### **Figure 3: Playlist Genre and Subgenre by Popularity and Track Count**
   <img width="1102" alt="image" src="https://github.com/user-attachments/assets/51f7c1e0-bba2-492b-8a7e-6a7bff99a275">
   - **Legend**: Treemap blocks represent genres and subgenres. 🎨 Color gradient indicates average popularity (warmer = lower).  
   - **X-axis**: Genres and Subgenres 

### **Figure 4: *Genre Proportion Across Top 30 Artists**
   <img width="1089" alt="image" src="https://github.com/user-attachments/assets/5368a765-795c-42e4-aa60-86d1968cb9ca">
   - **Legend**: 📊 Stacked bar chart showing the proportion of genres for each artist 
   - **X-axis**: Artist names
   - **Y-axis**: Genre proportion

---

## 🎶 Part 2: Song Features and Keys 🎹 🎶
### **Figure 5**: Comparison of Top 15 Artists in Pop Across Different Keys** 🎼
   <img width="1104" alt="image" src="https://github.com/user-attachments/assets/f9c2d9e0-fe35-4516-a46a-09953841bf12">
   - **Legend**: 📊 Stacked bar chart showing song counts by key for each artist  
   - **X-axis**: Musical keys (C, D, G, etc.)
   - **Y-axis**: Count of songs

### **Figure 6: Popularity vs. Danceability and Tempo (All Genres)** 🥁
   <img width="1090" alt="image" src="https://github.com/user-attachments/assets/66bed53f-b79b-4d86-ab21-f588de25dcf1">
   - **Legend**: 💬 Scatter plot with points representing songs, color-coded by genre 
   - **Left**: Danceability vs. Popularity
   - **Right**: Tempo (BPM) vs. Popularity

### **Figure 7: Popularity vs. Danceability and Tempo for Genre Comparisons** 💃
   <img width="1185" alt="image" src="https://github.com/user-attachments/assets/f194796a-c223-483c-a915-e9ed1d4c3ad0">
   - **Legend**: Scatter plots comparing genres across rows (tempo and danceability) and columns (different genre combinations)

---

## 📊 Summary of Analysis and Business Value
- **Part 1**: Highlights dominant artists, popular tracks, and genre trends. These insights are essential for identifying hitmakers, optimizing playlist curation, and targeting marketing efforts toward trending genres like Pop and EDM while exploring niche genres such as Latin and R&B.
- **Part 2**: Reveals correlations between song features (tempo, danceability, and keys) and popularity. This supports innovative music production, personalized recommendations, and cross-genre experiments to enhance engagement and diversify content offerings.

---

## 🛠️ Data and Methods
The dataset consists of **30,000 Spotify songs**. Analysis methods includes:
- Aggregation methods: Mean, quartiles, and proportions.
- Visualizations: 📊 Boxplots, 🖼️ Treemaps, 💬 Scatter plots, and 📊 Stacked bar charts.
- Filtering: 🎯 Focused on top artists, songs, genres, keys, and audio features.

**Data Source**: [30,000 Spotify Songs | Kaggle]([https://www.kaggle.com/datasets](https://www.kaggle.com/datasets/joebeachcapital/30000-spotify-songs/data))  
**GitHub Repository**: [Link to Repository](https://github.com/jessie7pc/2415FinalProject-30000SpotifySongs/)

