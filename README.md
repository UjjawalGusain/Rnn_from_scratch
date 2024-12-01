# MyRNN: A Simple Recurrent Neural Network for Sentiment Analysis

## Overview

This is a **dummy project** created for practice, where a simple RNN model is trained to classify text sentiment (positive or negative) based on one-hot encoded input. The dataset used here is small and artificial, so the model will overfit the data. This project is intended for learning and practicing basic concepts in deep learning and RNNs.

## Project Description

The goal of this project is to build a simple RNN model using PyTorch to perform sentiment analysis on text data. The input text is tokenized and one-hot encoded before being passed to the RNN for training. The sentiment is classified into binary classes (positive or negative).

### Key Steps:
1. **Data Preprocessing**:
   - Tokenization of the text into words.
   - One-hot encoding of words using PyTorch.
   - Padding sequences to make them of equal length.
   
2. **Model Building**:
   - A simple RNN model with a linear input layer, a recurrent layer, and a final output layer.
   - The model uses Tanh as the activation function for hidden states and Sigmoid as the activation for the output layer.

3. **Training**:
   - The model is trained using a dummy dataset with a small number of text samples.
   - Loss is computed using Binary Cross-Entropy, and the model is trained for several epochs.

4. **Evaluation**:
   - The model’s performance can be evaluated on the small dataset, but overfitting is expected due to the limited size of the data.

