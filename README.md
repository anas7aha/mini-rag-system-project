# 🧠 Mini Retrieval-Augmented Generation (RAG) System

This project implements a **Mini RAG System** — a combination of **retrieval** and **generation** techniques that allow AI models to answer fact-based questions using a custom knowledge base.

---

## 🚀 Overview

RAG (Retrieval-Augmented Generation) is a powerful architecture that enhances language models by retrieving relevant documents and generating answers grounded in real data — reducing hallucinations and improving factual accuracy.

This project was built as part of a hands-on AI engineering exercise to understand and implement a basic RAG pipeline.

---

## 🧩 Key Components

- **Retriever:** Uses the `sentence-transformers/all-MiniLM-L6-v2` model to encode the knowledge base into embeddings and retrieve the most relevant text chunks for a given query.
- **Generator:** Uses `distilbert-base-cased-distilled-squad` from Hugging Face to extract precise answers from the retrieved text.
- **Knowledge Base Expansion:** Demonstrates how to dynamically extend the system's knowledge and verify its performance.

---

## 🧠 Student Tasks Completed

| Task | Description | Status |
|------|--------------|--------|
| **Task 1** | Built the RAG pipeline and ran a self-assessment | ✅ |
| **Task 2** | Added a new test question and extended evaluation | ✅ |
| **Task 3** | Expanded knowledge with a new fact about *Jupiter* | ✅ |

---

## 🧪 Example Output

