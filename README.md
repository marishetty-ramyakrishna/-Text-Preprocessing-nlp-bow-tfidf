# Text Preprocessing in NLP: Bag of Words (BoW) and TF-IDF

## 📌 Overview

Natural Language Processing (NLP) deals with processing and understanding human language. Since machine learning models work with numerical data, text needs to be converted into a numerical representation before it can be used for analysis and machine learning.

This repository accompanies the article **"Text Preprocessing in NLP: Bag of Words (BoW) and TF-IDF"** and presents two commonly used techniques for representing text numerically:

* **Bag of Words (BoW)**
* **TF-IDF (Term Frequency–Inverse Document Frequency)**

## 📚 Topics Covered

* Text preprocessing in NLP
* Converting text into numerical representations
* Bag of Words (BoW)
* TF-IDF
* Understanding how words are represented as numerical features
* Comparing BoW and TF-IDF

## 🧠 Bag of Words (BoW)

Bag of Words is a simple technique for representing text based on the words that occur in a collection of documents.

It creates a vocabulary from the text and represents each document using the frequency of the words appearing in that vocabulary.

### Example

For documents such as:

```text
Document 1: I love Machine Learning
Document 2: Machine Learning is amazing
Document 3: I love Python
```

A vocabulary can be created from the unique words, and each document can then be represented using numerical values based on word occurrence.

## 📊 TF-IDF

TF-IDF assigns importance to words based on how frequently they occur in a document and how common they are across the complete collection of documents.

It consists of two main components:

* **TF — Term Frequency**
* **IDF — Inverse Document Frequency**

Words that are frequent in a particular document but less common across other documents receive higher importance.

## 🔍 BoW vs TF-IDF

| Feature                              | Bag of Words   | TF-IDF                   |
| ------------------------------------ | -------------- | ------------------------ |
| Representation                       | Word frequency | Weighted word importance |
| Considers word frequency             | Yes            | Yes                      |
| Considers document frequency         | No             | Yes                      |
| Simple to understand                 | Yes            | Yes                      |
| Common words can receive high values | Yes            | Reduced importance       |

## 🛠️ Technologies

* Python
* Natural Language Processing (NLP)
* Machine Learning concepts
* Text vectorization


## 🎯 Learning Objective

The main objective of this repository is to demonstrate how textual data can be transformed into numerical features using **Bag of Words** and **TF-IDF**, which can then be used as input for machine learning and NLP tasks.

## 📝 Article

This repository is based on the Medium article:[https://lnkd.in/p/daYhD4xS]

**Text Preprocessing in NLP: Bag of Words (BoW) and TF-IDF**

## 👩‍💻 Author

**Marishetty Ramyakrishna**

⭐ If you found this repository useful, consider giving it a star!
