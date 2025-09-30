# Retrieval-Augmented Generation (RAG) Demo

This repository provides simple Colab notebooks and code examples to help students understand **Retrieval-Augmented Generation (RAG)**.  

We provide two modes:  

---

## 🚀 No-Key Mode (in-class, required)

- **No dependency on OpenAI/Gemini API keys**, so no one gets blocked by account setup or quota limits.  
- Goal: walk through the **three core steps of RAG**:
  1. **Chunking** – split source text into smaller segments  
  2. **Embedding & Indexing** – use an embedding model (e.g., `sentence-transformers`) and store vectors in a vector database (e.g., FAISS / Chroma)  
  3. **Retrieve & Draft an Answer** – take a question → retrieve relevant chunks → stitch together a **draft** answer  

👉 At this stage, we use a **simple placeholder “generator”** (just return retrieved passages + a templated sentence). This ensures everyone understands the pipeline without needing an API key.  

---

## 🔑 With-Key Mode (optional extension)

- Students with API keys (e.g., **Google Gemini, OpenAI, Groq**) can replace the placeholder generator with a **real LLM**.  

**Advantages**:
- Produces more natural answers grounded in the retrieved context  
- Allows exploration of advanced features such as **reranking**, **citations**, and **Corrective RAG**  

**Disadvantages**:
- Requires an account and API key, which may not be convenient for everyone  

---

## 📂 Structure

- `RAG_no_key.ipynb` → Minimal in-class notebook (no API keys required)  
- `RAG_with_key.ipynb` → Extension notebook using Gemini or OpenAI API keys  

---

## ✅ How to Use

1. Open the desired notebook in **Google Colab**.  
2. For **No-Key Mode**, just run all cells.  
3. For **With-Key Mode**, add your API key in the environment setup cell.  

---

## 📚 References & Learning

- [RAG Concept Overview (YouTube)](https://www.youtube.com/watch?v=qN_2fnOPY-M)  
- [Step-by-step RAG Implementation (YouTube)](https://www.youtube.com/watch?v=Fm2ZzS5CTP8)  

---

## 📝 License

MIT License. Free to use for teaching and learning. 


If you use this repository in your teaching, research, or projects, please cite it by linking to this GitHub repo:

[https://github.com/your-username/your-repo-name](https://github.com/your-username/your-repo-name)




