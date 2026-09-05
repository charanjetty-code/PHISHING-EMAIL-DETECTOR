# 🛡️ Phishing Email Detection Model

**Author:** JETTY CHARAN  
**License:** MIT License  
**Project Type:** Machine Learning / Security Application  

A machine learning-powered security application built with **Python, Scikit-learn, and Web Technologies** that detects phishing emails by analyzing text content, embedded URLs, urgent trigger keywords, and structural characteristics.

---

## 📌 Project Overview

Phishing attacks remain one of the top cyber threats today. This project provides an end-to-end Machine Learning pipeline that extracts hybrid features (NLP + Structural metadata) to classify incoming emails as either **Phishing** or **Safe** with high accuracy.

It includes:
- **Feature Extraction Engine**: Analyzes textual content (TF-IDF) alongside structural signals (IP addresses, suspicious domains, keyword scores, exclamation marks).
- **Machine Learning Models**: Uses Naive Bayes & Random Forest classifiers trained on email text data.
- **Interactive Web Interface**: A visual dashboard allowing users to test custom emails, inspect detected risk indicators, and view model evaluation metrics (Confusion Matrix, Accuracy, ROC Curve).

---

## 🌟 Key Features

* **Hybrid Feature Engineering**: Combines natural language processing (TF-IDF) with custom heuristic features (URL counts, IP link detection, urgent keyword density).
* **High-Accuracy Classification**: Evaluates emails and assigns a real-time confidence score.
* **Visual Inspector**: Highlights suspicious URLs, domain spoofs, and high-risk trigger words directly within the email body.
* **Interactive Model Evaluation**: Displays real-time model accuracy, confusion matrix, precision/recall stats, and top predictor features using Chart.js.
* **Exportable Python Engine**: Clean, documented Scikit-learn backend ready for deployment or academic submission.

---

## 🛠️ Tech Stack

- **Core Language:** Python 3.x
- **Machine Learning:** Scikit-learn, NumPy, Pandas
- **Natural Language Processing:** TF-IDF Vectorization, NLTK / Regex
- **Frontend / Dashboard:** HTML5, Tailwind CSS, JavaScript (ES6+), Chart.js
- **Icons & Styling:** Lucide Icons / FontAwesome

---

## 📂 Repository Structure
