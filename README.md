Project Readme
Sentiment Analysis and Word Cloud Generation
This repository contains two Jupyter Notebooks demonstrating sentiment analysis using TextBlob and word cloud generation using WordCloud and matplotlib.

Notebooks
1. sentiment analysis python.ipynb
This notebook performs sentiment analysis on a dataset of sentences and visualizes the most common words in negative sentiments using a word cloud.

Features
Installs necessary libraries (TextBlob, WordCloud).

Reads a CSV file containing sentences for sentiment analysis.

Defines a function to classify sentiment as positive, negative, or neutral.

Applies sentiment analysis to the dataset.

Filters and combines negative sentences.

Generates and displays a word cloud of common words in negative sentences.

Usage
Ensure you have the required libraries installed. If not, the notebook includes !pip install TextBlob and !pip install WordCloud commands.

Place your sentiment analysis data in a CSV file named Sentiment_Analysis .csv in the same directory as the notebook. The CSV should have a column named "Sentences".

Run all cells in the sentiment analysis python.ipynb notebook.

2. wordcloud.ipynb
This notebook generates a word cloud from movie plot summaries based on a specific director's name.

Features
Installs necessary libraries (pandas, matplotlib.pyplot, TextBlob, WordCloud).

Reads a CSV file containing movie plot data.

Prompts the user to enter a director's name.

Filters movie data to include only movies directed by the specified director.

Combines all plot summaries for the selected director into a single string.

Generates and displays a word cloud of common words in the director's movie plots.

Usage
Ensure you have the required libraries installed. The notebook imports pandas, matplotlib.pyplot, textblob, and wordcloud.

Place your movie plots data in a CSV file named wiki_movie_plots.csv in the same directory as the notebook. The CSV should have a column named "Director" and "Plot".

Run all cells in the wordcloud.ipynb notebook. You will be prompted to "Enter the director name".
