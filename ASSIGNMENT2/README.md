NLP Practical Assignment 2
1. Problem Statement

    Perform the following text representation techniques:
    
    Bag of Words (BoW)
    Count Occurrence
    Normalized Count Occurrence
    TF-IDF (Term Frequency–Inverse Document Frequency)
    Word Embeddings using Word2Vec
    Dataset
    
    Dataset used:
    Car Dataset from Kaggle – Car Dataset

2. Explanation
    Bag of Words (BoW)
    Bag of Words is a technique used to convert text into numerical form.
    
    Count Occurrence: Counts how many times each word appears in a document
    Normalized Count: Divides word count by total number of words in the document
    TF-IDF
    
    TF-IDF measures the importance of a word in a document relative to the entire dataset.
    
    TF (Term Frequency): Frequency of a word in a document
    IDF (Inverse Document Frequency): Measures how unique or rare a word is across documents
    Word2Vec
    
    Word2Vec is used to create word embeddings (vector representations of words).
    
    Captures semantic relationships between words
    Similar words have similar vector representations
    Implementation Overview
    Load and preprocess dataset
    Clean and tokenize text data
    Apply Bag of Words (Count and Normalized)
    Compute TF-IDF features
    Train Word2Vec model to generate embeddings
    Output
    BoW vectors (count and normalized)
    TF-IDF matrix
    Word embeddings for words in the dataset
3. Conclusion
    
    This assignment demonstrates different techniques to convert text into numerical representations. Bag of Words and TF-IDF provide simple statistical methods, while Word2Vec captures semantic meaning through embeddings, making it useful for advanced NLP tasks.
