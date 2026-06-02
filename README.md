# 🧠 Machine Learning – NLP & Sentiment Analysis

A collection of hands-on machine learning projects from my M.Sc. in Artificial Intelligence at Østfold University College (HiØ), Norway.

---

## 📌 Featured Project: Twitter Sentiment Analysis

**Goal:** Classify the sentiment of tweets into four categories — *Positive*, *Negative*, *Neutral*, or *Mixed* — using both traditional ML and deep learning models.

**Dataset:** Twitter Entity Sentiment dataset (~74,000 tweets across companies, brands, and products such as Amazon, Google, and FIFA)

### What I built

| Model | Type | Notes |
|---|---|---|
| Decision Tree | Traditional ML | Baseline classifier |
| Random Forest | Traditional ML | Ensemble with bagging |
| Shallow Neural Network | Deep Learning (PyTorch) | Simple feedforward |
| Mid-Sized Neural Network | Deep Learning (PyTorch) | Dropout + batch normalization |
| Deep Residual Network | Deep Learning (PyTorch) | Residual connections to combat vanishing gradients |

### Pipeline

```
Raw Tweets
    → Text Preprocessing (emoji handling, stop words, lemmatization)
    → Feature Extraction (TF-IDF vectorization)
    → Model Training & Evaluation
    → Interactive Predictions
```

### Evaluation metrics used
- Accuracy, Precision, Recall, F1-score
- Confusion matrices
- Precision-recall curves

---

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3.10-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-2.x-orange)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.x-green)
![Pandas](https://img.shields.io/badge/Pandas-2.x-blue)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)

- **PyTorch** — Neural network design and training
- **Scikit-learn** — Traditional ML models and evaluation
- **Pandas / NumPy** — Data loading, cleaning, and exploration
- **Matplotlib / Seaborn** — Visualization

---

## 📂 Structure

```
Machine_learning/
├── sentiment_analysis/
│   ├── sentiment_analysis.ipynb   # Main notebook
│   ├── twitter_training.csv       # Training dataset
│   └── twitter_test.csv           # Test dataset
└── README.md
```

---

## 🎓 About

These projects were completed as part of my double M.Sc. in:
- **Artificial Intelligence** — Østfold University College, Norway (2023–2025)
- **IT, Digitalisation & Sustainability** — Lucerne University of Applied Sciences, Switzerland (2023–2025)


📫 Connect with me on linkedin.com/in/mohamad-chamsi-5878772b9

 email : mohamad.chamsi@outlook.com
