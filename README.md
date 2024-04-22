# Semantic Search Using NLP and LSI

This project demonstrates how to perform semantic search using Natural Language Processing (NLP) and Latent Semantic Indexing (LSI). Semantic search allows you to search for documents based on meaning rather than just keywords. LSI is a technique used to reduce the dimensionality of text data and capture latent relationships between words and documents.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Data](#data)
- [Latent Semantic Indexing (LSI)](#latent-semantic-indexing-lsi)
- [Code Explanation](#code-explanation)
- [References](#references)

## Introduction

Semantic search enables users to find documents based on their meaning rather than just keywords. In this project, Latent Semantic Indexing (LSI) is employed to capture latent relationships between words and documents in a corpus. This project uses NLP techniques to preprocess text data, apply LSI, and perform semantic search.

## Features

- Uses LSI for semantic search in a corpus of documents.
- Preprocesses text data using NLP techniques.
- Finds documents that match a query based on semantic similarity.

## Setup and Installation

1. **Clone the Repository**:
    - Clone the project repository to your local machine.
    ```bash
    git clone https://github.com/your-username/your-repo-name.git
    cd your-repo-name
    ```

2. **Create a Virtual Environment**:
    - Create and activate a virtual environment (recommended).
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

3. **Install Dependencies**:
    - Install the required Python packages using the provided `requirements.txt` file.
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Run the Script**:
    - Run the script to perform semantic search using LSI.
    ```bash
    python semantic_search.py
    ```

2. **Provide Query**:
    - The script will prompt you to input a query.

3. **Receive Search Results**:
    - The system will display documents from the corpus that match the query based on semantic similarity.

## Data

- The data used in this project consists of a corpus of documents.
- The corpus can include a variety of document types such as articles, reports, or textual data.
- The data is preprocessed and used for training the LSI model.

## Latent Semantic Indexing (LSI)

- LSI is a technique that captures latent relationships between words and documents in a corpus.
- The process includes the following steps:
    - **Text Preprocessing**: Text data is tokenized, normalized, and vectorized.
    - **Term Frequency-Inverse Document Frequency (TF-IDF)**: TF-IDF weighting is applied to the term-document matrix to emphasize important terms.
    - **Singular Value Decomposition (SVD)**: SVD is applied to the weighted term-document matrix to reduce its dimensionality and obtain latent semantic structures.
    - **Querying**: Once the model is trained, queries can be performed by transforming the query vector and finding the most similar documents.

## Code Explanation

- **semantic_search.py**:
    - The script for loading the corpus, applying LSI, and running semantic search.
    - Takes user input for queries and performs text preprocessing, TF-IDF weighting, and SVD.
    - Uses the trained LSI model to find documents that match the query based on semantic similarity.

## References

- [Scikit-learn Documentation](https://scikit-learn.org/)
- [Kaggle Reference Code Link](https://www.kaggle.com/code/ajitrajput/semantic-search-engine-using-nlp)
- [Natural Language Toolkit (nltk)](https://www.nltk.org/)

## Conclusion

This project demonstrates how to perform semantic search using NLP and Latent Semantic Indexing (LSI). By applying LSI to a corpus of documents, the project enables semantic search based on meaning rather than just keywords. Customize and extend this project to suit your needs and explore different datasets and approaches for semantic search.
