# 🎥 AI Video Assistant with RAG

An AI-powered application that transforms YouTube videos into an interactive knowledge base. The system downloads videos, extracts audio, generates transcripts, creates vector embeddings, and enables users to ask natural language questions about the video using Retrieval-Augmented Generation (RAG).

Built with **Python**, **LangChain**, **Whisper**, **HuggingFace Embeddings**, **ChromaDB**, and **Streamlit**.

---

## ✨ Features

* 📺 Download YouTube videos
* 🎧 Extract audio using FFmpeg
* ✂️ Split long audio into manageable chunks
* 📝 Convert speech to text using Whisper
* 📚 Generate embeddings with HuggingFace
* 🗂️ Store embeddings in ChromaDB
* 🔎 Retrieve relevant transcript sections with RAG
* 💬 Ask questions about video content
* ⚡ Interactive Streamlit interface
* ❌ Robust error handling

---

## 🛠️ Tech Stack

### Languages

* Python

### Frameworks & Libraries

* LangChain
* Streamlit
* Whisper
* HuggingFace Embeddings
* ChromaDB
* yt-dlp
* FFmpeg
* pydub
* Requests

### Concepts

* Retrieval-Augmented Generation (RAG)
* Large Language Models (LLMs)
* Vector Search
* Semantic Search
* Embeddings
* Speech-to-Text
* Prompt Engineering

---

## 🏗️ Architecture

```text
YouTube URL
      │
      ▼
   yt-dlp
      │
      ▼
Audio Extraction (FFmpeg)
      │
      ▼
 Audio Chunking (pydub)
      │
      ▼
Speech-to-Text (Whisper)
      │
      ▼
Text Chunking
      │
      ▼
HuggingFace Embeddings
      │
      ▼
Chroma Vector Database
      │
      ▼
Retriever (RAG)
      │
      ▼
LLM Response
```

---

## 📁 Project Structure

```text
AI-Video-Assistant-with-RAG/
│
├── app.py
├── rag_pipeline.py
├── vector_db.py
├── requirements.txt
├── .env.example
├── README.md
└── assets/
```

---

## ⚙️ Installation

```bash
git clone https://github.com/yourusername/AI-Video-Assistant-with-RAG.git

cd AI-Video-Assistant-with-RAG

python -m venv .venv

pip install -r requirements.txt
```

Create a `.env` file:

```env
MISTRAL_API_KEY=your_api_key
```

---

## ▶️ Run

```bash
streamlit run app.py
```

---

## 💬 Example Questions

* Summarize this video.
* What are the key points discussed?
* Explain the main concepts.
* What does the speaker say about AI?
* Give me the important takeaways.

---

## 🚀 Future Improvements

* Multi-video support
* PDF report generation
* Conversation memory
* Timestamp-based responses
* Multi-language transcription
* Cloud deployment
* Docker support

---

## 🎯 Skills Demonstrated

* Generative AI
* Retrieval-Augmented Generation (RAG)
* LangChain
* ChromaDB
* Whisper
* HuggingFace Embeddings
* Vector Search
* Semantic Retrieval
* Streamlit
* Speech-to-Text
* Python

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.

## 👨‍💻 Author

**Arjun Verma**
