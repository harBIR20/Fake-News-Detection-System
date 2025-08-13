# 📰 Fake News Detection System

## 📌 Introduction
The **Fake News Detection System** is a machine learning-based project designed to combat the spread of false information in the digital era. It classifies news articles into two categories:
- **Real News**
- **Fake News**

By leveraging multiple machine learning algorithms, the system achieves high accuracy in detecting potentially misleading information.

---

## 🎯 Motivation
The rapid rise of **fake news and misinformation** has become a significant concern in today’s information landscape. Misleading or false information can influence:
- Public opinion
- Decision-making
- Democratic processes

This project aims to help users identify deceptive news articles, promoting informed and critical thinking when consuming online information.

---

## 📂 Project Overview

### 1️⃣ Data Collection
- Collected a diverse dataset of both **genuine** and **fabricated** news articles.
- Dataset includes multiple sources and a variety of topics for better generalization.

### 2️⃣ Data Preprocessing
- Text cleaning & tokenization
- Stopword removal
- Feature extraction
- Train-test dataset splitting

### 3️⃣ Feature Engineering
- **TF-IDF** (Term Frequency–Inverse Document Frequency)
- Word embeddings (**Word2Vec** / **GloVe**) for semantic understanding

### 4️⃣ Model Training
Four machine learning models were implemented and tuned:
- **Logistic Regression** – A robust linear classifier.
- **Random Forest** – Ensemble method combining multiple decision trees.
- **Decision Tree** – Simple yet powerful classification approach.
- **Gradient Boosting Classifier** – Sequential ensemble for improved accuracy.

### 5️⃣ Model Evaluation
Metrics used:
- Accuracy
- Precision
- Recall
- F1-Score

---

## 📊 Results

| Model                        | Accuracy |
|------------------------------|----------|
| Logistic Regression          | 97%      |
| Random Forest                | 99%      |
| Decision Tree                | 99%      |
| Gradient Boosting Classifier | 97%      |

These results demonstrate that the models are highly effective in distinguishing between real and fake news.

---

## 🚀 Installation & Usage

### Prerequisites
- Python 3.8+
- pip (Python package manager)
- 
## Steps
## Clone the repository
git clone https://github.com/your-username/fake-news-detection.git
cd fake-news-detection

## Install dependencies
pip install -r requirements.txt

## Run the project
python main.py

## 🛠 Technologies Used:
Python
scikit-learn
pandas, numpy

NLTK / spaCy (for text preprocessing)

Matplotlib / Seaborn (for visualization)

## 📌 Future Improvements
Integrating deep learning models (LSTM, BERT)

Expanding dataset with real-time news scraping

Building a web interface for public use

## 📜 License
This project is licensed under the MIT License – feel free to use, modify, and distribute it.

## 🤝 Contributing
Contributions are welcome!

Fork the repository

Create your feature branch

Commit changes

Push to the branch

Create a Pull Request
