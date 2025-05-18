# 💬 Emotion Detection from Text

This is a simple machine learning web app built using **Streamlit** that predicts the **emotion** (Happy, Sad, Angry) from input text using a trained ML model.

---

## 🚀 Features

- Predicts 3 emotions: **happy**, **sad**, **angry**
- Uses `neattext` for smart text preprocessing
- Built-in text cleaning and vectorization
- Fast inference using a saved `MultinomialNB` model
- Clean, minimal Streamlit interface
- Fully offline — no APIs needed

---

## 🧠 Model Info

- Dataset: Filtered to only include `sad`, `happy`, `angry` labels
- Preprocessing: `neattext` for cleaning, `TfidfVectorizer` for encoding
- Model: `Multinomial Naive Bayes` from `scikit-learn`
- Saved using `joblib`

---

## 🗂️ Project Structure

```
emotion-detector/
│
├── app.py                      # Streamlit app
├── emotion_model.pkl           # Trained model
├── tfidf_vectorizer.pkl        # TF-IDF vectorizer
├── filtered_emotion_dataset.csv  # Cleaned dataset (optional)
├── requirements.txt            # Python dependencies
└── README.md                   # Project documentation
```

---

## ✅ Installation Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/Smohanty834/emotion-detector.git
cd emotion-detector
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the Streamlit App

```bash
streamlit run app.py
```
---

## 🙋‍♂️ Author

**Your Name**  
GitHub: [@Smohanty834](https://github.com/Smohanty834)
