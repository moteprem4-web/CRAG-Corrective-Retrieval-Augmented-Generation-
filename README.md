# 🚀 My Learning Journey: Corrective Retrieval Augmented Generation (CRAG)

This repository documents my structured learning journey into **Corrective Retrieval-Augmented Generation (CRAG)** — an advanced evolution of traditional RAG systems designed to improve retrieval quality and reduce hallucinations in LLM-based applications.

This is not just a project — it is my step-by-step exploration of how to build more reliable, production-grade RAG systems.

---

## 📌 Why I Started Learning CRAG

While studying traditional RAG pipelines, I understood that:

1. Retrieval is often noisy.
2. LLMs blindly trust retrieved documents.
3. Poor retrieval leads to hallucinated responses.

I wanted to go beyond basic RAG and learn how to:

- Validate retrieved documents
- Improve context quality
- Reduce hallucinations
- Build more production-ready AI systems

That’s when I started exploring **Corrective RAG (CRAG).**

---

## 🧠 What I Have Learned So Far

### ✅ 1. Traditional RAG Architecture

- Embedding models
- Vector databases (FAISS / Chroma)
- Retriever logic
- LLM-based generation

Understanding the limitations of single-pass retrieval.

---

### ✅ 2. Problem in Standard RAG

Traditional pipeline:

1. User Query  
2. Retrieve Top-K  
3. Send to LLM  
4. Generate Answer  

⚠️ Issue: No validation of retrieved context.

---

### ✅ 3. CRAG Concept

CRAG adds a correction layer:

1. User Query  
2. Embedding Generation  
3. Vector Retrieval  
4. Retrieval Quality Evaluation  
5. If low confidence → Query Rewriting / Re-Retrieval  
6. Validated Context → LLM  
7. Grounded Response  

This creates a **feedback loop for retrieval improvement.**

---

## 🏗️ Conceptual Architecture I’m Studying

