ReviewSentimentAnalyzer

🔍 Sentiment Analysis of Product Reviews using TextBlob

This project analyzes product reviews from a small dataset and classifies them into Positive, Negative, or Neutral sentiments. It also visualizes the overall sentiment distribution.

Features

✅ Analyze sentiment of product reviews

✅ Calculate polarity scores for each review

✅ Classify reviews into Positive, Negative, or Neutral

✅ Visualize sentiment distribution using a count plot

Installation

Make sure you have Python installed (3.8+) and then install the required libraries:

pip install pandas textblob matplotlib seaborn


Note: You may need to download TextBlob’s NLTK corpora:

import nltk
nltk.download('punkt')

Usage

Prepare your dataset with columns:

Product – Product name

Review – Review text

Run the Python script:

python review_sentiment.py


The script will:

Display the dataset with sentiment classification and polarity scores

Show a count plot of Positive, Negative, and Neutral reviews

Dataset Example
Product	Review	Sentiment	Polarity
Book	Absolutely loved it! Very useful and well-written.	Positive	0.75
Laptop	Terrible performance, it kept crashing!	Negative	-0.8

(The script can be adapted to larger datasets.)

Visualization

Sentiment Distribution – Displays the count of Positive, Negative, and Neutral reviews.
