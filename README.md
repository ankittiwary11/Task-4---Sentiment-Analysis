# 🔍 Task 4 - Sentiment Analysis using NLP
### CodTech IT Solutions — Data Analytics Internship

---

## 👤 Intern Details

| Field | Details |
|-------|---------|
| **Name** | Ankit Tiwary |
| **Intern ID** | CITS538 |
| **Company** | CodTech IT Solutions Pvt. Ltd. |
| **Domain** | Data Analytics |
| **Duration** | 4 Weeks |
| **Mentor** | Neela Santhosh Kumar |

---

## 📌 Task Overview

Perform **Sentiment Analysis** on textual data (e.g., movie reviews, tweets) using **Natural Language Processing (NLP)** techniques.

---

## 🎯 Objectives

- Preprocess raw textual data for NLP tasks
- Build and evaluate supervised ML models for sentiment classification
- Apply lexicon-based sentiment analysis using VADER
- Extract insights and visualize results

---

## 📁 Repository Structure

```
Task-4-Sentiment-Analysis/
│
├── sentiment_analysis.ipynb   # Main Jupyter Notebook
├── README.md                  # Project documentation
├── requirements.txt           # Python dependencies
│
└── outputs/                   # Generated plots (auto-created)
    ├── sentiment_distribution.png
    ├── review_length_analysis.png
    ├── wordclouds.png
    ├── confusion_matrix_*.png
    ├── model_comparison.png
    └── vader_distribution.png
```

---

## 🛠️ Tech Stack

| Category | Tools / Libraries |
|----------|------------------|
| Language | Python 3.x |
| NLP | NLTK, VADER |
| ML Models | Scikit-learn |
| Vectorization | TF-IDF, CountVectorizer |
| Visualization | Matplotlib, Seaborn, WordCloud |
| Data Handling | Pandas, NumPy |
| Environment | Jupyter Notebook |

---

## 📊 Workflow

```
Raw Text Data
     ↓
Data Preprocessing
(Lowercase → Remove HTML/URLs → Remove Special Chars → Tokenize → Remove Stopwords → Lemmatize)
     ↓
Exploratory Data Analysis
(Distribution Plots, Review Length, WordClouds)
     ↓
Feature Extraction
(TF-IDF Vectorization with Bigrams)
     ↓
Model Training
(Logistic Regression | Naive Bayes)
     ↓
Model Evaluation
(Accuracy, Precision, Recall, F1-Score, Confusion Matrix)
     ↓
VADER Analysis
(Lexicon-based unsupervised sentiment scoring)
     ↓
Insights & Conclusions
```

---

## 📈 Results Summary

| Model | Accuracy |
|-------|----------|
| Logistic Regression | ~88–91% |
| Multinomial Naive Bayes | ~85–88% |
| VADER (Lexicon) | ~70–75% |

> *Exact results may vary based on dataset size and random seed.*

---

## 🚀 How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/YOUR_USERNAME/CodTech-Data-Analytics-Internship.git
cd CodTech-Data-Analytics-Internship/Task-4-Sentiment-Analysis
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Launch Jupyter Notebook
```bash
jupyter notebook sentiment_analysis.ipynb
```

### 4. Run All Cells
- Go to **Kernel → Restart & Run All**

---

## 📦 Dataset Used

**IMDB Movie Reviews Dataset**
- 50,000 movie reviews (positive/negative)
- Balanced dataset: 25K positive, 25K negative
- Source: Kaggle / GitHub (auto-loaded in notebook)

---

## 🔑 Key Concepts Covered

- **Text Preprocessing:** Tokenization, Stopword Removal, Lemmatization
- **Feature Engineering:** TF-IDF with unigrams and bigrams
- **Supervised Learning:** Logistic Regression, Naive Bayes
- **Lexicon-Based NLP:** VADER Sentiment Intensity Analyzer
- **Evaluation Metrics:** Accuracy, Precision, Recall, F1-Score
- **Visualization:** WordClouds, Confusion Matrix, Distribution Plots

---

## 💡 Key Insights

1. **Preprocessing matters** — removing noise significantly improves model accuracy
2. **TF-IDF + Logistic Regression** is highly effective for binary sentiment classification
3. **VADER** works well without training data, ideal for quick sentiment scoring
4. **Bigrams** (two-word combinations) capture important context like "not good" or "very bad"
5. Supervised ML models outperform lexicon-based approaches on domain-specific data

---

## 📜 License

This project is submitted as part of the **CodTech IT Solutions Data Analytics Internship**.

---

*⭐ If this helped you, consider starring the repository!*
