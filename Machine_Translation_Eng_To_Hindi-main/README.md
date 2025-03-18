# Hindi to English Translation using Transformer Model

This repository contains a Transformer model implementation for translating text from Hindi to English. 
The model is based on the architecture introduced in the paper "Attention is All You Need" by Vaswani et al. and is implemented using TensorFlow and Keras.



## Introduction

The goal of this project is to build a machine translation model that can accurately translate sentences from Hindi to English using a Transformer architecture. 
Transformers have become the state-of-the-art in many NLP tasks due to their ability to handle long-range dependencies and parallelize training.

## Model Architecture

The model consists of an encoder and a decoder, both of which are implemented using the Transformer architecture. The key components of the model include:

- **Multi-Head Attention**: Allows the model to focus on different parts of the input sentence for different purposes.
- **Positional Encoding**: Adds information about the position of the words in the sentence.
- **Feed-Forward Neural Networks**: Processes the output from the attention layer.
- **Layer Normalization and Dropout**: Used for regularization and improving training stability.

## Dataset

The dataset used for training and evaluating the model consists of Hindi-English sentence pairs.
The data was sourced from Kaggle and contains 300,000 sentence pairs, with a maximum sentence length of 10 words.
Each sentence pair is tokenized and preprocessed to add special `<start>` and `<end>` tokens.
