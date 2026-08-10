# Self-RAG: Self-Reflective Retrieval-Augmented Generation

A practical implementation of a **Self-RAG (Self-Reflective Retrieval-Augmented Generation)** system using a **Hugging Face Chat Model**.

Unlike a traditional RAG pipeline that simply retrieves documents and generates an answer, this project adds multiple evaluation and feedback steps to improve the quality and reliability of the final response.

---

## 🚀 Project Overview

Traditional RAG generally follows:

```text
Question
   ↓
Retrieve Documents
   ↓
Generate Answer
