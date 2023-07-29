# POS Tagging using Hidden Markov Model

This repository contains Python code for Part-of-Speech (POS) Tagging using a Hidden Markov Model (HMM) on the Brown corpus data. The Hidden Markov Model is used to predict the POS tags for words in sentences.

## About the Dataset

The code uses the Brown corpus from the NLTK library, which contains tagged sentences with words and their respective POS tags.

## How the Code Works

1. **Data Preparation**: The Brown corpus is loaded and modified to add special tokens '##' and '&&' at the start and end of each sentence, respectively.

2. **POS Tag Mapping**: The POS tags are mapped into standard categories like 'Adjective', 'Noun', 'Adposition', 'Adverb', 'Conjuction', 'Numerial', 'Determiner', 'Particle', 'Pronoun', 'Verb', 'Punctuation', '##', and '&&'.

3. **Training**: The code calculates the emission and transition probabilities based on the training data.

4. **Prediction**: The Hidden Markov Model predicts the POS tags for the test data using the Viterbi algorithm.

5. **Evaluation**: The accuracy and loss of the model are calculated on the test data.

## Requirements

- Python 3.x
- NLTK library

## Usage

1. Clone or download this repository to your local machine.

2. Make sure you have the required dependencies installed. You can install the NLTK library using pip:


3. Execute the `pos_tagger.py` script to perform POS tagging on the Brown corpus data.

## Results

The code provides the accuracy and loss of the model on the test data. Additionally, it shows the accuracy and loss specifically for the 'Adjective' tag.

