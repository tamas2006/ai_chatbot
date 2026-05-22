# BCA Interview Assistant AI

An AI-powered interview preparation assistant built by fine-tuning the TinyLlama language model using Hugging Face Transformers and Google Colab.

This project helps BCA students prepare for technical interviews by answering common computer science and programming questions.

---

# Project Overview

This project demonstrates the complete workflow of training and fine-tuning a Small Language Model (SLM):

- Creating a custom dataset
- Formatting conversational training data
- Tokenizing text
- Fine-tuning TinyLlama
- Testing model responses
- Building a beginner AI chatbot system

The project was trained on a custom BCA interview question-answer dataset.

---

# Features

- AI-powered technical interview assistance
- Fine-tuned TinyLlama model
- Custom JSON dataset
- Google Colab GPU training
- Interactive chatbot inference
- Beginner-friendly LLM pipeline

---

# Tech Stack

- Python
- Google Colab
- Hugging Face Transformers
- TinyLlama
- PyTorch
- TRL
- Datasets Library
- JSON

---

# Model Information

| Parameter | Value |
|---|---|
| Base Model | TinyLlama-1.1B-Chat-v1.0 |
| Training Type | Fine-Tuning |
| GPU Used | Tesla T4 |
| Epochs | 3 |
| Dataset Size | 30 Examples |
| Final Training Loss | 0.39 |

---

# Dataset Format

Example dataset entry:

```json
{
  "instruction": "What is Python?",
  "response": "Python is a high-level programming language used for software development, AI, and web development."
}
