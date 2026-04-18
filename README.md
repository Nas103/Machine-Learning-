# Machine-Learning-

# 🧠 Sentiment Analysis LLM (Lightweight NLP Pipeline)

## Overview

This project implements a lightweight Natural Language Processing (NLP) pipeline for sentiment analysis using classical machine learning techniques. It processes text reviews, transforms them into numerical features using TF-IDF, and classifies sentiment using Logistic Regression.

Despite being labeled as an "LLM program," this is technically a traditional ML-based text classification system—not a large language model.

---

## 🚀 Features

* Text preprocessing (tokenization, stopword removal, stemming)
* TF-IDF vectorization
* Multi-class sentiment classification (Negative, Neutral, Positive)
* Simple test predictions
* Data visualization (sentiment distribution)

---

## 🧰 Tech Stack

* Python
* NLTK (Natural Language Toolkit)
* Scikit-learn
* Pandas
* Matplotlib

---

## 📦 Installation

1. Clone the repository:

```bash
git clone <your-repo-url>
cd <repo-name>
```

2. Install dependencies:

```bash
pip install nltk pandas scikit-learn matplotlib
```

3. Download required NLTK datasets:

```python
import nltk
nltk.download('punkt')
nltk.download('stopwords')
```

---

## ⚙️ How It Works

### 1. Preprocessing

Text is cleaned and normalized through:

* Lowercasing
* Removing punctuation
* Tokenization
* Stopword removal
* Stemming using Porter Stemmer

### 2. Feature Extraction

* Uses **TF-IDF Vectorizer** to convert text into numerical feature vectors.

### 3. Model Training

* A **Logistic Regression** classifier is trained on labeled sentiment data.

### 4. Prediction

* New reviews are preprocessed, vectorized, and passed to the model for prediction.

---

## 📊 Example Dataset

| Review                             | Sentiment |
| ---------------------------------- | --------- |
| This product is fantastic!         | Positive  |
| Terrible quality, broke in 2 days. | Negative  |
| It works okay but could be better. | Neutral   |
| Absolutely love it!                | Positive  |
| Not worth the price.               | Negative  |

---

## 🧪 Example Output

```bash
Review: 'Love this product! Worth every penny.' → Sentiment: Positive
Review: 'Disappointing and overpriced.' → Sentiment: Negative
Review: 'It's decent, but nothing special.' → Sentiment: Neutral
```

---

## 📈 Visualization

The program includes a bar chart showing sentiment distribution across the dataset.

---
## 👨‍💻 Author
Nas

