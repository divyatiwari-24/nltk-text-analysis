## Introduction:

This project explores text analysis using the Natural Language Toolkit (NLTK) on Shakespeare’s Hamlet (from the Gutenberg Corpus).

The analysis includes:

- Text preprocessing

- Word frequency distribution

- Named Entity Recognition (NER)

- Sentiment exploration using VADER

## Features

1. Preprocessing

   - Sentence & word tokenization
    
   - Lowercasing, punctuation & stopword removal
    
   - Lemmatization

2. Frequency Analysis

   - Word frequency distribution
    
   - Top 20 most frequent words (bar chart)
    
   - POS tagging to extract common nouns

3. Named Entity Recognition (NER)

   - Extracts people, places, organizations

4. Sentiment Analysis
    
   - Sentence-level sentiment classification
    
   - Results visualized in a pie chart
    
   - Distribution:
    
     a. Positive: 23.6%
      
     b. Negative: 15.6%
      
     c. Neutral: 60.8%


## How to Run

Clone this repository:

git clone https://github.com/your-username/nltk-text-analysis.git
cd nltk-text-analysis


Install dependencies:

pip install nltk matplotlib


Download required NLTK resources:

import nltk
nltk.download('gutenberg')
nltk.download('punkt')
nltk.download('stopwords')
nltk.download('wordnet')
nltk.download('averaged_perceptron_tagger')
nltk.download('maxent_ne_chunker')
nltk.download('words')
nltk.download('vader_lexicon')


Run the Notebook:

jupyter notebook Text_Analysis_Assignment.ipynb

## References

NLTK Documentation

VADER Sentiment Analysis

Gutenberg Corpus

 Developed by Divya Tiwari (2025)
