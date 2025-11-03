# YouTube_RAG  
**YouTube Video Summarization with Real-Time Chat Capability**

[![GitHub stars](https://img.shields.io/github/stars/Valolaga/YouTube_RAG?style=social)](https://github.com/Valolaga/YouTube_RAG/stargazers)
[![GitHub license](https://img.shields.io/github/license/Valolaga/YouTube_RAG)](https://github.com/Valolaga/YouTube_RAG/blob/main/LICENSE)
[![Python](https://img.shields.io/badge/Python-3.9%2B-blue)](https://www.python.org/)
[![Streamlit](https://img.shields.io/badge/Interface-Streamlit-red)](https://streamlit.io)

> **Summarize any YouTube video in seconds. Then chat with it — in real time.**  
> Powered by **Retrieval-Augmented Generation (RAG)**, this tool extracts video transcripts, generates intelligent summaries, and lets you ask questions interactively — like talking to the video itself.

![Demo GIF](assets/demo.gif)  
*(Replace with your actual demo GIF or screenshot)*

---

## 🚀 Key Features

- **Instant Video Summarization**  
  Paste a YouTube URL → get a concise, structured summary in seconds.
- **Real-Time Interactive Chat**  
  Ask follow-up questions: *"What was the main argument at 5:30?"* or *"Explain the conclusion in simple terms."*
- **RAG-Powered Accuracy**  
  Retrieves exact transcript segments to ground answers in real content.
- **User-Friendly Web Interface**  
  Built with **Streamlit** — no coding needed to use.
- **Supports Long Videos**  
  Efficient chunking and vector search for hour-long content.

---

## 🛠 Tech Stack

| Component           | Technology Used                          |
|---------------------|------------------------------------------|
| **Core Framework**  | LangChain                                |
| **LLM**             | OpenAI (GPT-3.5/4), or local via Hugging Face |
| **Embeddings**      | `text-embedding-ada-002` or `sentence-transformers` |
| **Vector Store**    | FAISS (local) or Pinecone (cloud)        |
| **Transcript Fetch**| `yt-dlp` + YouTube Transcript API        |
| **Frontend**        | Streamlit (real-time chat UI)            |
| **Deployment**      | Local, Streamlit Sharing, or Docker      |

---

## ▶️ Quick Start

### 1. Clone the Repository
```bash
git clone https://github.com/Valolaga/YouTube_RAG.git
cd YouTube_RAG

