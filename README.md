# AI-ML-Internship-Tasks-Phase-2
Advanced AI/ML projects showcasing transformer models, end-to-end ML pipelines, and LLM-based applications built during an AI/ML Engineering Internship.
# 🤖 AI/ML Internship Tasks – DevelopersHub Corporation

## 📌 Overview
This repository contains my work for the AI/ML Engineering Internship at DevelopersHub Corporation.  
It includes multiple real-world machine learning and AI projects covering NLP, ML pipelines, and LLM-based applications.

---

## ✅ Completed Tasks

### 📰 Task 1: News Topic Classifier (BERT)
- Built a transformer-based NLP model using BERT
- Classified news headlines into categories (World, Sports, Business, Sci/Tech)
- Used Hugging Face Transformers for fine-tuning
- Evaluated using Accuracy and F1-score
- Deployed using Gradio for live interaction

---

### 📊 Task 2: Customer Churn Prediction Pipeline
- Developed an end-to-end ML pipeline using Scikit-learn
- Applied preprocessing (encoding + scaling)
- Trained models: Logistic Regression & Random Forest
- Performed hyperparameter tuning using GridSearchCV
- Exported model using joblib

---

### 🎫 Task 5: Support Ticket Auto Tagging (LLM)
- Built an AI system to classify support tickets into categories
- Used LLM-based zero-shot and few-shot learning
- Applied prompt engineering techniques
- Generated top 3 predicted tags for each ticket

---

## 🛠️ Technologies Used
- Python
- Hugging Face Transformers
- Scikit-learn
- Pandas & NumPy
- Gradio / Streamlit
- Joblib
- Large Language Models (LLMs)

---
# 📰 Task 1: News Topic Classifier using BERT

## 📌 Objective
The objective of this task is to build a Natural Language Processing (NLP) model using a transformer-based architecture (BERT) to classify news headlines into predefined categories.

## 📊 Dataset
- AG News Dataset (Hugging Face)
- Categories:
  - World
  - Sports
  - Business
  - Sci/Tech

## ⚙️ Methodology / Approach
1. Loaded dataset using Hugging Face Datasets
2. Preprocessed text using BERT tokenizer
3. Fine-tuned `bert-base-uncased` model
4. Used Trainer API for training
5. Evaluated model using:
   - Accuracy
   - F1-score
6. Deployed using Gradio interface

## 🤖 Model Used
- BERT (bert-base-uncased)

## 📈 Results
- Accuracy: ~85% (depends on training size)
- F1 Score: ~85%

## 💡 Key Insights
- Transformer models perform very well on text classification tasks
- Fine-tuning significantly improves performance
- Pretrained embeddings reduce training time

# 📊 Task 2: Customer Churn Prediction using ML Pipeline

## 📌 Objective
The objective of this task is to build a complete machine learning pipeline to predict whether a customer will churn (leave the service) or not using structured data.

## 📊 Dataset
- Telco Customer Churn Dataset
- Features include:
  - Customer demographics
  - Account details
  - Services subscribed

## ⚙️ Methodology / Approach
1. Loaded dataset using pandas
2. Cleaned data (handled missing values and data types)
3. Performed preprocessing:
   - Scaled numerical features using StandardScaler
   - Encoded categorical features using OneHotEncoder
4. Built pipeline using Scikit-learn Pipeline API
5. Trained models:
   - Logistic Regression
   - Random Forest
6. Applied GridSearchCV for hyperparameter tuning
7. Evaluated model using accuracy
8. Saved final model using joblib

## 🤖 Models Used
- Logistic Regression
- Random Forest Classifier

## 📈 Results
- Accuracy: ~78–85% (depending on model and tuning)
- Best performance achieved with Random Forest

## 💡 Key Insights
- Data preprocessing plays a critical role in model performance
- Pipeline helps automate and organize ML workflow
- Hyperparameter tuning significantly improves results


---
# 🎫 Task 5: Auto Tagging Support Tickets using LLM

## 📌 Objective
The objective of this task is to automatically classify support tickets into relevant categories using a Large Language Model (LLM).

## 📊 Dataset
- Free-text support ticket dataset
- Example tickets:
  - "App crashes on login"
  - "Unable to reset password"

## ⚙️ Methodology / Approach
1. Loaded and explored support ticket data
2. Applied LLM for text classification
3. Used:
   - Zero-shot learning (no training)
   - Few-shot learning (with examples)
4. Designed effective prompts for better predictions
5. Generated top 3 most relevant tags for each ticket
6. Compared performance between zero-shot and few-shot approaches

## 🤖 Model Used
- Hugging Face LLM / OpenAI model (for text generation and classification)

## 📈 Results
- Zero-shot: Moderate accuracy
- Few-shot: Improved classification performance
- LLM successfully generated multiple relevant tags

## 💡 Key Insights
- Prompt engineering plays a key role in LLM performance
- Few-shot learning improves prediction quality
- LLMs can perform classification without explicit training



