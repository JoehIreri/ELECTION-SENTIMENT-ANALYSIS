
#LOGISTIC REGRESSION MODEL USING TWITTER DATA

This repository contains code for a predictive model that classifies voters based on their Twitter behaviors and interactions. The model is built using Python and various libraries such as TextBlob, pandas, numpy, matplotlib, wordcloud, and plotly.

#Dataset.
The dataset used in this project includes Twitter data related to two political figures: Donald Trump and Joe Biden. The data is stored in separate CSV files (Trumpall2.csv and Bidenall2.csv).

#Data Preprocessing
The following steps were performed for data preprocessing:

#Data loading using pandas.
Sentiment analysis using TextBlob to determine polarity (positive, negative, neutral) of tweets.
Filtering out neutral tweets and updating the dataset accordingly.
Grouping tweets by sentiment and visualizing the sentiment analysis comparison using Plotly.
#Word Cloud Visualization
Word cloud visualizations were generated to represent the most frequent words in the tweets for each political figure:

Trump Word Cloud
Biden Word Cloud
