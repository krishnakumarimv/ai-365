# AI 365 — Day 1 Exercise

## 🧩 Task

Write a simple **Python rule-based program** that identifies whether a message contains an AI-related keyword.

## 📊 Dataset

**Python Basics / Synthetic Messages**
A small hand-crafted set of 15 everyday text messages — some AI-related ("This chatbot answered my query instantly"), some not ("Please pick up milk on your way home") — used to practice basic string matching and `pandas` operations.

## ✅ Expected Output

- Runnable notebook cell(s)
- Result (a table showing each message flagged `True`/`False`)
- 2–3 sentence interpretation of the findings

## 🚀 How to Run

1. Clone this repo / download `AI_Day1_Exercise.ipynb`
2. Open it in Jupyter Notebook, JupyterLab, VS Code, or Google Colab
3. Run all cells top to bottom (`Cell → Run All`)
4. No external dataset download needed — the messages are defined directly in the notebook

## 📁 Files

| File | Description |
|---|---|
| `AI_Day1_Exercise.ipynb` | Full solution notebook: dataset, rule-based keyword detector, results, and interpretation |

## 🔑 Approach

A fixed list of AI-related keywords (`ai`, `chatbot`, `machine learning`, `neural network`, `algorithm`, `robot`, `automat`, etc.) is checked against each message using simple substring matching — no machine learning involved. This is the simplest possible way to build a keyword classifier, and it's a useful baseline before reaching for anything more sophisticated.

## 📈 Result Summary

- **8 of 15** messages flagged as AI-related
- Rule-based matching is fast and fully explainable
- It's also brittle — it misses AI-related messages that don't use an exact keyword (e.g. *"the system learned from our data on its own"*), and can misfire on keywords used out of context

## 💡 Key Takeaway

Rule-based systems are a great starting point for text classification, but their reliance on exact keyword matches is exactly the limitation that real machine learning models are designed to overcome — by learning patterns in language instead of matching fixed words.

---

*Part of the [AI 365](https://whatsapp.com/channel/0029VbCHNrh59PwTRYmQsQ0i) daily learning series on WhatsApp.*
