

> An end-to-end Natural Language Processing (NLP) project for classifying SMS messages as **Spam** or **Ham** using TensorFlow/Keras and Deep Learning.

![Python](https://img.shields.io/badge/Python-3.12-blue?logo=python)
![TensorFlow](https://img.shields.io/badge/TensorFlow-Deep%20Learning-orange?logo=tensorflow)
![Keras](https://img.shields.io/badge/Keras-Neural%20Networks-red?logo=keras)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-f7931e?logo=scikitlearn)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![License](https://img.shields.io/badge/License-MIT-green)

---

# 📌 Project Overview

Spam messages remain one of the biggest challenges in digital communication. Manual filtering is inefficient, and traditional rule-based systems often fail to detect evolving spam patterns.

This project develops a **Deep Learning-based Natural Language Processing (NLP)** model capable of automatically classifying SMS messages into **Spam** or **Ham (Legitimate Messages)**.

The project demonstrates an end-to-end machine learning workflow including:

- Data preprocessing
- Text cleaning
- Tokenization
- Sequence padding
- Model development
- Model evaluation
- Prediction

---

# 📊 Project Snapshot

| Feature | Details |
|----------|---------|
| Problem | SMS Spam Detection |
| Task | Binary Text Classification |
| Dataset | SMS Messages |
| Samples | 5,572 |
| Classes | Spam / Ham |
| Framework | TensorFlow / Keras |
| Language | Python |

---

# 📂 Dataset

The dataset contains SMS text messages labelled as either:

- Ham (Legitimate Messages)
- Spam Messages

### Dataset Columns

| Column | Description |
|----------|------------|
| Category | Message Label |
| Message | SMS Text |

---

# ⚙️ Data Preprocessing

The following preprocessing steps were performed before training:

- Loading the dataset with Pandas
- Removing punctuation
- Lowercasing text
- Removing stopwords
- Text tokenization
- Sequence padding
- Label encoding
- Train/Test split

These preprocessing steps convert raw text into numerical sequences that can be processed by a deep learning model.

---

# 🧠 Model Architecture

The deep learning architecture used in this project is shown below.

```
Input SMS

      │

      ▼

Embedding Layer

      │

      ▼

GlobalAveragePooling1D

      │

      ▼

Dense Layer (ReLU)

      │

      ▼

Dense Layer

      │

      ▼

Sigmoid Output

      │

      ▼

Spam / Ham Prediction
```

---

# 📈 Model Evaluation

The model was evaluated using multiple classification metrics including:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- Confusion Matrix

A Logistic Regression model was also trained as a baseline for comparison.

---

# 📚 Technologies Used

- Python
- TensorFlow
- Keras
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- NLTK

---

# 🔄 Project Workflow

```
SMS Message

      │

      ▼

Text Cleaning

      │

      ▼

Tokenization

      │

      ▼

Padding

      │

      ▼

Embedding Layer

      │

      ▼

Deep Learning Model

      │

      ▼

Prediction

      │

      ▼

Spam / Ham
```

---

# 📁 Repository Structure

```
spam-detection-nlp/

│── README.md

│── requirements.txt

│── .gitignore

│── notebooks/

│      └── spam_detection.ipynb

│── data/

│      └── mail_data.csv

│── images/

│── report/
```

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/Liquidfingers/spam-detection-nlp.git
```

Move into the project directory

```bash
cd spam-detection-nlp
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

# 🎯 Skills Demonstrated

This project demonstrates practical experience in:

- Natural Language Processing
- Deep Learning
- Binary Classification
- TensorFlow/Keras
- Text Preprocessing
- Feature Engineering
- Model Evaluation
- Machine Learning

---

# 🚀 Future Improvements

Future versions of this project could include:

- Long Short-Term Memory (LSTM) Networks
- Gated Recurrent Units (GRU)
- Transformer Models
- BERT
- Hyperparameter Optimization
- Streamlit Deployment
- FastAPI Deployment

---

# 👨‍💻 Author

**Victor Nnamani**

Machine Learning Engineer | Data Engineer | Deep Learning Enthusiast

---

⭐ If you found this project useful, consider giving it a star!
