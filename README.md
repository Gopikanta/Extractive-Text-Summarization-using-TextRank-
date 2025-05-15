# 🧠 Extractive Text Summarization using TextRank

This project demonstrates an **Extractive Text Summarization** technique using the **TextRank algorithm**. The implementation uses Natural Language Processing tools like **spaCy** for sentence parsing and word embeddings, and **NetworkX** for computing sentence importance using the PageRank algorithm. Additionally, the code includes a word frequency analysis with graphical visualization.

---

## ✨ Features

- Extracts the most important sentences from a given input text.
- Uses pre-trained word embeddings from spaCy (`en_core_web_sm`) for sentence similarity.
- Applies the PageRank algorithm to rank sentences based on relevance.
- Includes word repetition analysis and plots a frequency bar chart.

---

## 🛠️ Technologies Used

- **Python**
- **spaCy**
- **NumPy**
- **NetworkX**
- **Matplotlib**
- **collections.Counter**

---

## 📁 Project Structure

🧪 How It Works
The input text is tokenized into sentences using spaCy.

Each sentence is cleaned (stopwords and punctuation removed).

Sentence embeddings are created using the average of token vectors.

Sentence similarity is calculated using cosine similarity.

A similarity matrix is constructed and passed into PageRank.

Top-ranked sentences are selected for the summary.

The word frequency count (excluding stopwords and punctuation) is computed and visualized.

