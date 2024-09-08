SentimentAnalysisTweets
This project is part of an assignment to perform sentiment analysis on a dataset of approximately 27,000 tweets. The goal is to classify the sentiment expressed in each tweet using natural language processing techniques.

Project Overview
Dataset: 27,000 tweets, split 80% for training and 20% for testing.
Objective: Implement a text classifier for sentiment analysis.
Tools Used: Python, NLTK, Scikit-learn
Features
Data Processing: Load and split data.
Preprocessing: Normalize text, remove stopwords, lemmatize.
Feature Extraction: Generate unigrams and bigrams.
Model Training: Train a LinearSVC classifier.
Evaluation: Use precision, recall, and F1 score metrics.
Installation
Clone the repository:
bash

Copy
git clone https://github.com/your_username/SentimentAnalysisTweets.git
cd SentimentAnalysisTweets
Install dependencies:
bash

Copy
pip install -r requirements.txt
Usage
Run the Jupyter Notebook to execute the sentiment analysis:

bash

Copy
jupyter notebook NLP_Assignment_1_shrey_shrivastava.ipynb
Results
The model achieves an average precision of 85.69%, recall of 85.86%, and F1 score of 85.65%.
