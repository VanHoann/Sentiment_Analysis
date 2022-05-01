# Sentiment Analysis with the Yelp Dataset
This repo contains the code and report for HKUST COMP4332 project 1, which is using the data from the [Yelp Dataset](https://www.yelp.com/dataset) to predict the 'stars' based on the reviews provided by the users, here only 'texts' is used.

## Models
The metrics to be used to compare among models are macro-f1 score and accuracy.

<ol>
  <li>Baseline model 1 follows Statistical Machine Learning with TF-IDF and Logistic Regression</li>
  <li>Baseline model 2 follows simple Deep Learning with Word2Vec and RNN</li>
  <li>The final model uses Transformer architecture with RoBERTa</li>
</ol> 

The final report can be found in `report.pdf`, in which each model is further explained in details.

## Training Environment

Most of the training of the models is done on [Google Colab](https://colab.research.google.com/) because of their GPU support.

