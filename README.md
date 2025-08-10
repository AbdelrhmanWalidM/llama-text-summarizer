# 🦙 LLaMA Text Summarizer

A local **AI-powered text summarizer** built with **Ollama + FastAPI + Streamlit**.

---

## 🚀 Features
- Summarizes long text instantly with **LLaMA 2** (or LLaMA 3).
- Runs fully **offline** via [Ollama](https://ollama.com/).
- Clean UI with **Streamlit**, API with **FastAPI**.

---

## ⚙️ Tech Stack
- Ollama (LLaMA model)
- FastAPI (Backend)
- Streamlit (Frontend)
- Python Requests

---

## 📦 Setup
```bash
git clone https://github.com/AbdelrhmanWalidM/llama-text-summarizer.git
cd llama-text-summarizer
python -m venv venv
venv\Scripts\activate  # or source venv/bin/activate
pip install -r requirements.txt
ollama pull llama2
ollama serve

```
---

## ▶️ Run
**Backend:**
```bash
uvicorn backend.main:app --reload --port 8000
```
**Frontend:**
```bash
streamlit run frontend/app.py
```
