# 🧠 Mental Health Message Classifier

## 📌 Project Overview

The Mental Health Message Classifier is a Machine Learning-based web application developed using Python and Streamlit. It analyzes text messages and identifies potentially suicide-related posts using Natural Language Processing (NLP) techniques and a trained classification model.

The application provides a simple interface where users can enter a tweet or message and receive a prediction.

## 🎯 Project Objectives

- Classify text messages based on potentially suicide-related content.
- Apply text preprocessing techniques to clean input data.
- Use Machine Learning for text classification.
- Develop an interactive web application using Streamlit.
- Demonstrate the application of NLP in mental health awareness.

## 🛠️ Technologies Used

- **Python** – Programming language
- **Streamlit** – Web application framework
- **Scikit-learn** – Machine Learning model and text vectorization
- **Joblib** – Model and vectorizer loading
- **Regular Expressions (re)** – Text cleaning
- **String** – Punctuation removal

## 📂 Project Structure

```text
Mental-Health-Message-Classifier/
│
├── app.py
├── model.pkl
├── vectorizer.pkl
└── README.md
```

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Mental-Health-Message-Classifier.git
```

### 2. Navigate to the Project Directory

```bash
cd Mental-Health-Message-Classifier
```

### 3. Install Required Libraries

```bash
pip install streamlit scikit-learn joblib
```

### 4. Run the Application

```bash
streamlit run app.py
```

## 🔍 How It Works

1. Enter a tweet or message in the text input area.
2. Click the **Predict** button.
3. The application preprocesses the input text by removing URLs, mentions, hashtags, and punctuation, then converts it to lowercase.
4. The cleaned text is transformed using the saved vectorizer.
5. The trained Machine Learning model predicts the category.
6. The application displays the prediction.

## 📊 Prediction Results

- ⚠️ **Potential Suicide Post:** The model identifies the message as potentially suicide-related.
- ✅ **Not a Suicide Post:** The model classifies the message as not suicide-related.

## ⚠️ Disclaimer

This project is developed for educational and research purposes only. It is not a clinical diagnostic tool and cannot reliably assess an individual's mental health or suicide risk. Model predictions should not replace professional mental health assessment or support.

## 👨‍💻 About the Author

**S VIGNESH**

An aspiring Data Analyst and Machine Learning enthusiast passionate about exploring real-world problems through Python, data analytics, and artificial intelligence. Interested in developing practical applications using Machine Learning and Natural Language Processing to transform data into meaningful insights.

**Areas of Interest:**
- Machine Learning
- Natural Language Processing (NLP)
- Python Programming
- Data Analytics
- Artificial Intelligence

## ⭐ Support

If you find this project interesting, please consider giving this repository a ⭐ star!

**Developed by S VIGNESH**
