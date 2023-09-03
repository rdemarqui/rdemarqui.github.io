<div align="center">
  <h1>Portfolio</h1>
</div>

<p align="justify"> Below, some selected machine learning projects. These are independent projects, many of which reflect what I've been learning in my career or topics that I have an interest in. Feel free to explore them, or if you prefer, visit my <a href="https://github.com/rdemarqui">GitHub</a> page.




### Topics
* [Classification](#classification)
* [Regression](#regression)
* [Natural Language Processing](#natural-language-processing)
* Audio (coming soon)
* Computer Vision (coming soon)
---

## Classification 

### [Financial Distress Prediction](https://github.com/rdemarqui/financial_distress_prediction)

<p align="justify"> Credit scoring algorithms, which make a guess at the probability of default, are the method banks use to determine whether or not a loan should be granted. In this Kaggle competition, participants was required to predict the probability that somebody will experience financial distress in the next two years.</p>

<p align="center">
<img src="images\financial_distress_prediction.png" class="center" width="100%"/>
</p>

<p align="justify"> To tackle this problem, I implemented several models and compared them to find out which one got the best score (AUC). After fine tune the winner, I used SHAP to explain which features were most important to the model.</p>

<code><span style="font-family: 'Hubot Sans', monospace;">| pandas | numpy | matplotlib | sklearn | skopt | imblearn | shap | xgboost | lightgbm |</span></code>

[![View more on GitHub](https://img.shields.io/badge/View%20more%20on-GitHub-blue?logo=github)](https://github.com/rdemarqui/financial_distress_prediction)

---

## Regression

### [Traffic and congestion prediction on LTE networks](https://github.com/rdemarqui/traffic_prediction_and_congestion)
<p align="justify"> A nationwide cellular mobile network contains tens of thousands of base stations. Estimating the traffic increment and consequent congestion of each of these elements can become an arduous and imprecise task, and can lead to incorrect investment decisions.</p>

<p align="center">
<img src="images\cell_traffic_grow_congestion_forecasting.png" class="center" width="100%"/>
</p>

<p align="justify"> To address this business problem, I replicated the work done by D. Chmieliauskas and D. Guršnys (2019) with some improvements. First, Facebook Prophet was used to generate a time series forecast for the data traffic, then a linear regression between traffic volume and cell resource usage was performed to define the congestion threshold. The purpose of this work was to provide a replicable code for <a href="https://paperswithcode.com/paper/lte-cell-traffic-grow-and-congestion">paperswithcode.com</a></p>

<code><span style="font-family: 'Hubot Sans', monospace;">| fbprophet | pandas | sklearn | scipy | numpy | matplotlib | seaborn |</span></code>

[![View more on GitHub](https://img.shields.io/badge/View%20more%20on-GitHub-blue?logo=github)](https://github.com/rdemarqui/traffic_prediction_and_congestion)

---

## Natural Language Processing

### [Sentiment Analysis](https://github.com/rdemarqui/sentiment_analysis)
<p align="justify"> Sentiment analysis is a segment of machine learning that deciphers emotions within textual data. By employing sophisticated algorithms, it classifies text as positive, negative, or neutral, enabling invaluable insights across industries.</p>

<p align="center">
<img src="images\vector_model_boxplot.png" class="center" width="65%"/>
</p>

<p align="justify"> In this study, I measured the impact of different text pre-processing methodologies, such as stop word removal, lemmatization and stemming in different types of word embedding, from the simplest ones like bag of words to transfomers like BERT.</p>

<code><span style="font-family: 'Hubot Sans', monospace;">| nltk | spacy | pandas | numpy | sklearn | lightgbm | matplotlib | seaborn | gensim | torch | transformers | sentence_transformers |</span></code>

[![View more on GitHub](https://img.shields.io/badge/View%20more%20on-GitHub-blue?logo=github)](https://github.com/rdemarqui/sentiment_analysis)

---

### [Recommender System](https://github.com/rdemarqui/perfume_recommender)
<p align="justify"> A recommender system is a class of algorithms and techniques used in information filtering and decision-making processes. It's main purpose is to provide personalized suggestions or recommendations to users for items they might be interested in.</p>

<p align="center">
<img src="images\app_gradio.png" class="center" width="100%"/>
</p>

<p align="justify"> In this work, I created a perfume recommendation system built based on the scent description using bag of words and similarity search (cosine). Then a demo app was build and can been seen on <a href="https://huggingface.co/spaces/rdemarqui/perfume_recommender">Perfume Recommender App </a>.</p>

<code><span style="font-family: 'Hubot Sans', monospace;">| pandas | numpy | sklearn | scipy | gradio |</span></code>

[![View more on GitHub](https://img.shields.io/badge/View%20more%20on-GitHub-blue?logo=github)](https://github.com/rdemarqui/perfume_recommender)

---
