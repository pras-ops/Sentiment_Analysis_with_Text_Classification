# Sentiment Analysis with Text Classification

This project is aimed at predicting the sentiment of a given text and classifying it as positive, negative, or neutral in nature. The project utilizes various natural language processing techniques and machine learning algorithms to achieve this task. The README.md file provides an overview of the project and its components.

## Project Components

The project consists of the following major components:

### 1. Importing Necessary Libraries

This section imports the required libraries for data processing, visualization, and machine learning.

### 2. Loading Data

The project loads the text data from the file "TextAnalytics.txt" and stores it in a variable called "text".

### 3. Text Normalization

Text normalization is performed to transform the text into a canonical form. This includes operations like removing special characters, tokenization, converting to lowercase, removing contractions, and lemmatization.

### 4. Data Cleaning

The data is cleaned by removing unnecessary columns and additional characters present in the dataframe.

### 5. Visualization

The project visualizes the data by creating a word cloud and bar graph to show the most common words in the text.

 1. Visualizing the highest repeating words in the dataframe using the wordcloud
 2. Top 10 repeated/common words using bar graph




### 6. Sentiment Analysis

Sentiment analysis is performed using the VADER (Valence Aware Dictionary and sEntiment Reasoner) sentiment analysis tool. It calculates the sentiment polarity of each word and assigns it as positive, negative, or neutral. The project provides the top positive and negative words found in the dataset.

### 7. Findings

The project analyzes the sentiment scores for each sentence and identifies the most important, positive, and negative sentences based on the compound, positive, and negative scores. It also assigns a sentiment label (positive, negative, or neutral) to each sentence using threshold values.

### 8. Text Classification

Text classification is performed using a logistic regression model. The project uses the TF-IDF vectorizer to convert the text data into numerical features and trains a logistic regression classifier. The accuracy of the model is evaluated on the train and test sets.

## Usage

To use this project, follow these steps:

1.  Ensure that you have the necessary libraries installed. You can install them using pip or conda.
2.  Place your text data in a file named "TextAnalytics.txt" in the same directory as the code.
3.  Run the code in a Python environment.

## Conclusion

This project demonstrates how to perform sentiment analysis on text data using natural language processing techniques and machine learning algorithms. It provides insights into the sentiment of the text and classifies it as positive, negative, or neutral. The project can be extended and customized for different text classification tasks and datasets.
