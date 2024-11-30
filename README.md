# spotifyandweatherdata

Music and Weather: ​Analyzing the Impact of Varying Weather on Music Choices

Project Description:
This project investigates the connection between my music listening habits and daily weather. By correlating my Spotify music listening history (obtained through Spotify’s data request feature) with daily weather data, I aim to answer several questions:

How does daily weather affect the types of music I listen to?
Are there any noticeable differences in my listening frequency or duration depending on the weather conditions?

Dataset:
Spotify Data, Spotify API
Source: Spotify data request feature. I will obtain my personal listening history as a JSON file via Spotify Account Privacy Settings.
Features:
track_name: Name of the track.
artist: Artist performing the track.
playback_timestamp: Timestamp of the playback.
audio_features: derived from Spotify’s metadata (energy, valence, tempo).

Weather Data
Source: I will obtain historical weather data using OpenWeather API.
Features:
Temperature, humidity, weather conditions (sunny, rainy, foggy, snowy).
I aim for timestamps to match Spotify listening data.

Project Workflow

Data Collection:

I requested Spotify data using Spotify’s data request feature.
I obtained weather data for relevant time periods and locations using OpenWeather API.

Data Preprocessing:

I will parse Spotify JSON files to extract relevant features (track name, play time).

I will combine Spotify data with weather data using timestamp alignment.

Exploratory Data Analysis (EDA):

I will visually present trends in my listening preferences across different weather conditions.
Relationships between audio features (energy, tempo) and weather measurements (temperature, rain) will be revealed.

Documentation and Reporting:

Visualizations were created to showcase the insights.
I will compile the relationships found into a comprehensive report.

Project Goals:

Understanding Patterns: Discover how an external factor, weather, affects my personal music habits.

Tools and Libraries Used:
Programming Language: Python
Libraries:
Data Processing: pandas, numpy
Visualization: matplotlib, seaborn, plotly
Machine Learning: scikit-learn
Weather Data Retrieval: requests, json

Key Visualizations and Findings (To Be Updated):
Genre Trends by Weather: Bar charts showing how weather affects genre preferences.
Mood Score Analysis: Scatter plots that relate Spotify audio characteristics like energy and value to weather data.
Listening Habits Over Time: Time-series analysis of listening frequency across seasons.
