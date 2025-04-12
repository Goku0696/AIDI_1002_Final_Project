# AIDI_1002_Final_Project

# 📚 EDA on IMDB: Data Augmentation for Text Classification

This project explores the impact of **Easy Data Augmentation (EDA)** on the **IMDB Movie Reviews** dataset for binary sentiment classification. It is based on the research paper:

> **EDA: Easy Data Augmentation Techniques for Boosting Performance on Text Classification Tasks**  
> 🔗 [arXiv:1901.11196](https://arxiv.org/abs/1901.11196)  
> 💻 GitHub: [https://github.com/jasonwei20/eda_nlp](https://github.com/jasonwei20/eda_nlp)

---

## 📝 Project Overview

- ✅ Reproduces EDA text augmentation on custom sentences.
- ✅ Applies EDA to a real-world dataset (IMDB).
- ✅ Compares Logistic Regression performance on:
  - Original data
  - EDA-augmented data

---


---

## 🚀 Getting Started

###  Clone the Repository,install required libraries and run 
```bash
git clone https://github.com/your-username/EDA_IMDB_Project.git
cd EDA_IMDB_Project


pip install pandas scikit-learn datasets nltk

import nltk
nltk.download('wordnet')
nltk.download('omw-1.4')
nltk.download('punkt')

jupyter notebook AIDI_1002_Final_Project.ipynb



