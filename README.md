# AI Resume Analyzer using RAG (Retrieval-Augmented Guidance)

This project implements a lightweight Resume Analysis tool using 
SentenceTransformer embeddings and a custom knowledge base.

The system generates resume improvement suggestions using 
cosine similarity between the user's resume and predefined tips.

---

## 🚀 Features
- Uses `all-MiniLM-L6-v2` SentenceTransformer model.
- Embeds a small curated knowledge base.
- Computes semantic similarity between resume text and tips.
- Returns Top 3 suggestions for resume improvement.
- Fully interactive command-line tool.

---

## 🧠 Technologies Used
- Python
- SentenceTransformer (MiniLM)
- NumPy
- Scikit-Learn (Cosine Similarity)

---

## 📁 File Included
- `ai_resume_analyzer.py` – main script (uploaded by you)

---

## ▶️ How to Run
```bash
pip install sentence-transformers scikit-learn numpy
python ai_resume_analyzer.py
