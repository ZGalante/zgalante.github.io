---
title:  "Machine Learning Projects at Scale"
layout: post
---
This section includes machine learning projects done at scale using tools such as PySpark and Hadoop. 

## Flight Delay Prediction

Working with over 1 billion records with 200 features (1 TB of data), I worked on a team using PySpark to create a modeling pipeline predicting flight delays at scale. This included an intense amount of data preprocessing, as there were several data sources being used and required cleaning, transforming, and joining data. I also created important features such as a personalized page rank graph, and reputation score for each airline. A major consideration during the project was data leakage, and ensuring that no future data was included during training and feature engineering. 

## Spam Detection

This project used Hadoop and low level map reduce concepts to predict an email as being spam. This required creating custom mappers and reducers and orchestrating the communication between them. Using a naive bayes model from scratch, I was able to achieve an F-1 score of 0.88. 



## Brain Tumor Detection
Throughout this project I worked on a team using computer vision concepts to detect if an MRI contained a tumor. We used a dataset of over 4,500 images to construct a convolutional neural network to acheive a recall score of 99%. Shown below is the general architecture of the model used to achieve the described results. The full project repo can be found [here.](https://github.com/ZGalante/github-portfolio/tree/main/Brain_Tumor_Detection)


<img src="https://github.com/ZGalante/github-portfolio/blob/main/Brain_Tumor_Detection/CNN_Architecture.png?raw=true" width="1100" height="500">

