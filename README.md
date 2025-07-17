# 🧠 Stack Overflow Tag Prediction using NLP & Streamlit

A real-time web app that predicts relevant Stack Overflow tags based on user-submitted questions using natural language processing (NLP) and a machine learning classification model.

🔗 **Live Demo**: [Try it on Hugging Face Spaces 🚀](https://huggingface.co/spaces/sahitya6183/Stack_Over_FLow)

---

## 🔍 Short Description / Purpose

This project uses NLP techniques and a multi-label classification model to predict the most relevant tags for a Stack Overflow post, based on its title and body. It aims to help developers quickly categorize their questions and receive more accurate community support.

---

## 💻 Tech Stack

The project was developed using the following technologies:

- 🐍 **Python** – Core programming language  
- 📚 **scikit-learn** – For TF-IDF vectorization and MLPClassifier  
- 🔤 **NLP** – HTML cleaning, stopword removal, lemmatization  
- 🌐 **Streamlit** – For building the interactive web interface  
- 🤗 **Hugging Face Spaces** – Hosting the deployed web application

---

## 🗃️ Dataset

- Source: [Stack Overflow Tag Prediction Dataset](https://www.kaggle.com/datasets)
- Includes:  
  - `title` – Short summary of the question  
  - `body` – Full content of the question  
  - `tags` – List of relevant tags (multi-label)

---

## 🎯 Features / Highlights

### • Problem Statement

Manually tagging posts on Stack Overflow is time-consuming and often inconsistent. An automated tool is needed to suggest the most relevant tags based on question content.

### • Solution Overview

- ✅ **TF-IDF Vectorization** to convert textual data into numerical features  
- ✅ **Multi-label classification** using **MLPClassifier** (neural network)  
- ✅ **NLP Preprocessing** including:
  - HTML tag removal  
  - Stopword filtering  
  - Lemmatization for clean, standardized text  
- ✅ **Cross-validation** to validate model performance  
- ✅ Achieved **92% accuracy** on the test set  
- ✅ **Robust error handling** for empty or unclear inputs  
- ✅ **Deployed** via Streamlit on Hugging Face Spaces

---
