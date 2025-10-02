# News Classifier (ML Model)

This project is a **machine learning text classification model** built using **scikit-learn**.  
It classifies text data (e.g., news articles) into predefined categories.  

The model is trained using:
- **CountVectorizer** (feature extraction)
- **TfidfTransformer** (feature scaling)
- A **classifier** (e.g., Naive Bayes / Logistic Regression / SVM)

The trained model is saved as `model.pkl` using **joblib** for easy reuse.

---

## 🚀 Features
- Preprocesses text using Bag-of-Words & TF-IDF.
- Trains a machine learning classifier for text classification.
- Saves and loads the trained model (`model.pkl`).
- Can be easily integrated into applications (Flask, FastAPI, Streamlit, etc.).

---

---

## ⚙️ Installation
Clone the repository and install dependencies:

```bash
git clone https://github.com/<your-username>/news-classifier.git
cd news-classifier
pip install -r requirements.txt

