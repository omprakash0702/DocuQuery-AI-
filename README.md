📄 DocuQuery AI
An intelligent PDF document assistant that lets you upload PDFs and query them in natural language.
Powered by LangChain, Hugging Face Transformers, FAISS vector store, and a Gradio interface, this project uses Retrieval-Augmented Generation (RAG) to deliver accurate, context-aware answers.

🚀 Features
PDF Upload – Supports single or multiple PDF uploads.

Natural Language Query – Ask questions as if talking to a person.

Retrieval-Augmented Generation (RAG) – Fetches only the most relevant chunks for precise answers.

Gradio Interface – Clean, interactive UI for seamless use.

Local or Cloud Models – Works with Hugging Face or OpenAI LLMs.

🛠 Tech Stack
LangChain – For chaining LLM calls and retrieval pipelines.

Hugging Face Transformers – For running language models.

FAISS – For fast and efficient vector similarity search.

PyPDF2 / pdfplumber – For PDF text extraction.

Gradio – For building the web interface.

⚙️ How It Works
Upload PDFs → The system extracts text and splits it into manageable chunks.

Vectorization → Chunks are converted into embeddings using a Hugging Face embedding model.

Indexing → FAISS stores these embeddings for quick retrieval.

Querying → When a user asks a question, FAISS finds the most relevant chunks.

Generation → The selected chunks are passed to the LLM to generate an accurate answer.

Response → Gradio displays the result in the web interface.

Sample output->
<img width="732" height="408" alt="image" src="https://github.com/user-attachments/assets/b98c54a4-605c-46a6-9835-ffaea14bd5b0" />
