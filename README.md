# Google ML Olympiad Hausa Sentiment Analysis

This challenge is part of the ML Olympiad, An associated Kaggle Community Competitions hosted by ML GDEs or TFUGs, sponsored by Google Developers.

A Repo of my solution to the Google Machine Learning OLympiad Competition Hosted on Kaggle 1st Place Solutuion

Position on Leader Board -- 1st (Gold)

To get the Data check the link Below
link -- https://www.kaggle.com/c/hausa-sentiment-analysis

# ML Olympiad - Hausa Sentiment Analysis

Hausa is a Chadic language, a branch of the Afroasiatic language family. It is the most spoken in the family, next to Arabic. Hausa is considered the largest ethnic group in sub-Saharan Africa, with some diverse native speakers who are culturally homogeneous.

Sentiment analysis relies on multiple word senses and cultural knowledge and can be influenced by age, gender and socio-economic status. For this task, we have collected and annotated sentences from different social media platforms.

The objective of this challenge is to develop a multi-class classification model to classify news content according to its specific category. Given a sentence, the task is to classify whether the sentence is of positive (1), negative (-1) or neutral (0) sentiment. For messages conveying more than one sentiment, whichever is the stronger sentiment should be chosen.

## Predict if the text would be considered positive, neutral or negative (for an average user).


## MY Solution Approach
- A Random Forest Model
    - Exploratory Data Analysis removing redundant features
    - Used a RepeatedStratifiedKfold of 5 Splits and repeats of 3 creating 15 splits (To overcome overfitting)
    - Used different Random Forest Parameters based on parameter tunning
    - Hence created 3 models
- Finally created a Blend Model for the 3 Model 

## Experiment that Performed Less
- Using Simple Transformers Classifiers 
- Using Deep Learning (RNN and LSTM)
- Using Catboot and XGBoost (This was attributed to the low dataset sample)
