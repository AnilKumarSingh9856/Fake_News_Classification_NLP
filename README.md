# 📰 Fake News Classification using NLP

![Fake News Detection Banner](https://img.freepik.com/free-vector/news-concept-illustration_114360-1675.jpg)

## Overview

This project focuses on identifying and classifying fake news articles using Natural Language Processing (NLP) techniques. The goal is to build a reliable model that can differentiate between real and fake news based on textual data such as article titles or content.

- **Language:** Python (Jupyter Notebook)
- **Dataset:** News articles labeled as "Fake News" or "Factual News"
- **Techniques:** Data preprocessing, POS tagging, sentiment analysis, topic modeling, ML classification

---

## Table of Contents

- [Demo](#demo)
- [Features](#features)
- [Setup & Installation](#setup--installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

---

## Demo

Run the [Jupyter Notebook](https://github.com/AnilKumarSingh9856/Fake_News_Classification_NLP/blob/main/Fake_News_Classification_NLP.ipynb) directly in [Google Colab](https://colab.research.google.com/github/AnilKumarSingh9856/Fake_News_Classification_NLP/blob/main/Fake_News_Classification_NLP.ipynb):

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AnilKumarSingh9856/Fake_News_Classification_NLP/blob/main/Fake_News_Classification_NLP.ipynb)

---

## Features

- 📊 **Data Exploration:** Visualizes the distribution of fake and factual news.
- 🧹 **Preprocessing:** Tokenization, stemming, lemmatization, and stopword removal.
- 🏷 **POS Tagging & NER:** Uses spaCy for part-of-speech tagging and named entity recognition.
- 😃 **Sentiment Analysis:** Utilizes VADER for sentiment scoring.
- 🧠 **Topic Modeling:** Implements Gensim’s LSI & TF-IDF models.
- 🤖 **ML Models:** Logistic Regression and SGDClassifier for final classification.
- 📈 **Evaluation:** Accuracy, classification report, and visualizations.

---

## Setup & Installation

1. **Clone this repository:**
    ```bash
    git clone https://github.com/AnilKumarSingh9856/Fake_News_Classification_NLP.git
    cd Fake_News_Classification_NLP
    ```

2. **Open the notebook:**
    - Use Jupyter Notebook locally, or [run on Colab](https://colab.research.google.com/github/AnilKumarSingh9856/Fake_News_Classification_NLP/blob/main/Fake_News_Classification_NLP.ipynb).

3. **Install Dependencies:**
    Most requirements are installed automatically in Colab. For local setup:
    ```bash
    pip install pandas matplotlib seaborn spacy nltk vaderSentiment gensim scikit-learn
    python -m spacy download en_core_web_sm
    ```

---

## Usage

1. **Upload your dataset:**  
   The notebook expects a CSV file (e.g., `fake-news-data.csv`) with columns: `title`, `text`, `date`, `fake_or_factual`.

2. **Follow the notebook steps:**  
   - Data loading & exploration
   - Preprocessing & feature engineering
   - Model training & evaluation

3. **Modify and experiment:**  
   Tweak models, try different classifiers, or use your own news data!

---

## Project Structure

```
├── Fake_News_Classification_NLP.ipynb   # Main notebook
├── fake-news-data.csv                   # Sample dataset (upload manually)
└── README.md                            # Project documentation (this file)
```

---

## Results

- Classification accuracy and sample predictions are displayed in the notebook.
- Example output:  
  | Model               | Accuracy |
  |---------------------|----------|
  | Logistic Regression |  **91.66%** |
  | SGD Classifier      |  **93.33%** |

*See the notebook for charts and detailed metrics.*

---

## Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---

## License

[MIT](LICENSE)

---

**Star** ⭐ this repo if you find it useful!
