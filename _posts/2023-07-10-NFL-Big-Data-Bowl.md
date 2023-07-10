---
title:  "Personal Projects"
layout: post
---
Included are personal projects that have been submitted to competitions such as the NFL Big Data Bowl and the Horizon Summit. 

## NFL Big Data Bowl (Kaggle)

Using a transfer learning approach, this project leverages player tracking data to create an evaluation metric for offensive linemen during the 2021 NFL season. This project required extensive feature engineering to create useful metrics such as bounding box dimensions, and defender tracking to be used in baseline models. Results were then used to train an additonal model to predict the success of a team according to the created metrics, and can be seen in the plot below. 

<img src="https://github.com/ZGalante/github-portfolio/blob/main/NFL_Big_Data_Bowl_2023/Team_plot.png?raw=true" width="800" height="600">


## Horizon Summit (San Francisco 49ers)

Working alongside college football coaches, I created an end to end machine learning pipeline to predict if an opposing team was going to run or the pass the ball. Data was gathered by scraping the ESPN website for play by play details, which was then used to train a neural network. This pre-trained network was then leveraged to make individual predictions at inference. Coaches were then able to use the created flask application to generate play sheets for a given opponent. 


