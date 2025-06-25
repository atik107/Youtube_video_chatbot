# 🎥 YouTube Video Chatbot

A chatbot application that enables users to ask questions about YouTube videos using natural language. The system fetches video transcripts, indexes them using FAISS vector search, and provides intelligent responses using LLMs (Large Language Models).

---

## 🚀 Features

- 🔍 Automatically fetches YouTube video transcripts
- 🧠 Embeds transcript content using OpenAI embeddings
- 💬 Answers user queries using context-aware LLMs
- 🗃️ FAISS-powered semantic search for fast information retrieval
- ⚙️ LangChain-based processing pipeline

---

## 🧰 Tech Stack

- **Python 3**
- **YouTube Transcript API**
- **LangChain** (`langchain-community`, `langchain-openai`)
- **FAISS** (Facebook AI Similarity Search)
- **OpenAI / Groq API**
- **Tiktoken**, **dotenv**

---

## 📦 Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/youtube-video-chatbot.git
cd youtube-video-chatbot
