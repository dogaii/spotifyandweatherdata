Spotify and Weather Data: 
WEBSITE: https://dogaii.github.io/
Analyzing the Impact of Varying Weather on Listening Habits
Project Description
This project investigates the connection between my music listening habits and daily weather conditions. By correlating 1 year of Spotify music listening history with 1 year of weather data, I aim to understand how external factors such as temperature and precipitation affect personal music habits.
Dataset
Spotify Data
Source: Spotify data request feature
Features:
track_name: Name of the track
artist: Artist performing the track
playback_timestamp: Timestamp of the playback
ms_played: Total playback duration in milliseconds
Weather Data
Source: Visual Crossing Weather API
Features:
avg_temp: Daily average temperature (°C)
precipitation: Daily precipitation levels (mm)
weather_condition: Categorized as Sunny, Rainy, Cold, or Hot, based on temperature and precipitation thresholds


Project Workflow
1. Data Collection
Spotify data was requested using Spotify’s privacy settings.
Historical weather data for the corresponding dates and locations was fetched using the Visual Crossing API.
2. Data Preprocessing
Parsed Spotify JSON files with columns to extract playback features such as track name, artist, and listening time.


Spotify and weather data were combined with timestamp alignment.
Weather conditions were categorized based on temperature and precipitation thresholds.

3. Exploratory Data Analysis (EDA)
Analyzed listening time and frequency under changing weather conditions.
Seasonal trends and changes in listening habits were examined.
4. Documentation and Reporting
Created visualizations to showcase trends and insights.
Compiled findings into a detailed report to summarize key observations.

Project Goals
The primary goal was to investigate how changing weather conditions, such as temperature and precipitation, affect the frequency of music listening.

Tools and Libraries Used
Programming Language
Python
Libraries
Data Processing: pandas, numpy
Visualization: matplotlib, seaborn, wordcloud
Data Retrieval: requests, json

Key Visualizations and Findings
Key Visualizations
Bar Charts: Displayed total listening duration under different weather conditions (Sunny, Rainy, Cold, Hot).
Heatmap: Showed the correlation between average temperature, precipitation, and listening duration.
Boxplots: Highlighted the distribution of daily listening duration across weather conditions.
2D Density Plot: Visualized the relationship between average temperature and playback duration.
Hexbin Plot: Represented point density for temperature versus listening duration.
Scatter Plots: Illustrated the relationship between weather metrics and listening behavior, with regression lines to identify trends.
Time-Series Line Plots: Tracked seasonal changes in listening habits over the year.
Findings
Weather Effects:

Listening times were highest on sunny days, followed by rainy weather.
Rainy weather also showed significant amounts of listening, likely related to indoor activities and increased comfort-seeking behaviors.

Temperature Trends:

As shown in the graphs, greater play times were observed during moderate temperatures (e.g., spring and fall).

Seasonal Listening Behavior:

Play times tended to be consistent with periods of favorable or stable weather conditions rather than extreme climates.



