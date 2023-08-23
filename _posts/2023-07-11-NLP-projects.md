---
title:  "Natural Language Processing Projects"
layout: post
---
Below are projects using Natural Language Processing and Generative AI. Subjects range from text classification using a pre-trained BERT model to summarization with T-5.

## Hate Speech Moderation 
During this project I worked on a team conducting research on how to classify hateful tweets. We learned that this problem had been attempted in the past using traditional machine learning models, but saw the opportunity to apply modern architectures. We fine-tuned foundation models such as BERT and BERTweet to understand the parts of a tweet that would signify hate. We found that the learned BERT embeddings combined with a convolutional neural network proved to be one of our best models, achieving a ROGUE score of 0.539. Finally, we visualized the model's attention to understand it's performance and help improve classifications, as shown below. 

The full paper can be found [here](https://github.com/ZGalante/zgalante.github.io/blob/master/assets/Moderating%20Hate%20Speech%20on%20Social%20Media.pdf). Please be warned that it does include hateful text found in tweets. 

<img src="https://github.com/ZGalante/zgalante.github.io/blob/master/assets/Attention_visualization.png?raw=true" width="900" height="300">

## IMDB Movie Review Classification

This project uses embeddings from a pre-trained BERT model to perform sentiment analysis on movie reviews. This was accomplished using a BERT model as a baseline, and then passing the learned embeddings to a convolutional neural network for classification. 

## Synonym Detection
In this project I used PySpark to conduct synonym detection on Google's n-gram corpus by using several similarity metrics, such as Overlap, Dice, Cosine, and Jaccard. Due to the size of the corpus, this project relied on optimization strategies such as inverted indices to illistrate co-occurence. 

## Summarization 

Building off foundational knowledge of transformers and large language models, this project uses the T-5 encoder-decoder model to summarize news articles. After tokenizing inputs, the model was able to achieve a rougeL score of 0.31. 

