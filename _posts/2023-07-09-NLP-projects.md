---
title:  "Natural Language Processing Projects"
layout: post
---
Below are projects using natrual language processing. Subjects range from text classification using a pre-trained BERT model to summarization with T-5.

## IMDB Movie Review Classification

This project uses embeddings from a pre-trained BERT model to perform a sentiment analysis on movie reviews. This was accomplished using a BERT model as a baseline, and then passing the learned embeddings to a convolutional neural network for classification. 

## Synonym Detection
In this project I used PySpark to conduct synonym detection on Google's n-gram corpus by using several similarity metrics, such as Overlap, Dice, Cosine, and Jaccard. Due to the size of the corpus, this project relied on optimization strategies such as inverted indices to illistrate co-occurence. 

## Summarization 

Building off foundational knowledge of transformers and large language models, this project uses the T-5 encoder-decoder model to summarize news articles. After tokenizing inputs, the model was able to achieve a rougeL score of 0.31. 

