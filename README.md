# Image Captioning
Generating image captions using encoder-decoder deep neural network

<b>Click on the image to open Youtube video</b><br>
[![IMAGE ALT TEXT HERE](_includes/youtube_ss.png)](https://www.youtube.com/watch?v=fblhQTDh7lY)


## Contents
* [Overview](#overview)
* [Motivation](#motivation)
* [Dataset](#dataset)
* [Setup](#setup)
* [Repository files](#repository-files)
* [Model](#model)
* [What did I learn](#what-did-i-learn)

## Overview


## Motivation


## Dataset
The dataset was downloaded from Kaggle<br>
Website: [Flickr 8k Dataset](https://www.kaggle.com/datasets/adityajn105/flickr8k)

About dataset: A new benchmark collection for sentence-based image description and search, consisting of 8,000 images that are each paired with five different captions which provide clear descriptions of the salient entities and events. … The images were chosen from six different Flickr groups, and tend not to contain any well-known people or locations, but were manually selected to depict a variety of scenes and situations

## Setup
Performed on Kaggle Notebook


## Repository files
emotion_detection_text_dataset  : contains dataset (both original and after pre processing)
<br>saved_model_text_classification : saved TensorFlow model
<br>emotion_detection_2.ipnyb       : jupyter notebook 
<br>model_layers.png                : image for training model used
<br>text_cleaning.py                : custom python function to clean data for efficient tokanization
<br>

## Model
Architechture of the VGG16 model used as encoder<br>
<p align="center">
  <img src="_includes/vgg16_layers.png" width="400">
</p>

Architechture of the LSTM model used as decoder<br>
<p align="center">
  <img src="_includes/lstm_layers.png" width="600">
</p>

## What did I learn?
#### Problem: 
Solution:<br>

#### Problem: 
Solution:<br>
