# AI-Based Spam Message Detection System

## 📌 Overview

This project is a machine learning-based system that classifies SMS messages as **Spam** or **Not Spam (Ham)** using Natural Language Processing (NLP) techniques.

The goal is to solve the real-world problem of unwanted and potentially harmful spam messages.

---

## 🚀 Features

* Classifies messages into Spam or Not Spam
* Uses NLP techniques for text processing
* Trained using machine learning algorithms
* Simple and easy-to-use interface (optional Streamlit app)

---

## 🧠 Technologies Used

* Python
* Scikit-learn
* Pandas
* NumPy

---

## 📂 Project Structure

```
spam-detector/
│
├── data/
│   └── spam.csv
│
├── src/
│   ├── train.py
│   └── predict.py
│
├── app.py
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation

1. Clone the repository:

```
git clone https://github.com/rishabh-3296/AI-and-ML-Project.git
```

2. Navigate to project folder:

```
cd spam-detector
```

3. Install dependencies:

```
pip install -r requirements.txt
```

---

## ▶️ Usage

### Train the Model

```
python src/train.py
```

### Predict a Message

```
python src/predict.py
```

---

## 💡 Example

Input:

```
"Congratulations! You have won a free ticket"
```

Output:

```
Spam
```

---

## 📊 Methodology

* Data Cleaning
* Text Vectorization using TF-IDF
* Model Training using Naive Bayes
* Prediction

---

## 📌 Future Improvements

* Add deep learning models
* Improve accuracy with larger dataset
* Deploy as a web application

---

## 👨‍💻 Author

Rishabh Raj

