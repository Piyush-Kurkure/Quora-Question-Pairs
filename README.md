# Quora-Question-Pairs

Goal - The main aim of this project is to identify whether question pairs in the dataset have the same content or not. The goal is to predict which of the provided pairs of questions contain two questions with the same meaning.

This project is divided into three major parts:
1. Data Analysis and Visualizations
2. Developing Logistic Regression Model
3. Developing LSTM Neural Network model


Dataset:
The dataset can be downloaded from here -
https://www.kaggle.com/c/quora-question-pairs/data

### Logistic Regression Model:
Steps:
1. Data Preprocessing - Transform features by scaling each feature 
2. Using GridSearchCV, we do Exhaustive search over specified parameter values for an estimator.
3. Train LR model using best parameters.
4. Visualize the results of CV parameters.

### LSTM Model:

Steps:
1. Data Preprocessing - Convert text to machine readable format
2. Prepare Embedding matrix using word index of text data in dataset with the help of word2vec for word Embeddings.
3. Define the Model using Embedding layers and LSTM layers.
4. Train and Learn the Model till ethical accuracy is attained.
