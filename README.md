# 📚 Parts of Speech (POS) Tagging Using BERT

This project demonstrates how to fine-tune the BanglaBERT model for Parts of Speech (POS) tagging on a provided dataset using the Hugging Face Transformers library. The goal is to develop an end-to-end machine learning pipeline that includes data preprocessing, model training, and evaluation.

## 🚀 Project Overview

This repository contains:
1. **Data Preprocessing**: Load, clean, and tokenize the raw dataset.
2. **Model Development**: Fine-tuning three pre-trained models for the POS tagging task:
   - **ShahajBERT**  
   - **BanglaBERTT5**  
   - **csebuetnlp BanglaBERT** 
3. **Model Evaluation**: Evaluate the model on various metrics (Accuracy, Precision, Recall, F1 Score).
4. **Classification Report**: Generates a detailed report for model evaluation.

## 🛠️ Requirements

Ensure you have the following installed:
- Python 3.6+
- PyTorch
- Hugging Face Transformers
- Scikit-learn
- Matplotlib
- Pandas
- Numpy

## 🤖 Models Used

1. **ShahajBERT**:
General-purpose Bangla BERT model.
Fine-tuned for POS tagging.
2. **BanglaBERTT5**:
BanglaT5 model optimized for text-to-text tasks.
Adapted for POS tagging with token classification.
3. **csebuetnlp BanglaBERT**:
A Bengali language-specific pre-trained BERT model.
Demonstrates the best performance due to pre-training on a large Bangla corpus.

## 🚀 Results

| Model                 | Accuracy | Precision | Recall | F1 Score |
|-----------------------|----------|-----------|--------|----------|
| **ShahajBERT**        | 0.6465   | 0.6440    | 0.6465 | 0.6333   |
| **BanglaBERTT5**      | 0.6768   | 0.6518    | 0.6768 | 0.6600   |
| **csebuetnlp BanglaBERT** | 0.7623   | 0.7528    | 0.7623 | 0.7528   |

