# Portfolio

## Classification 
### Financial Distress Prediction

Credit scoring algorithms, which make a guess at the probability of default, are the method banks use to determine whether or not a loan should be granted. In this Kaggle competition, participants was required to improve on the state of the art in credit scoring, by predicting the probability that somebody will experience financial distress in the next two years.

To tackle this problem, I implemented several models and compared them to find out which one got the best score (AUC). After fine tune the winner, I used SHAP to explain which features were most important to the model.

[![View more on GitHub](https://img.shields.io/badge/View%20more%20on-GitHub-blue?logo=github)](https://github.com/rdemarqui/financial_distress_prediction)

<p align="center">
<img src="images\financial_distress_prediction.PNG" class="center" width="100%"/>
</p>

## Regression 
### Traffic and congestion prediction on LTE networks
A nationwide cellular mobile network contains tens of thousands of base stations. Estimating the traffic increment and consequent congestion of each of these elements can become an arduous and imprecise task, and can lead to incorrect investment decisions.

In this study I replicated the work done by D. Chmieliauskas and D. Guršnys (2019) with some improvements. First, Facebook Prophet was used to generate a time series forecast for the data traffic, then a linear regression between traffic volume and cell resource usage was performed to define the congestion threshold. The purpose of this work was to provide a replicable code for [paperswithcode.com](https://paperswithcode.com/paper/lte-cell-traffic-grow-and-congestion).

[![View more on GitHub](https://img.shields.io/badge/View%20more%20on-GitHub-blue?logo=github)](https://github.com/rdemarqui/traffic_prediction_and_congestion)

<p align="center">
<img src="images\cell_traffic_grow_congestion_forecasting.png" class="center" width="100%"/>
</p>


## Natural Language Processing (NLP) 
### Sentiment Analysis
Sentiment analysis is a segment of machine learning that deciphers emotions within textual data. By employing sophisticated algorithms, it classifies text as positive, negative, or neutral, enabling invaluable insights across industries.

In this study, I measured the impact of different text pre-processing methodologies, such as stop word removal, lemmatization and stemming in different types of word embedding, from the simplest ones like bag of words to LLM like BERT.

[![View more on GitHub](https://img.shields.io/badge/View%20more%20on-GitHub-blue?logo=github)](https://github.com/rdemarqui/sentiment_analysis)
---
### Recommender System
A recommender system is a class of algorithms and techniques used in information filtering and decision-making processes. It's main purpose is to provide personalized suggestions or recommendations to users for items they might be interested in.

In this study I created a perfume recommendation system built based on the scent description using bag of words and similarity search (cosine). Then a demo app was build and can been seen on [Perfume Recommender App](https://huggingface.co/spaces/rdemarqui/perfume_recommender).

[![View more on GitHub](https://img.shields.io/badge/View%20more%20on-GitHub-blue?logo=github)](https://github.com/rdemarqui/perfume_recommender)

<p align="center">
<img src="images\app_gradio.png" class="center" width="100%"/>
</p>

<!--
### Voice Recognition
-->

<!--
## Computer Vision 

detecção de objetos, classificação de imagens e segmentação. reconhecimento facial
-->
---
