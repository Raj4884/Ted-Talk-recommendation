# 🎤 TED Talk Recommendation System

A machine learning and NLP-based project that recommends TED Talks based on user preferences, content similarity, and topic modeling.

![Python](https://img.shields.io/badge/Python-3.10-blue)
![NLP](https://img.shields.io/badge/NLP-TF-IDF|LDA|Word2Vec-orange)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Project-Complete-brightgreen)

---

## 📌 Objective

The goal of this project is to build an intelligent system that recommends relevant TED Talks to users based on talk descriptions, tags, or user inputs. It leverages natural language processing and vector similarity models to make personalized suggestions.

---

## 📂 Dataset

- **Source:** [Kaggle - TED Talks Dataset](https://www.kaggle.com/datasets/rounakbanik/ted-talks)
- **Fields Used:**
  - Title
  - Description
  - Tags
  - Transcript
  - Views, Duration, Ratings

---

## 🛠️ Tech Stack

- **Languages:** Python
- **Libraries & Tools:**
  - Pandas, NumPy, Scikit-learn
  - NLTK, spaCy
  - TF-IDF, Cosine Similarity
  - Word2Vec / GloVe (for embeddings)
  - Streamlit (for deployment)

---

## 🔄 Workflow

1. **Data Preprocessing**
   - Clean text: remove stopwords, lemmatize, lowercase
   - Handle missing values
   - Tokenization & vectorization (TF-IDF / Word2Vec)

2. **Exploratory Data Analysis**
   - Top tags, most viewed talks
   - Word clouds and bar plots

3. **Recommendation Engine**
   - Content-Based Filtering using Cosine Similarity
   - Semantic Search using Word Embeddings (Word2Vec/GloVe)
   - Optional: Topic modeling with LDA for topic-aware suggestions
