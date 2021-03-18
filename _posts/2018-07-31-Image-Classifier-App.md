---
title: "Mushroom Image Classifier iOS App"
date: 2018-07-31
layout: post
feature-img: "assets/img/thumbnails/mushroom_images.webp" 
thumbnail: "assets/img/thumbnails/mushroom_images.webp" 
excerpt_separator: <!--more-->
---

I made a iOS app that can detect if an image has a mushroom in it.
I followed [Jameson Toole's tutorial.](https://hackernoon.com/building-not-hotdog-with-turi-create-and-core-ml-in-an-afternoon-231b14738edf)
I built the model in Python using Turi Create. Unlike Keras or Pytorch, Turi Create does
most of the work for you. This allowed me to create a model quickly, however, I did 
not get the control I would have gotten using Keras or the satisfaction of building the 
model myself. One advantage of using Turi Create is that it, unlike Keras, allows 
me to utilize the GPU of my Mac, however, because the model was so simple, it didn't 
take a long time to train on my CPU. It is also very easy to port the resulting model to Xcode.
I also used Vision and CoreML to convert it into an app.
This project was very simple and I hope to, in the future, build a more complex image classifier.
The app works pretty well and has a 95.7% accuracy.


### Images of the app:

{% include aligner.html images="blog/mushroom_app.png" %}

{% include aligner.html images="blog/not_mushroom.png" %}

thumbnail and header photo by Slawek K on Unsplash