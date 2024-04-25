# Sentiment Analysis on Amazon Reviews

## Project Overview
This project is a comprehensive sentiment analysis of Amazon product reviews. The primary objective is to classify the sentiment of the reviews as positive or negative based on the text content. This analysis can provide valuable insights for businesses and researchers interested in understanding consumer behaviour and improving product quality.

## Methodology
The sentiment analysis is performed using two different techniques:
1. **VADER (Valence Aware Dictionary and sentiment Reasoner)**: A lexicon and rule-based sentiment analysis tool that is specifically attuned to sentiments expressed in social media.
2. **RoBERTa Pretrained Model from Hugging Face**: A robustly optimized BERT pretraining approach that improves the state-of-the-art performance of BERT on a wide range of natural language processing tasks.

## Dataset
The dataset used in this project is sourced from Kaggle and contains a large collection of Amazon reviews. Each review includes the text content and a corresponding sentiment label (positive or negative).

## Tools and Libraries Used
- **Python**: The main programming language used for implementing the project.
- **Pandas & Numpy**: Used for data manipulation and analysis.
- **Scikit-learn**: Used for machine learning model training and evaluation.
- **Matplotlib & Seaborn**: Used for data visualization.
- **VADER Sentiment Analysis**: Used for sentiment analysis based on a bag-of-words approach.
- **Hugging Face's Transformers**: Used for sentiment analysis with the RoBERTa model.

## Installation and Setup
1. Clone this repository to your local machine using the command: `git clone https://github.com/nakul-patle/Sentiment-analysis-of-amazon-reviews`
2. Navigate to the project directory: `cd Sentiment-analysis-of-amazon-reviews`
