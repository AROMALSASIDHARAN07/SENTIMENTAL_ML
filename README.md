# Emotion Classification 📝🎭

This repository demonstrates **text-based emotion classification** using machine learning.  
It uses **Naive Bayes** and **SVM** with **TF-IDF** features to classify text into different emotions.

---

## 🚀 Features Covered

- Text Cleaning & Preprocessing  
- Stopword Removal  
- Lowercasing  
- TF-IDF Feature Extraction  
- Label Encoding  
- Emotion Classification with Naive Bayes  
- Emotion Classification with SVM  
- Model Evaluation (Accuracy, F1-score, Classification Report)  

---

## 🛠️ Technologies & Libraries Used

- Python 🐍  
- pandas  
- NLTK  
- scikit-learn  
- joblib  

---

## 📌 Project Steps Explained

### 1️⃣ Text Preprocessing  
- Converts text to lowercase  
- Removes punctuation and numbers  
- Removes stopwords  

### 2️⃣ Feature Extraction  
- Uses **TF-IDF** to convert text into numerical features  

### 3️⃣ Label Encoding  
- Converts emotion labels into numeric format for modeling  

### 4️⃣ Model Training  
- **Naive Bayes (MultinomialNB)**  
- **Support Vector Machine (LinearSVC)**  

### 5️⃣ Model Evaluation  
- Measures **accuracy**, **F1-score**, and outputs **classification report**  

### 6️⃣ Model & Vectorizer Saving  
- Saves models: `naive_bayes_model.pkl`, `svm_model.pkl`  
- Saves TF-IDF vectorizer: `tfidf_vectorizer.pkl`  
- Saves label encoder: `label_encoder.pkl`  

---

## 📂 Project Structure

