# Spotify Top Tracks 2023 Data Analysis

## Project Overview

This project involves the analysis of Spotify's Top Tracks for the year 2023 using R. The goal of the analysis is to gain insights into the trends, patterns, and characteristics of popular music in 2023. The project includes data collection, preprocessing, exploratory data analysis (EDA), and visualization.

## Table of Contents

- [Project Overview](#project-overview)
- [Objectives](#objectives)
- [Data Collection](#data-collection)
- [Installation and Setup](#installation-and-setup)
- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Results and Insights](#results-and-insights)
- [Conclusion](#conclusion)
- [Acknowledgments](#acknowledgments)
- [Contact](#contact)

## Objectives
The primary goals of this analysis are:

-To identify recurring themes and traits in the top tracks of 2023.
-To explore the relationship between explicit content and track popularity.
-To analyze the distribution of track durations and other numerical features.
-To investigate correlations between musical attributes such as valence, energy, and danceability.
-To understand the distribution of musical genres and their popularity.

## Data Collection

The dataset used in this project was obtained from Spotify's public API. It includes various features for each track such as:

- Track Name
- Artist
- Album
- Release Date
- Popularity
- Danceability
- Energy
- Loudness
- Speechiness
- Acousticness
- Instrumentalness
- Liveness
- Valence
- Tempo
- Duration (ms)

## Installation and Setup

To replicate this analysis, you need to have R and RStudio installed on your machine. Additionally, you need to install the following R packages:

```R
install.packages(c("tidyverse", "spotifyr", "ggplot2", "dplyr", "lubridate", "scales", "readr"))
```

## Data Preprocessing

Data preprocessing involved the following steps:

1. **Loading Data**: Using the `spotifyr` package to retrieve data from Spotify API.
2. **Cleaning Data**: Removing duplicates, handling missing values, and converting data types.
3. **Feature Engineering**: Creating new features such as track length in minutes and extracting year from the release date.

## Exploratory Data Analysis

The exploratory data analysis (EDA) was conducted to understand the distribution and relationships of various features in the dataset. Key analyses included:

- Distribution of track popularity
- Analysis of audio features (danceability, energy, valence, etc.)
- Top artists and their most popular tracks
- Release trends over the year
- Correlation between different audio features

### Visualizations

Several visualizations were created to illustrate the findings:

- Histograms and density plots for audio features
- Bar plots for the top artists and tracks
- Line plots for trend analysis over time
- Scatter plots to show relationships between audio features

## Results and Insights

Some of the key insights from the analysis are:

- Most popular tracks tend to have high danceability and energy.
- There is a strong positive correlation between energy and loudness.
- Certain artists consistently produce popular tracks.
- Popular tracks are more likely to have a higher tempo and positive valence.

## Conclusion

This analysis provides a comprehensive overview of the musical landscape of 2023, as reflected in Spotify's "Top Tracks of 2023" playlist. By examining explicit content, track durations, musical attributes, and genre popularity, we gain valuable insights into the trends and preferences shaping the music industry. This project not only showcases the power of data in understanding cultural phenomena but also highlights the evolving nature of music consumption in the digital age.
