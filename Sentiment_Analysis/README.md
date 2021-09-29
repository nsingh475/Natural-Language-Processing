# Sentiment Analysis 

Sentiment analysis is an application of Natural Langugae Processing which tries to determine whether the sentiment of data. Sentiment analysis is often performed on textual data to help businesses monitor brand and product sentiment in customer feedback, and understand customer needs.

Sentiment analysis models focus on:
1. polarity (positive, negative, neutral)
2. feelings and emotions (angry, happy, sad, etc)
3. urgency (urgent, not urgent) 
4. intentions (interested v. not interested).

#### Sentiment analysis algorithms
Sentiment analysis algorithms fall into one of three buckets:
1. Rule-based
2. Automatic
3. Hybrid systems


#### Rules Based Sentiment Analysis
These rules may include various NLP techniques developed in computational linguistics, such as:
1. Stemming
2. Tokenization
3. Part-of-speech tagging and parsing.
4. Lexicons (i.e. lists of words and expressions)


#### Automatic Sentiment Analysis
It rely on machine learning technique. A sentiment analysis task is usually modeled as a classification problem, whereby a classifier is fed a text and returns a category, e.g. positive, negative, or neutral.
The classification step usually involves a statistical model like:
1. Naïve Bayes
2. Linear Regression or Logistic Regression
3. Support Vector Machines
4. Neural Networks


#### Project implementation and workflow
Following are the sub-tasks :
1. Importing Libraries
2. Exploratory Data Analysis and Preprocessing
3. Training/Validation Split
4. Loading Tokenizer and Encoding our Data
5. Setting up BERT Pretrained Model
6. Creating Data Loaders
7. Setting Up Optimizer and Scheduler
8. Defining our Performance Metrics
9. Creating our Training Loop 


In this project, Sentiment Analysis model is built using pre-trained BERT transformer. The architecture is for multi-class classification. 

