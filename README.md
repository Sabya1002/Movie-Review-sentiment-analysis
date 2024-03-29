# Movie-Review-sentiment-Analyzer
Sentiment Analyzer case study is a Machine Learning and NLP base project for sentiment analysis of movie reviews

DataSet: IMDB Movie review dataset
## Overview
This project aims to perform sentiment analysis on movie reviews using natural language processing (NLP) techniques and machine learning algorithms. We focus on the IMDB Movie Review dataset, which contains 150,000 labeled movie reviews. By analyzing the text of these reviews, we classify them as either positive or negative.
## Dataset
This IMDB dataset goal is to provide a base for sentiment analysis. Usually, datasets of this kind provide binary classes telling whether the text is positive or negative however this approach fails in some points. We don't know how the data was linked to those labels and the queries used. Here, these fails were solved. To do so we:

- Query ratings using a fixed window of 1 point to increase the probability of having reviews rating that specific value.
- Checked whether the movie was already evaluated or not.
- Recorded the firsts reviews and ratings excluding the spoiler tag.
- Then after data being retrieved, we translated all reviews to Portuguese.

## Approach
1.### Data Preprocessing:
  - Tokenization: Splitting reviews into individual words or tokens.
  - Removing stop words, punctuation, and special characters.
  - Lemmatization or stemming to reduce words to their base form.
2.### Feature Extraction:
  - Bag-of-words representation or word embeddings (e.g., Word2Vec, GloVe).
3.### Model Selection
  - We explore various machine learning models, including:
     -  Logistic Regression
     -  Random Forest Classifier
     -  Decision Tree Classifier
     -  Ada boost Classifier
     -  Finetuned Random Forest Classifier
     -  Support Vector Machines (SVM)
4.### Model Training and Evaluation:
  - Splitting the dataset into training and testing sets.
  - Training the selected model(s) on the training data.
  - Evaluating model performance using accuracy, precision, recall, F1-score, etc.
5.### Deployment:
  - Deploying the trained model for real-time sentiment analysis.
    
