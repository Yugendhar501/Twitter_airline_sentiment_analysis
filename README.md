# Twitter sentiment analysis using python streamlit

## Tweet Sentiment Analysis App:
This is a Streamlit web application for performing sentiment analysis on airline-related tweets. The app allows users to explore and visualize sentiments from customer tweets about various airlines. It provides interactive filtering, data visualization, and tweet exploration.

## Features:
### Display and Explore Tweets:

Load and display the first 50 rows of the dataset (Tweets.csv) containing airline-related tweets.
Filter tweets by sentiment (positive, negative, or neutral) and view random tweets from the selected sentiment category.

## Sentiment Visualizations:

View sentiment distribution using either a Histogram or a Pie Chart.
The Histogram shows the number of tweets for each sentiment (positive, negative, or neutral).
The Pie Chart shows the percentage distribution of each sentiment.

## Tweets by Time and Location:

Filter tweets based on the hour of the day using a slider.
Visualize the number of tweets posted during a specific hour and plot the locations of those tweets on a map.

## Airline-Specific Sentiment Analysis:

Select specific airlines (e.g., US Airways, United, American) and view a sentiment breakdown for the selected airlines using a histogram.

## Libraries Used:

Streamlit: For building the web interface.
Pandas: For data manipulation and filtering.
Plotly Express: For interactive visualizations like histograms and pie charts.
Matplotlib: Imported but not used in the code (optional for additional visualizations).
Numpy: Imported but not used in the code (optional for numerical analysis).
