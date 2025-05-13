# 🧠 NLP Preprocessing with NLTK (Lecture 1)

This project demonstrates basic Natural Language Processing (NLP) techniques using Python's [NLTK (Natural Language Toolkit)](https://www.nltk.org/). It includes tokenization, stemming, lemmatization, stopword removal, and feature extraction using the Bag of Words model.

---

## 📌 Key Concepts Covered

### 1. **Library Installation**
- `nltk` is installed to use its text-processing capabilities.

### 2. **Text Preparation**
- A sample paragraph about Narendra Modi is used for analysis.

### 3. **Tokenization**
- Splitting text into sentences (`sent_tokenize`) and words (`word_tokenize`).

### 4. **Stemming**
- Words are reduced to their root form using `PorterStemmer`.

### 5. **Lemmatization**
- Words are converted to their base form using grammar rules via `WordNetLemmatizer`.

### 6. **Stopword Removal**
- Common words like "the", "is", "in" are removed to focus on meaningful words.

### 7. **Text Cleaning**
- Regular expressions are used to remove punctuation and convert text to lowercase.

### 8. **Bag of Words Model**
- `CountVectorizer` from `scikit-learn` is used to convert text into numerical vectors for machine learning.

---

## 🧾 Requirements

Install dependencies using pip:
```bash
pip install nltk scikit-learn
