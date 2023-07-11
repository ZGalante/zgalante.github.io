---
title:  "Publications and Contests"
layout: post
---
This section features projects that have been publsihed to peer-reviewed journals and submitted to machine learning contests. 

## Hit Song Science

- Fast tracked for journal publication in Volume 22 of the [Issues in Information Systems (IIS)](https://digitalcommons.bryant.edu/cgi/viewcontent.cgi?article=1043&context=cisjou) 
- A related teaching case was published in Volume 20 of [Information Systems Education Journal (ISEDJ)](https://files.eric.ed.gov/fulltext/EJ1351062.pdf)

Adding to the limited amount of 'hit song science' literature, we created a bracket style model to predict if a song would be a hit. This was determined based off the results of the 'Locura de Marzo' tournament, a global tournament where Spanish songs are voted against each other. This was accomplished with metrics aquired from several APIs, including Spotify, Twitter, and YouTube. This included low level features about the song, such as its tempo and acousticness in addition to the song's popularity through platforms such as Twitter and YouTube. After exploring several models, we used a stacked modeling approach with Support Vector Machines to feed the results of one round to the next. Due to the dependencies of a correct prediction, evaluating this type of model proved to be a challenge as well, which was ultimately solved by looking at the number of correct predictions per round. 


## NFL Big Data Bowl (Kaggle)

Using a transfer learning approach, this project leverages player tracking data to create an evaluation metric for offensive linemen during the 2021 NFL season. This project required extensive feature engineering to create useful metrics such as bounding box dimensions, and defender tracking to be used in baseline models. Results were then used to train an additonal model to predict the success of a team according to the created metrics, and can be seen in the plot below. 

<img src="https://github.com/ZGalante/github-portfolio/blob/main/NFL_Big_Data_Bowl_2023/Team_plot.png?raw=true" width="800" height="600">


## Horizon Summit (San Francisco 49ers)

Working alongside college football coaches, I created an end to end machine learning pipeline to predict if an opposing team was going to run or the pass the ball. Data was gathered by scraping the ESPN website for play by play details, which was then used to train a neural network. This pre-trained network was then leveraged to make individual predictions at inference. Coaches were then able to use the created flask application to generate play sheets for a given opponent. 


[Live Demo](https://studio.youtube.com/video/kNb_ZNog_ng/edit)
