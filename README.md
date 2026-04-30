# NLP-project-for-extract-user-performance-for-text
# 🔍 NLP User Performance Analyzer (Google Colab)

## 📌 Project Overview

This project implements a **Natural Language Processing (NLP)** system to analyze user-provided text and extract meaningful insights such as sentiment, performance level, and keywords.

The entire project is developed and executed using **Google Colab**, making it easy to run without local setup.

---

## 🎯 Objectives

* Analyze user input text dynamically
* Perform sentiment analysis using NLP
* Classify performance levels (High / Average / Low)
* Extract keywords from text
* Handle edge cases like empty or stopword-only input

---

## 🚀 Features

* ✅ Runs completely in Google Colab (no installation required)
* ✅ Real-time text input using `input()`
* ✅ Sentiment analysis using VADER
* ✅ Performance classification
* ✅ Keyword extraction
* ✅ Error handling for empty inputs
* ✅ Lightweight and beginner-friendly

---

## 🧠 How It Works

### 1. Text Preprocessing

* Convert text to lowercase
* Remove special characters
* Remove stopwords
* Clean and normalize input

### 2. Sentiment Analysis

* Uses VADER from NLTK
* Calculates sentiment score
* Classifies text into:

  * Positive
  * Neutral
  * Negative

### 3. Performance Mapping

* Positive → High
* Neutral → Average
* Negative → Low

### 4. Keyword Extraction

* Extracts top words from cleaned text
* Provides quick insight into feedback

---

## 🛠️ Technologies Used

* Python
* Natural Language Processing (NLP)
* NLTK
* Regular Expressions
* Google Colab

---

## ▶️ How to Run (Google Colab)

1. Open Google Colab
2. Copy and paste the code into a notebook
3. Run all cells
4. Enter text when prompted

---

## 🧪 Example

### Input:

```text
The support team was very helpful and quick
```

### Output:

* Sentiment: Positive
* Performance: High
* Keywords: support, helpful, quick

---

## ⚠️ Limitations

* Rule-based sentiment model (VADER)
* Limited context understanding
* Basic keyword extraction

---

## 🔮 Future Improvements

* Add machine learning models (Logistic Regression / BERT)
* Build a web interface (Streamlit / Gradio)
* Add visualization dashboards
* Support multiple languages

---

## 💡 Use Cases

* Customer feedback analysis
* Employee performance evaluation
* Product review analysis
* Social media sentiment tracking

---

## 👨‍💻 Author

Developed as part of an NLP learning project using Google Colab.

---

## ⭐ Conclusion

This project demonstrates how NLP techniques can convert raw text into meaningful insights. It provides a strong foundation for building advanced text analytics systems.
