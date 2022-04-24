# BT5153-MBTI-Group16

A group project for module BT5153, designed to predict your MBTI personality based on your posts in the forum.

## Data
The dataset mbti_1.csv is from [Kaggle](https://www.kaggle.com/datasets/datasnaek/mbti-type).

## Models
We first trained multi-class classifier for 16 types of personalities, then trained binary classifier for 4 dimentions to find the best model.
### Method1: Multi-Class Classifier
For multi-class classifier, we explored various models for three types of preprocessing: clean texts with stopwords, TF-IDF and Doc2Vec.

The code for Bert and CNN models is in [BERT&CNN.ipynb](./BERT&CNN.ipynb)


### Method2: Binary Classifier
