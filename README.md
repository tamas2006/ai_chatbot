# BCA Interview Assistant AI

An AI-powered interview preparation assistant built by fine-tuning the TinyLlama language model using Hugging Face Transformers and Google Colab.

This project helps BCA students prepare for technical interviews by answering common computer science and programming questions.

---

# Features

- Fine-tuned TinyLlama model
- BCA interview question answering
- Custom JSON dataset
- Interactive AI chatbot
- Google Colab training workflow
- Gradio-based GUI interface
- Beginner-friendly AI engineering project

---

# Tech Stack

- Python
- Hugging Face Transformers
- TinyLlama
- Google Colab
- PyTorch
- TRL
- Datasets Library
- Gradio

---

# Project Workflow

```text
Dataset Creation
        ↓
Dataset Formatting
        ↓
Tokenization
        ↓
Model Loading
        ↓
Fine-Tuning
        ↓
Loss Optimization
        ↓
Model Saving
        ↓
Chatbot GUI
```

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

# Dataset Example

```json
{
  "instruction": "What is Python?",
  "response": "Python is a high-level programming language used for software development, AI, and web development."
}
```

---

# Installation

Clone the repository:

```bash
git clone https://github.com/your-username/ai_chatbot.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

# Run The Project

Open the notebook in:

- Google Colab
- Jupyter Notebook
- VS Code

Run all cells step-by-step.

---

# Example Usage

```python
ask_ai("What is DBMS?")
```

Example Output:

```text
DBMS stands for Database Management System. It is software used to manage and organize databases.
```

---

# Gradio Chatbot GUI

This project also includes a Gemini/ChatGPT-style chatbot interface using Gradio.

Example:

```python
import gradio as gr

demo = gr.ChatInterface(
    fn=chat,
    title="BCA Interview Assistant AI"
)

demo.launch()
```

---

# Screenshots

## Training Output

Add screenshots here:

```markdown
![Training](screenshots/training_output.png)
```

## Chatbot Demo

```markdown
![Chatbot](screenshots/chatbot_demo.png)
```

---

# Requirements

```text
transformers
datasets
torch
trl
accelerate
bitsandbytes
gradio
```

---

# Future Improvements

- Larger training dataset
- Better conversational abilities
- Voice assistant support
- Resume analysis integration
- RAG-based retrieval system
- Online deployment
- Advanced UI improvements

---

# Learning Outcomes

This project helped in understanding:

- LLM fine-tuning
- tokenization
- transformers
- GPU training
- inference pipelines
- debugging AI workflows
- chatbot development
- model deployment basics

---

# Author

Created as a beginner AI engineering project for learning Small Language Model fine-tuning and deployment workflows.
