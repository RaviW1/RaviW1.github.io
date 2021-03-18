---
title: Music Generation Project
author: Ravi Wijeratne
date: '2020-07-16'
layout: post
feature-img: "assets/img/thumbnails/sheet_music.webp" 
thumbnail: "assets/img/thumbnails/sheet_music.webp" 
excerpt_separator: <!--more-->
---
I took on a small project this year. I wanted to work more on neural networks so I attempted to create one that generated music. 
I used a dataset of midi versions of mozart's music. 
In order to create the algorithm I utilized this [tutorial](https://www.analyticsvidhya.com/blog/2020/01/how-to-perform-automatic-music-generation/). 
This tutorial helped me understand how to work with midi data, which I have never worked with before. 
I used a modified version of the WaveNet Architecture for my model. One problem I ran into, was the model tended to return a long run of the same note most of the time. 
So in the end, it would, only half the time, generate a good song. In the future, I want to make the model more complex in the future and train it with more data.
### Here is one of the better pieces of generated music:
<html>
<audio controls>
  <source src="{{ "/assets/audio/music-3.ogg" | relative_url}}" type="audio/ogg">
</audio>
</html>


thumbnail and header photo by Scott Kelley from Unsplash