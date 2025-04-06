# GPT-Neo Movie Recommendation System 🎬🤖

This application is a simple AI-powered movie recommendation tool built using **EleutherAI's GPT-Neo** language model. It takes user input and a given context (such as a movie catalog) and generates natural language recommendations based on that input. The model is hosted locally using the Hugging Face Transformers library, with GPU acceleration via PyTorch.

---

## 🚀 What This App Does

This app allows users to get intelligent movie recommendations by inputting a query (e.g., *"I want to watch an action-packed movie with a great storyline"*). The model considers this user input and matches it against a provided movie context (e.g., a small movie catalog) to generate personalized recommendations in natural language.

---

## 🧠 Technologies & Libraries Used

| Library        | Purpose                                                                 |
|----------------|-------------------------------------------------------------------------|
| `transformers` | Loads pre-trained GPT-Neo models and tokenizers from Hugging Face Hub. |
| `torch`        | Provides GPU-accelerated model inference using PyTorch.                |
| `datasets`     | (Optional) Used for future data preprocessing or evaluation datasets.  |
| `accelerate`   | Helps with efficient model loading across CPUs/GPUs.                   |

---

## ⚙️ Installation

Install the required dependencies using pip:

``bash
pip install transformers datasets accelerate

##How It Works
The GPT-Neo 1.3B model is loaded from Hugging Face (EleutherAI/gpt-neo-1.3B).

A function generate_recommendations() takes a user query and a context.

GPT-Neo generates textual recommendations based on the input.

The result is displayed in natural language.
