# 📰 Fake News Detection  

## 📖 Overview  
This project implements a machine learning–based text classification system to detect **fake vs. real news articles**.  
It uses Natural Language Processing (NLP) techniques such as **tokenization, stop-word removal, lemmatization, and TF-IDF vectorization**.  

---

## 🎯 Objectives  
- Classify news articles as **Fake** or **Real**  
- Compare multiple ML models for accuracy  
- Provide a user-friendly **Gradio interface** for real-time testing  

---

## 📂 Dataset  
- Source: [Kaggle Fake News Dataset](https://www.kaggle.com/c/fake-news) *(or update with your dataset link)*  
- Preprocessing:  
  - Removed null values  
  - Cleaned text (tokenization, stop-word removal, lemmatization)  
  - Converted text into TF-IDF features  

---

## ⚙️ Approach  
1. **Data Preprocessing**  
   - Tokenization, stop-word removal, lemmatization  
2. **Feature Extraction**  
   - TF-IDF Vectorization  
3. **Model Training & Comparison**  
   - Logistic Regression ✅ (Best, 98% accuracy)  
   - Decision Tree  
   - Random Forest  
   - Gradient Boosting  
4. **Evaluation Metrics**  
   - Accuracy, Precision, Recall, F1-score  

---

## 📊 Results  
- **Logistic Regression** achieved **98% accuracy**, outperforming other models.  
- Insight: Simpler models can perform better with sparse TF-IDF features.  

---

## 🚀 Deployment  
- Deployed using **Gradio** for real-time predictions.  
- Users can input custom text to check if it’s **Fake** or **Real** news.  

---

## 🛠️ Tech Stack  
- **Programming:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, NLTK / spaCy, Gradio  
- **Version Control:** Git & GitHub  

---

## 📌 Future Improvements  
- Add **Deep Learning models** (LSTM, BERT)  
- Expand dataset for **multilingual fake news detection**  
- Deploy on **Streamlit, Hugging Face Spaces, or Heroku**  

---

## 📬 Contact  
- 👨‍💻 Author: **Lokesh Kumar**  
- 🌐 GitHub: [Lokesh-kumar14](https://github.com/Lokesh-kumar14)  
- 🔗 LinkedIn: [Your LinkedIn Link]  

