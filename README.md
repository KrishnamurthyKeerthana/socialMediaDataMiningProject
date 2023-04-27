#Twitter Sentiment Analysis

This is a Python program that uses the Tweepy library to fetch tweets containing specified search terms, performs sentiment analysis on them using the TextBlob and SentimentIntensityAnalyzer libraries, and produces a CSV file with the results. The program then reads the CSV file, counts the number of positive and negative tweets for each brand and location, and generates bar charts and word clouds to visualize the data.

#Getting Started

#Prerequisites

Python 3.x
Tweepy library
TextBlob library
SentimentIntensityAnalyzer library
pandas library
matplotlib library
wordcloud library
nltk library

#Installing

#Install Python 3.x from the official website: https://www.python.org/downloads/

Install the required libraries using pip:

pip install tweepy textblob pandas matplotlib wordcloud nltk

Usage
Replace the values of the consumer_key, consumer_secret, access_token, and access_token_secret variables in the code with your own Twitter API credentials.
Modify the search_words and geocodes variables in the code to specify the search terms and locations you want to use.

Run the code with the following command
python walmart.py

The program will generate CSV files and visualizations in the same directory as the code.

Authors
Keerthana Krishnamurthy and Bhumika Murali

License

