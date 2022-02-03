---
title: AI for Healthcare
author: Ravi Wijeratne
date: '2022-1-15'
layout: post
color: rgb(107,9,0)
excerpt_separator: <!--more-->
---

During the beginning of the pandemic I engaged in multiple Udacity Courses
This  is a summary of the AI for Healthcare course and what I learned from it.

## AI for Healthcare

In this course, I learned how to utilize machine learning techniques for health care
data. 
The first project was a CNN that used chest X-rays to diagnose pneumonia.

For this project,
I learned alot about how machine learning can be applied for health care purposes. This
project covered the types of error, the steps involved in getting a model approved by the FDA, 
and how to properly handle sensitive medical data. The actual model generated was not
particularly powerful, however with some continued work it could be made very robust.

### A visualization of the model's performance
{% include aligner.html images="blog/model_performance.png" %}

The next project I undertook was using MRI scans for Hippocampus Segmentation. This was my
first experience utilizing three dimensional data or MRI scans in general. The UNet-based
model was coded using Pytorch, a library I had very little familiarity with. The whole
project was very new to me and I learned a significant amount. In the future, I want to
do some more experimentation with the UNet architecture and explore what problems I can
apply it to.

### A visualization of the segmentation model's training performance
{% include aligner.html images="blog/P2_model_performance.png" %}S

The next project was to build a regression model that predicted expected hospitalization
time for a patient being given an experimental diabetes drug. This was then used to decide whether 
or not they should be included in the clinical trials. The data set was a synthetic and the
real challenge was the preprocessing and analysis of the dataset rather than the model building.
It was very challenging working with a medical dataset which required a considerable amount
of preprocessing, feature engineering, and filtering. I also learned how to deal with model
bias for demographic groups and how to mitigate these. This project was very informative on
how to work with medical data and how to analyze a model based on that data.

### A visualization of the model's biases
{% include aligner.html images="blog/model_biases.png" %}
This model shows significant bias towards Caucasians and African-Americans. There is also 
a bias towards women over men.

The final project was utilizing data, in this case heart rate, from wearables. This project used
data I was very inexperienced with handling. Preprocessing and analyzing the data was very
difficult. I was able to complete the project and I learned a lot from the experience.


Overall, this course introduced me to many new data types and introduced me to the 
possible implementations of machine learning technology in the health care industry. I 
also learned how to handle sensitive health care data, the impact of model bias based on
demographics, the intricacies of the FDA approval process, and the types of errors and metrics
to consider in a health care setting. 