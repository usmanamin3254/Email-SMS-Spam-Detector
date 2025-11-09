# 📧 AI Spam Detector | Email & SMS

![Python Version](https://img.shields.io/badge/python-3.13.7+-blue)
![Streamlit Version](https://img.shields.io/badge/streamlit-1.25.0-orange)
![License: MIT](https://img.shields.io/badge/License-MIT-green)

**AI-powered Email & SMS Spam Detector** that instantly identifies whether a message is **Spam** or **Safe**, leveraging **Natural Language Processing (NLP)** and **Machine Learning (ML)** techniques.

---

## 🖼️ Project Showcase

| Home Page | Enter Message |
|-----------|---------------|
| ![Home Page](images/home_page.png) | ![Enter Message](images/enter_message.png) |

| Spam Detection Result | Safe Message Result |
|---------------------|------------------|
| ![Spam Result](images/spam_result.png) | ![Safe Result](images/safe_result.png) |

---

## 🌟 Features

- **Instant Spam Detection** for emails and SMS messages.
- **Modern, responsive UI** with **light & dark mode** support.
- **NLP-powered text preprocessing** using NLTK:
  - Tokenization  
  - Stopword removal  
  - Stemming  
- **Machine Learning model** for accurate predictions.
- **Real-time results** with clear visual feedback.
- **User-friendly design** with polished input areas and interactive buttons.

---

## 🛠️ Technology Stack

- **Frontend / UI:** [Streamlit](https://streamlit.io/)  
- **Text Preprocessing & NLP:** NLTK (Tokenization, Stopwords, Stemming)  
- **Machine Learning:** Pre-trained model with TF-IDF vectorizer  
- **Programming Language:** Python 3.10+  
- **Data Storage:** Pickle files (`model.pkl`, `vectorizer.pkl`)  

---

## ⚡ Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/ai-spam-detector.git
cd ai-spam-detector

Create a virtual environment:

python -m venv venv
# Activate environment
source venv/bin/activate   # Linux / Mac
venv\Scripts\activate      # Windows

Install dependencies:

pip install -r requirements.txt

Ensure the following files are in the project root:

model.pkl → Pre-trained machine learning model

vectorizer.pkl → TF-IDF vectorizer

🚀 Usage

Run the Streamlit app:

streamlit run app.py

Enter an email or SMS message in the text area.

Click 🔍 Analyze Message.

The app will instantly show whether the message is Spam (🔴) or Safe (🟢).

👨‍💻 Author

Usman Amin
© 2025 AI Spam Detector Project
