# 🤖 Intent-Based Chatbot using NLP & TensorFlow Keras

This project is a **from-scratch implementation of an intent-based chatbot**, built to strengthen practical understanding of **Machine Learning, Deep Learning, and Natural Language Processing (NLP)**.

The primary goal of this project is to work through the **end-to-end ML workflow** — from text preprocessing and feature engineering to neural network training, inference, and real-world debugging.

---

## 📌 Project Overview

The chatbot classifies user input into predefined intents and returns an appropriate response.  
It uses traditional NLP techniques combined with a **feed-forward neural network** for intent classification.

This project focuses on **fundamentals, clarity, and practical learning**, rather than using pre-built chatbot frameworks.

---

## 🧠 Key Concepts Covered

- Natural Language Processing (NLP)
  - Tokenization
  - Stemming
  - Bag-of-Words feature representation
- Machine Learning workflow
  - Data preprocessing
  - Feature engineering
  - Model training & inference
- Deep Learning basics
  - Neural network architecture
  - Softmax-based multi-class classification
- Practical debugging & migration
  - Migrating legacy ML code to TensorFlow 2.x
  - Handling data shape mismatches
  - Resolving inference-time errors

---

## ⚙️ Tech Stack

- **Python**
- **NLTK** – text preprocessing
- **NumPy** – numerical operations
- **TensorFlow (Keras API)** – neural network training
- **JSON** – intent definitions

---

## 🏗️ Model Architecture

- **Input Layer:** Bag-of-Words vector
- **Hidden Layers:** Fully connected Dense layers with ReLU activation
- **Output Layer:** Softmax layer for intent classification

---

## 🚀 How the Chatbot Works

1. User input is tokenized and stemmed using NLTK
2. Text is converted into a Bag-of-Words feature vector
3. The neural network predicts intent probabilities
4. The intent with the highest confidence is selected
5. A predefined response is returned to the user

---

## ▶️ How to Run

### Install dependencies
```bash
pip install nltk tensorflow numpy
