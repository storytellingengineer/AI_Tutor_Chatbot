# AI Tutor Chatbot 🤖 (Work in Progress)

**Day 19 / #90DaysOfAI** — An Interactive AI Tutor Chatbot using RAG (Retrieval-Augmented Generation) built with **LangChain + Streamlit + OpenAI**.

## 🎓 What It Does

- Answers AI/ML/LLM-related questions in a student-friendly way.
- Retrieves relevant knowledge chunks from a curated `ai_knowledge.txt` file.
- Uses LangChain's RetrievalQA chain with FAISS vector store and OpenAI embeddings.

## 🗂 How It Works

- You provide a question → "What is a Transformer?"
- The app retrieves relevant notes from your knowledge base.
- It generates a detailed, easy-to-understand answer.
- You can also see the source chunks used to build the answer.

## 🧠 Applications

- AI tutors / study bots
- Knowledge retrieval for custom domains (LLMs, healthcare, law, etc.)
- Personal learning assistant
- Interview preparation companion

## 🚀 Getting Started

```bash
pip install -r requirements.txt
streamlit run app.py
```

Note: Add your OPENAI_API_KEY in .streamlit/secrets.toml

---

Built as part of my #90DaysOfAI series.

Follow my journey on [LinkedIn](https://www.linkedin.com/in/storytellingengineer/) 🚀
