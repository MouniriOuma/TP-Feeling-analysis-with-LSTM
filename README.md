# Feeling Analysis with LSTM

This repository contains a Python script for performing sentiment analysis on text data, specifically tweets. It uses a Long Short-Term Memory (LSTM) neural network trained using TensorFlow and Keras.

## Overview

The notebook `TP10.ipynb` implements a sentiment analysis model that categorizes text as either positive or negative. The process includes data loading, preprocessing, tokenization, model building, training, evaluation, and prediction on new text inputs.

## Usage

1. **Prepare the Dataset:**
The code use a dataset named sentiment100k.csv and is located in the same directory as the script. You may need to download this file separately or replace it with a different one you would like to use.
The format of the csv file should be such that the first two columns are the polarity and the text respectively. The other columns will be ignored by the program.
2. **Run the Notebook:**
You can run the jupyter notebook by launching a jupyter environment using jupyter notebook command, and then launching the TP10.ipynb file.
You can also use other interactive python environments to run the file.
3. **View the Output:**
The notebook will print various outputs during execution, including data statistics, training progress, model evaluations and examples of prediction.
