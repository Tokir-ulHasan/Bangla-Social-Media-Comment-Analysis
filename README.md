# 📘 Bangla Social Media Comment Analysis — Sentiment & Topic Classification

RNN & LSTM-based Deep Learning Models (TensorFlow/Keras)

This repository contains all code required to train, evaluate, and run inference on Bangla social media comments using **Simple RNN** and **LSTM** architectures.

The project performs two tasks:

* **Sentiment Classification**
* **Topic Classification**

Models are trained from scratch using TensorFlow/Keras, and all artifacts (tokenizer, label encoders, saved weights) are included.

---

## 🧠 Models Used in This Project

This project uses **exactly the architectures implemented in your notebook:**

### ✔️ **Simple RNN Model**

Used for the first version of **sentiment classification**:

* Embedding layer
* SimpleRNN layer
* Dense layers
* Softmax output

### ✔️ **LSTM Model**

Used for the final **sentiment** and **topic** models:

* Embedding
* LSTM layer(s)
* Dropout
* Dense + Softmax

## 🔧 Installation

### 1️⃣ Create a virtual environment

```bash
python -m venv venv
source venv/bin/activate      # Windows: venv\Scripts\activate
```

### 2️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

---

---

## Demo

Example:

```text
Write a Bangla comment: খাবারটা খুবই খারাপ ছিল
Predicted Topic: food
Predicted Sentiment: negative
```
---

## 📝 Sample Input/Output

Example content:

```json
{
  "input_comment": "মাংসে সর্বোচ্চ ৩০ প্রকারের মসলা ...",
  "predicted_topic": "food",
  "predicted_sentiment": "negative"
}
```

---

## 📦 Requirements

```
tensorflow
keras
pandas
numpy
scikit-learn
matplotlib
seaborn
```



# sample input - output
<img width="1920" height="1080" alt="Screenshot (36)" src="https://github.com/user-attachments/assets/5cd9b717-d465-4e4b-af9a-87c6119bc848" />
