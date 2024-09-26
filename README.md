## Sentiment Analysis using NLP

![Sentiment Analysis](https://github.com/user-attachments/assets/cc1a2218-d59e-4b1d-83da-43102b46380d)

## Objective

The goal of this project is to analyze the sentiment of customer reviews of Amazon products using NLP techniques in order to classify the overall sentiment as positive or negative. This will help identify trends in customer satisfaction, provide actionable insights for product improvement and enhance the customer experience by addressing common issues reflected in the reviews. Additionally, this analysis aims to quantify the emotional tone in user feedback to support better business decisions.

## Data Collection

I have sourced the "Amazon Alexa Reviews" dataset from kaggle.

https://www.kaggle.com/datasets/mahmoudshaheen1134/amazon-alexa-reviews-dataset

The dataset contains reviews of Alexa from May 2018 to July 2018.

## Data Cleaning and Preprocessing

- Dropped dulpicates records.
- Dropped 1 Missing value of verified reviews.
- Cleaned the Verified reviews with RegEx.
- Analyzed the data based on positive and negative feedbacks.
- Applied Stemming to the data to reduce overfitting and dimensionality.

## Model

- Applied 8 Models and got best score by XG-Boost Classifier with 92% Accuracy.

## Skills Used

- Count Vectorizer
- Stemming (Porter Stemmer)
- Lemmatization
- Word Cloud
- RegEx (Regular Expression)
