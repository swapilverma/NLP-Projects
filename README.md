# 📝 Multiple NLP Projects  

This repository contains **Natural Language Processing (NLP)** projects focused on text classification and sentiment analysis. The goal is to explore different feature extraction techniques and apply machine learning models to derive meaningful insights from textual data.

## 📂 Project Overview  

### 1️⃣ Spam vs. Ham Classification  
- **Objective:** Classify messages as **Spam** or **Ham** (Not Spam).  
- **Techniques Used:**  
  - Bag of Words (BOW)  
  - TF-IDF (Term Frequency-Inverse Document Frequency)  
  - Word2Vec  
  - Average Word2Vec  
- **Models Applied:**  
  - Multinomial Naïve Bayes
  - Gaussion Naïve Bayes      

### 2️⃣ Kindle Review Sentiment Analysis  
- **Objective:** Perform sentiment analysis on Kindle product reviews to classify them as **Positive or Negative**.  
- **Techniques Used:**  
  - Bag of Words (BOW)  
  - TF-IDF  
- **Models Applied:**  
  - Random Forest  

---

## 🛠️ Tools and Libraries Used  
- **Programming Language:** Python  
- **Libraries:**  
  - `pandas` - Data manipulation  
  - `nltk`  - Text preprocessing  
  - `scikit-learn` - Feature extraction and modeling  
  - `matplotlib` & `seaborn` - Data visualization  

---

## 📈 Results and Observations  

### 📌 Spam vs. Ham Classification  
- **TF-IDF** performed better than **BOW** with an accuracy of 97%.  
- **Avg Word2Vec** provided the accuracy of 96% with Random forest Classifier.
- Mutlinomial Naive Bayes provied better accuracy then Random forest classifer even though it was used with TF-IDF.   

### 📌 Kindle Review Sentiment Analysis  
- **TF-IDF** showed **BOW** showed similar results with accuracy of 58%.   

---

## 🚀 How to Use  

1. Clone the repository:  
   ```bash
   git clone https://github.com/swapilverma/NLP-Projects.git
