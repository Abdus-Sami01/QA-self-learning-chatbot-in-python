# QA-self-learning-chatbot-in-python
# Chatbot

This project is a chatbot that utilizes Natural Language Processing (NLP) techniques to understand and respond to user queries. It employs TF-IDF vectorization, cosine similarity, and a database for efficient information retrieval.

## Features
- Uses `nltk`, `spacy`, and `textblob` for text processing and understanding.
- Implements `sklearn`'s `TfidfVectorizer` for transforming text into numerical representations.
- Utilizes `faiss` for efficient similarity search.
- Stores FAQs in an SQLite database for quick lookups.

## Installation
To set up the project, install the required dependencies:

```sh
pip install -r requirements.txt
```

## Usage
Run the Jupyter Notebook to start interacting with the chatbot. Ensure that necessary models and datasets (like `nltk` stopwords and `spacy` language models) are downloaded before use.

## Dependencies
The dependencies are listed in `requirements.txt`.
