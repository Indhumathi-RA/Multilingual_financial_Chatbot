

# 💬 Multilingual Financial Literacy Chatbot (Hong Kong)

This project demonstrates a **Retrieval-Augmented Generation (RAG) chatbot** for financial literacy, designed to answer questions in **English, Mandarin, and Cantonese**. It uses **HuggingFace Transformers**, **SentenceTransformers**, **FAISS**, and **Gradio** to provide recruiter‑friendly, interactive demos.

---

## ✨ Features
- **Multilingual Support**: Input in English, Mandarin, or Cantonese → output in the same language.
- **RAG Pipeline**: Combines FAISS retrieval with HuggingFace LLMs for grounded answers.
- **Transparency**: Shows both the generated answer and the source documents retrieved.
- **Interactive UI**: Gradio interface for easy testing and recruiter demos.

---

## 🛠️ Tech Stack
- [SentenceTransformers](ca://s?q=SentenceTransformers_for_embeddings) → multilingual embeddings
- [FAISS](ca://s?q=FAISS_vector_search) → vector search for document retrieval
- [HuggingFace Transformers](ca://s?q=Transformers_pipeline_for_QA) → LLMs (mT5 / mBART‑50)
- [Gradio](ca://s?q=Gradio_UI_for_chatbots) → web interface

---

## 📂 Project Structure
