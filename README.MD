# 📰 Fake News Detection System

A Machine Learning-based web application that detects whether a news article is **REAL** or **FAKE** using Natural Language Processing (NLP).

---

## 🚀 Project Overview

This project uses text classification techniques to analyze news content and predict its authenticity. It is built using Python, Machine Learning, and Flask for deployment.

---

## 🧠 Technologies Used

* Python 🐍
* Flask 🌐
* Scikit-learn 🤖
* Pandas 📊
* NumPy 🔢
* TfidfVectorizer 🧾
* PassiveAggressiveClassifier ⚡

---

## 📂 Project Structure

fake-news-detection/
│
├── app.py                  # Flask application
├── finalized_model.pkl     # Trained ML model
├── vectorizer.pkl          # TF-IDF vectorizer
├── templates/
│   ├── index.html          # Input page
│   └── prediction.html     # Result page
├── dataset/                # Dataset (optional or external)
└── README.md               # Project documentation

---

## 📊 Dataset

The dataset contains labeled news articles categorized as:

* REAL
* FAKE



Dataset Link: []

---

## ⚙️ How It Works

1. User enters news text in the web interface.
2. Text is transformed using **TF-IDF Vectorization**.
3. The trained model predicts:

   * Fake ❌
   * Real ✅
4. Result is displayed on the screen.

---

## 🛠️ Installation & Setup

### 1. Clone the Repository

git clone https://github.com/VanshBanga/fake-news-detection.git
cd fake-news-detection

---

### 2. Install Dependencies

pip install flask pandas scikit-learn numpy

---

### 3. Run the Application

python app.py

---

### 4. Open in Browser

http://127.0.0.1:5000/

---

## 🧪 Model Details

* Algorithm: Passive Aggressive Classifier
* Vectorization: TF-IDF
* Accuracy: Add your accuracy here

---

## 📸 Screenshots (Optional)


## 🔮 Future Improvements

* Improve accuracy with deep learning (LSTM, BERT)
* Add multilingual support 🌍
* Deploy on AWS / Render / Heroku ☁️
* Add user authentication 🔐

---

## 🤝 Contributing

Feel free to fork this repository and contribute!

---

## 📄 License

This project is open-source and available under the MIT License.

---

## 👨‍💻 Author

**Vansh Banga**
B.Tech AI Student

---
