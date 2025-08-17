# 📈 Stock Market News Sentiment Analysis  

## 📝 Project Overview  
This project applies **Natural Language Processing (NLP)** techniques to analyze stock market news headlines and classify their sentiment into **Positive, Negative, or Neutral**.  
By understanding how financial news affects investor sentiment, this model can assist traders and analysts in market decision-making.  

---

## 📊 Dataset  
- Source: **Kaggle – Stock Market News Dataset**  
- Size: ~4,000 news headlines labeled with sentiment.  
- Columns:  
  - `News Headline` → textual input  
  - `Sentiment` → target label (Positive / Negative / Neutral)  

---

## 🔬 Methodology  

### 1. Data Preprocessing  
- Lowercasing text  
- Removing punctuation & numbers  
- Stopword removal (`nltk`)  
- Lemmatization  
- Tokenization  

### 2. Feature Engineering  
- **Bag of Words (CountVectorizer)**  
- **TF-IDF Vectorization**  

### 3. Models Implemented  
- Logistic Regression  
- Naive Bayes  
- Random Forest  
- Support Vector Machine (SVM)  

### 4. Model Evaluation  
Metrics used:  
- Accuracy Score  
- Confusion Matrix  
- Classification Report (Precision, Recall, F1-Score)  

---

## 📈 Results  

| Model                | Accuracy |
|-----------------------|----------|
| Logistic Regression  | **92.7%** |
| Naive Bayes          | 88.3% |
| Random Forest        | 90.2% |
| SVM                  | 91.4% |

- Logistic Regression achieved the **highest accuracy (92.7%)**, making it the best-performing model in this study.  
