<div align="center">
  <h1>Portfolio</h1>
</div>

<p align="justify"> Below, are some selected machine learning projects. These are independent projects and this portfolio will always be a work in progress. Feel free to explore it, or if you prefer, visit my <a href="https://github.com/rdemarqui">GitHub</a> page. </p>

### Topics
* [Natural Language Processing (NLP)](#natural-language-processing)
* [Classification](#classification)
* [Time Series Forecasting](#time-series-forecasting)
* Clustering (coming soon)
* [Causal Inference](#causal-inference)

---

## Natural Language Processing

### [Decoding User Complaints: An Analysis using Mistral 7B LLM](https://github.com/rdemarqui/llm_complaint_management)
<p align="justify"> Organizations face the critical task of analyzing diverse, complex user complaints. Accurate interpretation and response are key, with Large Language Models (LLMs) proving essential for efficient, automated complaint management and analysis.</p>

<p align="center">
<img src="images\llm_study.png" class="center" width="75%"/>
</p>

<p align="justify"> In this study, I developed a rapid and automated system using Mistral 7B LLM for categorizing user complaints into relevant categories. This approach offers valuable insights into customer concerns, thereby enhancing organizational response strategies. Read full article in <a href="https://medium.com/@rdemarqui/decoding-user-complaints-a-case-study-with-mistral-7b-llm-10f1021380b5">English</a> and <a href="https://www.linkedin.com/pulse/decodificando-reclama%25C3%25A7%25C3%25B5es-de-usu%25C3%25A1rios-um-estudo-caso-rildo-c5epf">Portuguese</a>. </p>

<code><span style="font-family: 'Hubot Sans', monospace;">| pandas | numpy | sklearn | matplotlib | seaborn | selenium | beautifulsoup | transformers |</span></code>

[![View more on GitHub](https://img.shields.io/badge/View%20more%20on-GitHub-blue?logo=github)](https://github.com/rdemarqui/llm_complaint_management)

---

### [Sentiment Analysis](https://github.com/rdemarqui/sentiment_analysis)
<p align="justify"> Sentiment analysis is a segment of machine learning that deciphers emotions within textual data. By employing sophisticated algorithms, it classifies text as positive, negative, or neutral, enabling invaluable insights across industries.</p>

<p align="center">
<img src="images\vector_model_boxplot.png" class="center" width="65%"/>
</p>

<p align="justify"> In this study, I measured the impact of different text pre-processing methodologies, such as stop word removal, lemmatization, and stemming in different types of word embedding, from the simplest ones like bag of words to transformers like BERT.</p>

<code><span style="font-family: 'Hubot Sans', monospace;">| nltk | spacy | pandas | numpy | sklearn | lightgbm | matplotlib | seaborn | gensim | torch | transformers | sentence_transformers |</span></code>

[![View more on GitHub](https://img.shields.io/badge/View%20more%20on-GitHub-blue?logo=github)](https://github.com/rdemarqui/sentiment_analysis)

---

### [Customer Complaint Analysis with Topic Modeling](https://github.com/rdemarqui/topic_modeling)

<p align="justify"> Analyzing large datasets of customer complaint texts is a challenging and essential task for companies looking to improve the quality of their products and services. The diversity of words, topics, and sentiments expressed in such texts can overwhelm analysts. This is where topic modeling emerges as a valuable tool.</p>

<p align="center">
<img src="images\pyLDAvis.png" class="center" width="100%"/>
</p>

<p align="justify"> This work explores how topic modeling can be an effective solution for analyzing large customer complaint datasets, highlighting its applications and benefits.</p>

<code><span style="font-family: 'Hubot Sans', monospace;">| selenium | beautifulsoup | pandas | nltk | spacy | pyLDAvis | bertopic |</span></code>

[![View more on GitHub](https://img.shields.io/badge/View%20more%20on-GitHub-blue?logo=github)](https://github.com/rdemarqui/topic_modeling)

---

### [Recommender System](https://github.com/rdemarqui/perfume_recommender)
<p align="justify"> A recommender system is a class of algorithms and techniques used in information filtering and decision-making processes. Its main purpose is to provide personalized suggestions or recommendations to users for items they might be interested in.</p>

<p align="center">
<img src="images\app_gradio.png" class="center" width="100%"/>
</p>

<p align="justify"> In this work, I created a perfume recommendation system built based on the scent description using bag-of-words and similarity search (cosine). Then a demo app was built and can be seen on <a href="https://huggingface.co/spaces/rdemarqui/perfume_recommender">Perfume Recommender App</a>.</p>

<code><span style="font-family: 'Hubot Sans', monospace;">| pandas | numpy | sklearn | scipy | gradio |</span></code>

[![View more on GitHub](https://img.shields.io/badge/View%20more%20on-GitHub-blue?logo=github)](https://github.com/rdemarqui/perfume_recommender)

---

## Classification 

### [Credit Risk](https://github.com/rdemarqui/financial_distress_prediction)

<p align="justify"> Credit scoring algorithms, which make a guess at the probability of default, are the methods banks use to determine whether or not a loan should be granted. In this Kaggle competition, participants were required to predict the probability that somebody would experience financial distress in the next two years.</p>

<p align="center">
<img src="images\financial_distress_prediction.png" class="center" width="100%"/>
</p>

<p align="justify"> To tackle this problem, I implemented several models and compared them to find out which one got the best score (AUC). After fine-tuning the winner, I used SHAP to explain which features were most important to the model.</p>

<code><span style="font-family: 'Hubot Sans', monospace;">| pandas | numpy | matplotlib | sklearn | skopt | imblearn | shap | xgboost | lightgbm |</span></code>

[![View more on GitHub](https://img.shields.io/badge/View%20more%20on-GitHub-blue?logo=github)](https://github.com/rdemarqui/financial_distress_prediction)

---

## Time Series Forecasting

### [Traffic and Congestion Prediction on LTE Networks](https://github.com/rdemarqui/traffic_prediction_and_congestion)
<p align="justify"> A nationwide cellular mobile network contains tens of thousands of base stations. Estimating the traffic increment and consequent congestion of each of these elements can become an arduous and imprecise task, and can lead to incorrect investment decisions.</p>

<p align="center">
<img src="images\cell_traffic_grow_congestion_forecasting.png" class="center" width="100%"/>
</p>

<p align="justify"> To address this business problem, I replicated the work done by D. Chmieliauskas and D. Guršnys (2019) with some improvements. First, Facebook Prophet was used to generate a time series forecast for the data traffic, and then a linear regression between traffic volume and cell resource usage was performed to define the congestion threshold. The purpose of this work was to provide a replicable code for <a href="https://paperswithcode.com/paper/lte-cell-traffic-grow-and-congestion">paperswithcode.com</a></p>

<code><span style="font-family: 'Hubot Sans', monospace;">| prophet | pandas | sklearn | scipy | numpy | matplotlib | seaborn |</span></code>

[![View more on GitHub](https://img.shields.io/badge/View%20more%20on-GitHub-blue?logo=github)](https://github.com/rdemarqui/traffic_prediction_and_congestion)

---

## Causal Inference

### [Translation of the book Causal Inference for The Brave and True](https://github.com/rdemarqui/python-causality-handbook-ptbr)
<p align="justify">This work is an authorized translation of the open-source book titled <a href="https://matheusfacure.github.io/python-causality-handbook/landing-page.html">Causal Inference for The Brave and True</a> originally authored in English by <a href="https://github.com/matheusfacure">Matheus Facure</a>. This translation aims to contribute to the Portuguese-speaking community that may not be very familiar with English, providing accessible material for those interested in the subject.</p>

<p align="justify">You can check the <a href="https://github.com/rdemarqui/python-causality-handbook-ptbr/blob/master/causal-inference-for-the-brave-and-true/00-Summary.ipynb">Brazilian Portuguese version here</a>. I had a lot of fun and learned a great deal while translating this book. I hope you enjoy and learn as well! Best wishes and happy studying!</p>

[![View more on GitHub](https://img.shields.io/badge/View%20more%20on-GitHub-blue?logo=github)](https://github.com/rdemarqui/python-causality-handbook-ptbr)

---
