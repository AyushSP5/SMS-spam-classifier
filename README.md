# 📩 SMS/Email Spam Classifier

An end-to-end **Machine Learning + NLP project** that classifies SMS/Email messages as **Spam** or **Not Spam**.

## 🚀 Project Overview

The project follows a complete ML workflow:

```text
Data Cleaning → EDA → Text Preprocessing → TF-IDF
→ Model Training → Evaluation → Streamlit Deployment
```

### 🔹 Key Features

* 🧹 Data cleaning and preprocessing
* 📊 Exploratory Data Analysis
* 🔤 NLP text preprocessing using NLTK
* 🔢 TF-IDF vectorization
* 🤖 Multinomial Naive Bayes classification
* 📈 Model evaluation using Accuracy, Precision, Recall & F1-Score
* 🌐 Interactive Streamlit web application

## 🛠️ Technologies Used

* **Python**
* **Pandas & NumPy**
* **NLTK**
* **Scikit-learn**
* **Matplotlib & Seaborn**
* **WordCloud**
* **Streamlit**
* **Pickle**

## 📊 Dataset

The project uses the **SMS Spam Collection Dataset** from the UCI Machine Learning Repository.

Messages are classified into:

* `0` → Not Spam
* `1` → Spam

## 🤖 Model

Several ML algorithms were evaluated, with **Multinomial Naive Bayes** selected for the final classifier due to its strong precision performance on the imbalanced dataset.

## 🌐 Run the Project

Clone the repository:

```bash
git clone https://github.com/AyushSP5/SMS-spam-classifier.git
cd SMS-spam-classifier
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
streamlit run app.py
```

## 📁 Project Structure

```text
SMS-spam-classifier/
│
├── app.py
├── model.pkl
├── vectorizer.pkl
├── requirements.txt
├── notebook.ipynb
└── README.md
```

## 👨‍💻 Author

**Ayush Patil**
Computer Engineering | PCCOE, Pune

⭐ If you find this project useful, consider giving the repository a star!
