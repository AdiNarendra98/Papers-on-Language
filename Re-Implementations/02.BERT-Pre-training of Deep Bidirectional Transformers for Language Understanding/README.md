# Twitter Sentiment Analysis using BERT 

## Introduction

Sentiment Analysis, also known as Opinion Mining and Emotion AI, is an algorithm used to determine the opinions of the masses about a specific topic. With the growth of social medias, blogs, discussion forums, online review sites, etc. major companies have come to realize that being sentiment-aware can help them gain insights into user behavior, track and manage their online presence and image and use that information to boost brand loyalties and advocacy, marketing message, product development, monitor competitive intelligence, etc. As of 2021, the world has 3.78B social media users (53.6% of the world's population) who spend an average time of 2.5 hours per day (Chaffey, 2021).

In this project we will build a Sentiment Classifier using BERT (Bidirectional Encoders Representations from Transformers) which is both a contextual and (the first ever) bidirectional language model. BERT is an open-source NLP pre-training model developed by the Google AI Language team in 2018. It is considered the most ground-breaking development in the field of NLP and is often compared to the ImageNet moment in Computer Vision.


<p align="center">
<img src="https://github.com/AdiNarendra98/Papers-on-Language/blob/main/Re-Implementations/02.BERT-Pre-training%20of%20Deep%20Bidirectional%20Transformers%20for%20Language%20Understanding/Images/BERT1.png" width="450" height="440"><br>
<b>Working Structure of BERT</b><br>
</p>

## Dataset

- [**SMILE Twitter**](https://www.kaggle.com/ashkhagan/smile-twitter-emotion-dataset): This is acollection of tweets mentioning 13 Twitter handles associated with British museums was gathered between May 2013 and June 2015. It was created for the purpose of classifying emotions, expressed on Twitter towards arts and cultural experiences in museums.
- It contains **3,085 tweets, with 5 emotions namely anger, disgust, happiness, surprise, sadness and the 6th label being not-relevant**.

<p align="center">
<img src="https://github.com/AdiNarendra98/Papers-on-Language/blob/main/Re-Implementations/02.BERT-Pre-training%20of%20Deep%20Bidirectional%20Transformers%20for%20Language%20Understanding/Images/df_full.png" width="500" height="300"><br>
<b>Sample Records from Dataset</b><br>
</p>

<p align="center">
<img src="https://github.com/AdiNarendra98/Papers-on-Language/blob/main/Re-Implementations/02.BERT-Pre-training%20of%20Deep%20Bidirectional%20Transformers%20for%20Language%20Understanding/Images/df.png" width="450" height="500"><br>
<b>Distribution of Dataset w.r.t to Labels</b><br>
</p>

## Prediction

<p align="center">
<img src="https://github.com/AdiNarendra98/Papers-on-Language/blob/main/Re-Implementations/02.BERT-Pre-training%20of%20Deep%20Bidirectional%20Transformers%20for%20Language%20Understanding/Images/prediction.png" width="300" height="500"><br>
<b>Sample Results</b><br>
</p>

## Future Work

* Add additional hidden layers on top of BERT-base
* Build a custom classifier.
* Correct class imbalance.
