---
title:  "Publications and Contests"
layout: post
---
This section features projects that have been publsihed to peer-reviewed journals and submitted to machine learning contests. 

## Hit Song Science

- Fast tracked for journal publication in Volume 22 of the Issues in Information Systems (IIS)

- A related teaching case was published in Volume 20 of Information Systems Education Journal (ISEDJ)

Adding to the limited amount of 'hit song science' literature, we created a bracket style model to predict if a song would be a hit. This was determined based off the results of the 'Locura de Marzo' tournament, a global tournament where Spanish songs are voted against each other. This was accomplished with metrics aquired from several APIs, including Spotify, Twitter, and YouTube. This included low level features about the song, such as its tempo and acousticness in addition to the song's popularity through platforms such as Twitter and YouTube. After exploring several models, we used a stacked modeling approach with Support Vector Machines to feed the results of one round to the next. Due to the dependencies of a correct prediction, evaluating this type of model proved to be a challenge as well, which was ultimately solved by looking at the number of correct predictions per round. 
