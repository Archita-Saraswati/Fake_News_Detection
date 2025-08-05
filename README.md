# 📰 Fake News Detection using Machine Learning

This project aims to detect whether a news article is **real** or **fake** using Natural Language Processing (NLP) and Machine Learning techniques. It leverages textual data and classification algorithms to identify misinformation automatically.

## 📌 Objective
To build a binary text classifier that can differentiate between real and fake news using supervised learning models.

---

## 🛠️ Technologies Used

### 📌 Programming Language:
- Python 3.x

### 📚 Libraries and Frameworks:
- **Pandas** – Data manipulation
- **NumPy** – Numerical operations
- **Scikit-learn** – ML algorithms, TF-IDF, evaluation
- **NLTK** – Natural Language Toolkit for text preprocessing
- **re** – Regular expressions for text cleaning

### 💻 Development Environment:
- Jupyter Notebook

---

## 📂 Dataset
The dataset contains **labeled news articles** classified as `REAL` or `FAKE`.

- Format: CSV
- Fields include: `title`, `text`, `label`

---

## 🧠 Machine Learning Models Used
- **Logistic Regression**
- **Naive Bayes Classifier**
- **Passive Aggressive Classifier**

---

## 🔄 Workflow

1. **Data Preprocessing**
   - Remove punctuation, symbols, numbers
   - Lowercasing
   - Remove stopwords
   - Tokenization

2. **Feature Extraction**
   - Convert text to numerical vectors using **TF-IDF (Term Frequency-Inverse Document Frequency)**

3. **Model Building**
   - Train ML models on training data
   - Evaluate using accuracy score

4. **Model Evaluation**
   - Accuracy comparison
   - Confusion matrix (optional)

---

## 📈 Results
- Accuracy metrics for each model were compared to select the best-performing classifier.
- Logistic Regression or Passive Aggressive Classifier generally provides high accuracy in such NLP problems.

---


