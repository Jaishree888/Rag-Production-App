# 🚀 Production-Ready RAG AI System

An end-to-end **Retrieval-Augmented Generation (RAG)** pipeline built using **FastAPI**, **Inngest**, **Qdrant**, and **Sentence Transformers** for intelligent semantic document retrieval.

> 📚 Upload PDFs → Generate Embeddings → Store in Vector DB → Retrieve Relevant Context:

![Python](https://img.shields.io/badge/Python-3.11-blue)
![FastAPI](https://img.shields.io/badge/FastAPI-Backend-green)
![Qdrant](https://img.shields.io/badge/Qdrant-VectorDB-red)
![Status](https://img.shields.io/badge/Status-Work%20In%20Progress-orange)

---

# ✨ Features

✅ PDF ingestion pipeline  
✅ Intelligent text chunking  
✅ Semantic embeddings generation  
✅ Vector similarity search using Qdrant  
✅ Event-driven workflow orchestration using Inngest  
✅ FastAPI backend integration  
✅ Local embedding support using SentenceTransformers  
✅ GitHub version control & deployment-ready structure  

---

# 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| 🐍 Python | Core development |
| ⚡ FastAPI | Backend API |
| 🧠 SentenceTransformers | Embedding generation |
| 📦 Qdrant | Vector database |
| 🔄 Inngest | Event-driven workflows |
| 🤗 HuggingFace | Embedding models |
| 🌐 Git & GitHub | Version control |

---

# 📂 Project Structure

```bash
RAGProductionApp/
│
├── main.py
├── data_loader.py
├── vector_db.py
├── custom_types.py
├── pyproject.toml
├── README.md
├── .gitignore
└── qdrant_storage/
```

---

# ⚙️ Workflow

## 📄 Step 1: PDF Ingestion
The system ingests PDF documents and extracts textual data.

## ✂️ Step 2: Chunking
Text is split into meaningful chunks using SentenceSplitter for efficient retrieval.

## 🧠 Step 3: Embedding Generation
Embeddings are generated using transformer-based sentence embedding models.

## 🗄️ Step 4: Vector Storage
Embeddings are stored inside Qdrant vector database.

## 🔍 Step 5: Semantic Retrieval
Relevant chunks are retrieved using vector similarity search.

---

# 🚀 Installation

## 1️⃣ Clone Repository

```bash
git clone https://github.com/Jaishree888/Rag-Production-App.git
cd Rag-Production-App
```

---

## 2️⃣ Create Virtual Environment

### Windows

```bash
python -m venv .venv
.venv\Scripts\activate
```

---

## 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

or

```bash
uv sync
```

---

# ▶️ Running the Project

## Start FastAPI Server

```bash
uv run --active uvicorn main:app --port 8001
```

---

## Start Inngest Dev Server

```bash
npx inngest-cli@latest dev
```

---

# 🌐 Local URLs

### FastAPI Server

```bash
http://127.0.0.1:8001
```

### Inngest Dashboard

```bash
http://localhost:8288
```

---

# 🧠 Embedding Model

Current embedding model:

```python
sentence-transformers/all-MiniLM-L6-v2
```

Embedding dimension:

```python
384
```

---

# 💻 Usage Example

## Run PDF Ingestion Event

```json
{
  "data": {
    "pdf_path": "C:\\Users\\YourName\\Downloads\\sample.pdf"
  }
}
```

---

## Run Query Event

```json
{
  "data": {
    "question": "What is this paper about?"
  }
}
```

---

# 📸 Screenshots

## 🔹 Inngest Workflow Dashboard
_Add screenshot here_

## 🔹 FastAPI Server Running
_Add screenshot here_

---

# 📈 Current Progress

| Status | Feature |
|---|---|
| ✅ | PDF ingestion |
| ✅ | Chunking pipeline |
| ✅ | Embedding generation |
| ✅ | Qdrant vector storage |
| ✅ | GitHub integration |
| 🚧 | Query-answer generation |
| 🚧 | Frontend integration |
| 🚧 | Cloud deployment |

---

# 🔮 Future Improvements

✨ Add LLM-powered response generation  
✨ Build interactive frontend UI  
✨ Deploy using Render/Vercel  
✨ Add authentication system  
✨ Implement streaming responses  
✨ Optimize retrieval ranking  

---

# 🤝 Contributing

Contributions, issues, and feature requests are welcome!

## Steps to Contribute

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Push the branch
5. Open a Pull Request

Please ensure your code follows clean coding practices and proper documentation.

---

# 📬 Contact

👩‍💻 Jaishree Jaiswal  

🔗 GitHub:  
https://github.com/Jaishree888

For collaboration, suggestions, or project discussions, feel free to connect through GitHub.

---

# 📜 License

This project is created for learning, experimentation, and educational purposes.

---

# ⭐ Support

If you found this project interesting, consider giving it a ⭐ on GitHub!
