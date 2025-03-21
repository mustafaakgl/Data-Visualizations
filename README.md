# Spotify Top 50 Tracks Analysis
This README provides an overview of the Jupyter Notebook that analyzes Spotify's Top 50 tracks of 2020.
## Project Overview
This project explores Spotify's Top 50 hits of 2020, aiming to identify and quantify factors contributing to their popularity. The analysis involves data cleaning, exploratory data analysis (EDA), and comparison of key audio features across different musical genres.
### Dataset
The dataset contains information about the 50 most streamed tracks on Spotify in 2020, featuring 16 variables:

### Numerical Variables:
* energy (0-1): Higher values indicate more energetic songs
* danceability (0-1): Higher values indicate songs that are easier to dance to
* instrumentalness (0-1): Values closer to 1 indicate songs likely to have no vocals
* valence (0-1): Higher values indicate more positive-sounding songs
* acousticness (0-1): Describes how acoustic a song is
* duration_ms: Length of song in milliseconds (typically 200k-400k)
* liveness (0-1): Likelihood the song was recorded with a live audience
* speechiness (0-1): Detects presence of spoken words in a track
* tempo: Beat speed of the song
* loudness: Higher values indicate louder songs

### Categorical Variables:
* artist
* track_name
* track_id: Identifier in Spotify's system
* key: Primary musical key identifier
* genre
* album

### Notebook Structure
The notebook is structured as follows:

### Setup and Data Loading

Required libraries (pandas, numpy, matplotlib, seaborn, etc.)
Data download and loading function


### Data Cleaning

Dropping unnecessary columns
Checking for and handling missing values
Removing duplicates
Discussion of outlier treatment (with reasoning for not removing outliers)


### Exploratory Data Analysis

Basic dataset statistics
Artist and album distribution analysis
Audio feature analysis (danceability, loudness, etc.)
Genre analysis
Correlation analysis between features
Genre comparisons for key audio features


### Key Insights and Conclusion

Summary of findings about popular artists, genres, and track characteristics
Conclusion about what makes songs popular on Spotify


### Suggestions for Improvement

Recommendations for enhancing the analysis in future iterations



### Key Findings

Billie Eilish was the most popular artist in the dataset
Pop dominated as the most represented genre
High danceability (>0.7) was common among most tracks
Strong positive correlation between energy and loudness
Strong negative correlation between energy and acousticness

### Usage
To run this notebook:

Ensure you have Jupyter Notebook installed
Install required dependencies: pandas, numpy, matplotlib, seaborn, requests
Open the notebook and run cells sequentially

### Future Improvements
Potential enhancements for this analysis:

Include more songs (from different years or expanding the dataset)
Add geographical data for regional analysis
Analyze user engagement metrics (plays, likes, shares)
