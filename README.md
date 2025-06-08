Twitter-Sentiment-Analysis-Project
Objective

Our main objective is to develop machine learning model that can accurately classify tweets as either positive, negative, or neutral based on their content. Sentiment analysis has a wide range of applications, from understanding public opinion to brand monitoring and beyond. We'll try to perform different EDA, Data Preprocessing, Encoding, Embedding and Neural Network Techniques to execute the project.

Dataset

We will be using a dataset containing tweets collected from Twitter. The dataset includes text, as well as labels indicating the sentiment associated with each tweet. The labels could be 'positive', 'negative'. Positive denoted by 4 and negative by 0. This dataset is having around 1.6 Million Tweets. The dataset is perfetly balanced i.e it has 800k tweets with positive and 800k tweets of negative sentiments.

Notebook Structure

This notebook is structured as follows:

Exploratory Data Analysis
1.1) Loading the dataset

1.2) Data cleaning

1.3) Label distribution

1.4) Creating Word Cloud

1.5) Creating word length distribution

Data Preparation for Model Building
2.1) Loading the Dataset

2.2) Data cleaning

Trying different Neural Networks
3.1) Splitting dataset into training/testing and validation

3.2) One Hot Encoding + model training

3.3) Count Vectoriser + model training

3.4) TF-IDF + model training

3.5) ANN with Text Sequences

3.5.1) Loading the dataset

3.5.2) Cleaning the dataset

3.5.3) Text encoding

3.5.4) Training the model

3.6) ANN + Embedding with Text Sequences

3.7) RNN + Embedding with Text Sequences

3.8) LSTM + Embedding with Text Sequences

3.9) GRU + Embedding with Text Sequencess
