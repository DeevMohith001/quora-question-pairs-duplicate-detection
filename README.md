# quora-question-pairs-duplicate-detection
NLP-based duplicate question detection using the Quora Question Pairs dataset (Kaggle Challenge).

# Quora Question Pairs - Duplicate Detection 🧠

This project is a solution to the [Quora Question Pairs](https://www.kaggle.com/c/quora-question-pairs) challenge on Kaggle. The goal is to identify whether two questions asked on Quora are semantically similar or not.

Achieved ~80% accuracy using traditional machine learning techniques and detailed NLP analysis under the guidance of Nitish Singh (CampusX) after completing his NLP course.

## 🔍 Problem Statement
Given pairs of questions, predict whether they are duplicates (i.e., have the same intent).

## 📦 Dataset
Available on Kaggle: https://www.kaggle.com/c/quora-question-pairs  
📁 *Due to Kaggle policy, data is not included. Please download it manually.*

## 🛠️ Techniques Used
- Text Preprocessing: tokenization, lemmatization, stopword removal
- Feature Engineering: TF-IDF, Jaccard similarity, fuzzy matching
- Embeddings: Word2Vec and GloVe
- Models: Logistic Regression, XGBoost
- Evaluation: Accuracy, Log Loss

## 📈 Current Performance
- ✅ Accuracy: ~80%
- 🔧 Work in progress to further improve using Siamese Networks and deep learning models

## 🗂️ Repository Structure
- `notebooks/`: Jupyter notebooks with experiments
- `src/`: Python scripts for preprocessing, feature extraction, and training
- `models/`: (optional) saved models
- `results/`: visualizations and evaluation outputs

## 👨‍🏫 Mentor
Guided by **Nitish Singh (CampusX)** as part of his NLP specialization course.

## 🤝 Let's Connect
If you have suggestions, feedback, or want to collaborate on improving this project, feel free to reach out!

---

