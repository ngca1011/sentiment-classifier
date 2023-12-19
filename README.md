# Sentiment Analysis with deep learning
This repository contains a simple sentiment analysis project using deep learning. The goal is to classify reviews as positive or negative based on their content.

## Overview

In this project, i use an LSTM-based neural network to classify book reviews as either positive or negative based on the review's text and score.

## Implementation

1. Data cleansing: Remove rows with missing values
2. Text preprocessing: Remove data noise like punctuation and numbers, additionally stopwords will also be removed
3. Tokenization and Padding: The text data is tokenized using the Tokenizer from Keras and padded to ensure consistent input lengths.
4. LSTM Model: An LSTM model is constructed using an Embedding layer followed by an LSTM layer and a Dense layer with sigmoid activation for binary classification.
5. Training: The model is trained using the Adam optimizer and binary crossentropy as the loss function.
6. Visualization: Training and validation loss and accuracy are visualized over epochs using matplotlib.
