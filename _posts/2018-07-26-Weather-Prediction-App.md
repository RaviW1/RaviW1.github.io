---
title: "Weather Prediction App"
date: 2018-07-26
layout: post
feature-img: "assets/img/thumbnails/weather_prediction_image.webp" 
thumbnail: "assets/img/thumbnails/weather_prediction_image.webp" 
excerpt_separator: <!--more-->
---

I have converted my Random Forest Algorithm into an iOS app using CoreML.
I used the random forest model and not the autocorrelation model because since I used sklearn
to create the random forest model it was far easier to convert it to the format required for the app.
I followed Brian Advent's LinkedIn course, iOS App Development: Core ML, to convert my model.
I also followed [Matt Mathias' tutorial.](https://www.bignerdranch.com/blog/machine-learning-in-ios-using-core-ml/)
Using both of the courses it was still fairly difficult to build the app.
I was forced to restart Xcode multiple time because of the numerous bugs that I ran into.
Many times the app failed to run and when I searched the error I could not find any 
solutions that didn't require me to go into the files of the application.
Eventually, I got lucky and the app ran without any other problems. I still don't know 
what caused the initial errors.
This was my first programming in Swift and was difficult at first. Due to the fact that
I had to teach myself Swift from the ground up, the code is very convoluted and 
it took me far longer than it should have.
In the end I was able to make a fully functioning app that predicted the weather in Memphis.
I have contemplated revamping the visuals of the app but I think I need to move on from this project.

### A screenshot of the app:
{% include aligner.html images="blog/Weather_App.png" %}