# BT5153-MBTI-Group16

A group project for module BT5153, designed to predict your MBTI personality based on your posts in the forum.

## Data
The dataset mbti_1.csv is from [Kaggle](https://www.kaggle.com/datasets/datasnaek/mbti-type).

## Data Preprocessing & EDA
The code for data preprocessing and EDA is in [Preprocessing&EDA.ipynb](./Preprocessing&EDA.ipynb).

## Models
We first trained multi-class classifier for 16 types of personalities, then trained binary classifier for 4 dimentions to find the best model.
### Method1: Multi-Class Classifier
For multi-class classifier, we explored various models for three types of preprocessing: clean texts with stopwords, TF-IDF and Doc2Vec.

The code for Bert and CNN models is in [Method1_BERT&CNN.ipynb](./Method1_BERT&CNN.ipynb).

The code for models trained on TF-IDF is in [Method1_tfidf.ipynb](./Method1_tfidf.ipynb).

The code for models trained on Doc2Vec is in [Method1_doc2vec.ipynb](./Method1_doc2vec.ipynb).

### Method2: Binary Classifier
The code for binary classifiers is in [Method2_code.ipynb](./Method2_code.ipynb).

### Model Explanation
We use SHAP for model explanation, and the code is in [Shap.ipynb](./Shap.ipynb).
