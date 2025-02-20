#IMDB Sentiment Analysis with RNN

This project uses a Recurrent Neural Network (RNN) to classify movie reviews from the IMDB dataset as positive or negative. The dataset is preprocessed and tokenized, and the model is trained to predict sentiment based on the text of the reviews.

##Dataset Overview
The IMDB dataset consists of 50,000 movie reviews gathered from the IMDB website. It is divided into 25,000 reviews for training and 25,000 reviews for testing, making it a balanced dataset with an equal number of positive and negative reviews.

Key features of the dataset:

- **Labels**: The reviews are labeled as either positive (1) or negative (0).
- **Text**: The content of the movie reviews, written in natural language, is the feature that the model learns to process.
- **Preprocessing**: The text data is tokenized, with words mapped to unique integer values. The vocabulary size is set, and - reviews are padded to ensure consistent input length to the model.

The dataset is publicly available and is commonly used for sentiment analysis tasks.

##Project Overview
The goal of this project is to build a simple RNN model to classify movie reviews from the IMDB dataset into two categories: positive and negative. The model is trained using TensorFlow and Keras, leveraging the power of recurrent layers to understand the sequence of words in the reviews.

Requirements
Python 3.x
TensorFlow
Numpy
Matplotlib (for visualizations)
