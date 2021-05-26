---
title: Cassava Leaf Detection Kaggle Competition
author: Ravi Wijeratne
date: '2021-5-26'
layout: post
color: rgb(107,9,0)
excerpt_separator: <!--more-->
---

During my winter break, I took on the Cassava Leaf Detection competition on Kaggle, 
which I thought would be a quick project that would keep me occupied. However, I found out 
I was greatly mistaken. What I thought would be a quick few week project ended up taking me
almost three months. I started the project at the start of my winter break, December 23, and
my last submission was made on the day that the competition ended, February 11. 

Initially, I had hoped I could make a simple model based off the ResNet architecture because I have had
success with that before. These hopes were crushed when I found I could get no more than 70%
accuracy. I then decided I needed a more complex model and decided to use transfer learning.
I decided to use the pre-trained ResNet50 model. To my surprise, This performed worse than my initial
model. I then tried to fine tune my initial model and was able to hit 75% before overfitting.
I then tried both the pre-trained Inception and MobileNet architectures. The Inception model was 
only able to hit 70% without any fine-tuning and I quickly abandoned it. The MobileNet architecture
was able to hit 80% with a lot of fine-tuning but I decided to drop it because I did not think 
I could get any more out of it. So, late in to the competition, I was scrambling to try and
find an architecture that could work. 


I finally stumbled onto the pre-trained EfficientNet model. 
My first test I was able to hit 83% before overfitting. The only problem was, for a reason I have yet
to discern, the model would sometimes decide not to learn and a training session would be wasted, also 
wasting my precious, limited GPU hours. It was the final week of the competition and, furiously rushing, 
I was able to tune the model to get 86%. With my GPU hours gone and the competition coming to 
a close I was able to submit my final model with a score of 0.8611. I got in 
2854th out of 3900 teams, the top team getting a score of 0.9132. 

### A visualization of the model
{% include aligner.html images="blog/model_plot.png" %}


This was my first Kaggle competition
and I was able to learn a lot. If I were able to redo this, I would not have spent as much time 
fine-tuning the MobileNet model as most of it didn't lead anywhere. Overall, I am happy with
this project and I think I learned quite a bit 
{% include aligner.html images="blog/leaderboard.png" %}

I meant to get this post out during February or March but I was still revamping the website
and I didn't finish until March 19th which was the end of my Spring Break. With the end of
the school year I wasn't able to work on any personal projects and I was only able to 
work on this post at the start of summer. I also have a recap of the extended summer, due to
quarantine, of 2020 that I need to post and I hope to post that soon.



