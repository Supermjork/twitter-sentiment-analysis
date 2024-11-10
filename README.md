# Sentiment Analysis for Tweets

Assignment for NLP Course to preprocess and analyse the sentiment of tweets.

The aim of this is to interpret which model captures words and related concepts in a coherent manner, and will be done through a series of steps; namely:

- [] Preprocessing
- [] Word Embedding Models (Word2Vec CBOW/Skip-gram, GloVe)
- [] Comparative Analysis
- [] Visualisation
- [] Evaluation

## Libraries to be used

The set of libraries used to make this project work.

### Preprocessing

- NLTK
- SpaCy
- re

### Word Embedding Models

- Gensim
- torchtext

### Dimensionality Reduction (Plotting)

- Scikit-learn
- Matplotlib
- Seaborn

## Installation

I'm using Python `3.12.2`

Make sure you have a virtual environment called `venv_nlp` setup for this to run in. (Make sure to be in the repository's root folder)

```ps1
# If you don't have the library for it
pip install virtualenv
```

```ps1
# Define your venv name
virtualenv venv_nlp
```

```ps1
# Activate your venv
.\venv_nlp\Scripts\activate.ps1
```

```ps1
# Once activated
# Install requirements
pip install -r .\requirements.txt
```
