# CO1: Fundamentals of Natural Language Processing (NLP)

## Overview

This repository contains practical implementations of fundamental Natural Language Processing (NLP) techniques using Python, NLTK, and spaCy.

## Objectives

- Understand text preprocessing techniques.
- Perform sentence and word tokenization.
- Apply stemming and lemmatization.
- Remove stop words from text.
- Perform Part-of-Speech (POS) tagging.
- Implement parsing and chunking.
- Perform Named Entity Recognition (NER).

## Technologies Used

- Python
- NLTK
- spaCy
- Regular Expressions (re)
- Jupyter Notebook / Google Colab

## List of Experiments

### 1. Tokenization of Sentences and Words Using NLTK and spaCy

**Objective:** Split text into sentences and words using NLTK and spaCy.

**Concepts:** Sentence tokenization, word tokenization, text preprocessing.

**Filename:** `01_Tokenization_NLTK_spaCy.ipynb`

### 2. Stemming and Lemmatization on Sample Text

**Objective:** Reduce words to their root form using stemming and lemmatization.

**Concepts:** Porter Stemmer, Snowball Stemmer, WordNet Lemmatizer.

**Filename:** `02_Stemming_and_Lemmatization.ipynb`

### 3. Stop-Word Removal from a Document

**Objective:** Remove common words that may contribute little to the analysis of a particular text.

**Concepts:** Stop words, text cleaning, preprocessing.

**Filename:** `03_Stop_Word_Removal.ipynb`

### 4. Part-of-Speech (POS) Tagging of a Given Sentence

**Objective:** Identify grammatical categories such as nouns, verbs, adjectives, and adverbs.

**Concepts:** POS tagging, grammatical analysis, linguistic processing.

**Filename:** `04_POS_Tagging.ipynb`

### 5. Parsing and Chunking Using Regex and spaCy

**Objective:** Identify grammatical structures and group words into meaningful phrases.

**Concepts:** Regular expressions, noun phrase chunking, dependency parsing, spaCy.

**Filename:** `05_Parsing_and_Chunking.ipynb`

### 6. Named Entity Recognition (NER) Using spaCy

**Objective:** Identify named entities such as people, organizations, locations, dates, and other entities in text.

**Concepts:** Named Entity Recognition, entity labels, information extraction.

**Filename:** `06_NER_Using_spaCy.ipynb`

## Installation

Install the required libraries using pip:

```bash
pip install nltk spacy jupyter
```

Download the required spaCy English language model:

```bash
python -m spacy download en_core_web_sm
```

## How to Run

1. Clone or download this repository.
2. Open the required notebook in Jupyter Notebook or Google Colab.
3. Install the required libraries.
4. Run the notebook cells sequentially.
5. Observe the output for each experiment.

## Repository Structure

```text
CO1-NLP/
│
├── README.md
├── 01_Tokenization_NLTK_spaCy.ipynb
├── 02_Stemming_and_Lemmatization.ipynb
├── 03_Stop_Word_Removal.ipynb
├── 04_POS_Tagging.ipynb
├── 05_Parsing_and_Chunking.ipynb
└── 06_NER_Using_spaCy.ipynb
```

## Learning Outcomes

After completing these experiments, learners will be able to:

- Preprocess text using NLP libraries.
- Understand stemming and lemmatization.
- Remove stop words from documents.
- Identify grammatical categories using POS tagging.
- Perform basic parsing and chunking.
- Extract named entities using spaCy.

## Author

**Ankit Maurya**

B.Tech – Computer Science and Engineering (Artificial Intelligence)

## License

This repository is intended for educational and academic purposes.
