# 📩 Spam Detection using Deep Learning

## 📌 Project Overview

This project presents an end-to-end Natural Language Processing (NLP) solution for detecting spam SMS messages using Deep Learning.

The objective is to automatically classify SMS messages into:

- ✅ Ham (Legitimate Messages)
- 🚫 Spam Messages

The project demonstrates the complete machine learning workflow, including data preprocessing, feature engineering, model development, evaluation, and prediction.

---

## 📂 Dataset

The dataset contains SMS messages labelled as either **Spam** or **Ham**.

### Features

| Column | Description |
|---------|-------------|
| Category | Spam or Ham |
| Message | SMS Text |

The dataset was preprocessed before training to improve model performance.

---

## ⚙️ Data Preprocessing

The following preprocessing techniques were applied:

- Removal of punctuation
- Lowercasing text
- Stopword removal
- Tokenization
- Sequence Padding
- Label Encoding
- Train/Test Split

---

## 🧠 Deep Learning Model

Model Architecture

Input

⬇️

Embedding Layer

⬇️

GlobalAveragePooling1D

⬇️

Dense Layer (ReLU)

⬇️

Dense Layer

⬇️

Sigmoid Output

---

## 📊 Model Evaluation

The project was evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- Confusion Matrix

The notebook also compares the deep learning model with a Logistic Regression baseline.

---

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- NLTK

---

## 📁 Repository Structure

```
spam-detection-nlp

├── README.md
├── requirements.txt
├── .gitignore
├── notebooks/
├── data/
├── images/
└── report/
```

---

## 🚀 How to Run

Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/spam-detection-nlp.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

Open

```
spam_detection.ipynb
```

Run all cells.

---

## 📈 Future Improvements

Future versions of this project may include:

- LSTM Networks
- GRU Networks
- Transformer Models
- BERT
- Hyperparameter Optimization
- Deployment with Streamlit or Flask

---

## 👨‍💻 Author

Victor Nnamani

Machine Learning | Data Engineering | Deep Learning
