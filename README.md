# DocuQuery_AI

**DocuQuery_AI** is an intelligent document assistant that allows users to upload PDFs and query them using natural language.  
Built using **LangChain**, **Hugging Face Transformers**, **FAISS** vector store, and **Gradio**, this project implements **Retrieval-Augmented Generation (RAG)** to extract relevant information from PDFs and deliver precise, context-aware answers.

---

## 🚀 Features
- 📄 **Upload PDFs** — Easily add your own documents.
- 💬 **Ask in Natural Language** — Query without worrying about keywords.
- 🎯 **Accurate Retrieval** — Uses FAISS for efficient similarity search.
- 🤖 **AI-Powered Answers** — Large Language Models provide context-aware responses.
- 🌐 **Interactive Web UI** — Powered by Gradio for ease of use.

---

## 🛠️ Tech Stack
- **LangChain** — Orchestrates document loading, text splitting, embeddings, and retrieval.
- **Hugging Face Transformers** — LLMs for generating answers.
- **FAISS** — Vector database for efficient similarity search.
- **Gradio** — Simple, interactive web-based UI.
- **PyMuPDF / pdfplumber** — For extracting text from PDFs.

---

## ⚙️ How It Works
1. **Upload PDF** — The system reads and processes your file.
2. **Chunk & Embed** — Text is split into small chunks and converted into embeddings using a Hugging Face model.
3. **Store in FAISS** — Embeddings are stored in a FAISS vector store for fast retrieval.
4. **Query** — User’s question is embedded and compared with stored chunks to find relevant ones.
5. **Generate Answer** — Relevant chunks are passed to the LLM to produce a precise, context-aware answer.
6. **Display in Gradio** — The answer is shown on the web interface.

---

## Sample output->
<img width="732" height="408" alt="image" src="https://github.com/user-attachments/assets/b98c54a4-605c-46a6-9835-ffaea14bd5b0" />
