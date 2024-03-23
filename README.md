# Twitter Sentiment Analysis Project

## Overview

This project aims to perform sentiment analysis on Twitter data related to two political figures, Donald Trump and Joe Biden. The sentiment analysis is carried out using the TextBlob library to determine the polarity (positive, negative, or neutral) of tweets. The project includes data preprocessing, sentiment analysis visualization, and model training for sentiment classification.

## Project Structure

The project is organized into the following main components:

1. **Data Collection**:
   - CSV files containing Twitter data for Donald Trump (`Trumpall2.csv`) and Joe Biden (`Bidenall2.csv`) are used for analysis.

2. **Sentiment Analysis**:
   - Sentiment analysis is performed using the TextBlob library to analyze the sentiment of individual tweets.
   - The sentiment polarity (positive, negative, neutral) is determined based on the sentiment scores.

3. **Data Visualization**:
   - Plotly is used to create bar charts comparing the sentiment analysis results for Trump and Biden.
   - Word clouds are generated to visualize common words in Trump and Biden's tweets.

4. **Model Training**:
   - Scikit-learn's CountVectorizer is utilized to convert text data into numerical vectors.
   - A Logistic Regression model is trained on the preprocessed data to classify sentiment.

5. **Model Deployment**:
   - The trained sentiment analysis model is saved using joblib for future use.

## Getting Started

To run the project locally, follow these steps:

1. Clone the repository to your local machine.
2. Install the required Python libraries listed in `requirements.txt`.
3. Ensure the CSV files (`Trumpall2.csv` and `Bidenall2.csv`) containing Twitter data are available in the specified location.
4. Run the Python script `sentiment_analysis.py` to perform sentiment analysis, visualize results, and train the sentiment analysis model.

## Dependencies

The project relies on the following Python libraries:

- pandas
- numpy
- matplotlib
- wordcloud
- TextBlob
- plotly
- scikit-learn

Install these dependencies using `pip install -r requirements.txt` before running the project.

## Usage

- Modify the file paths in the script `sentiment_analysis.py` if your CSV files are located in different directories.
- Adjust any parameters or settings as needed for data preprocessing, visualization, or model training.


