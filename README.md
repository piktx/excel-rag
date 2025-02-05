# 📊 Excel RAG Chatbot with Llama-3.2 & IBM Dockling

[![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=Streamlit&logoColor=white)](https://streamlit.io/)
[![LlamaIndex](https://img.shields.io/badge/LlamaIndex-0F9D58?style=for-the-badge&logo=llama&logoColor=white)](https://www.llamaindex.ai/)
[![Ollama](https://img.shields.io/badge/Ollama-01A3A8?style=for-the-badge&logo=ollama&logoColor=white)](https://ollama.ai/)
[![LocalAI](https://img.shields.io/badge/100%25-LocalAI-01C4C8?style=for-the-badge)](https://localai.io/)

An intelligent chatbot that performs **RAG (Retrieval Augmented Generation)** on Excel files using cutting-edge local AI models.

## 🚀 Features
- 🔍 **Excel File Analysis**: Upload and chat with XLSX/XLS/CSV files
- 🧠 **Local AI Processing**: 100% local execution with Llama-3.2 model
- 📈 **Data Visualization**: Built-in Excel preview and data exploration
- ⚡ **Streaming Responses**: Real-time answer generation with typing effect
- 🛡️ **Secure**: No data leaves your local machine
- 🔄 **Session Management**: Intelligent caching and memory management

## 🛠️ Tech Stack
- **Framework**: `Streamlit`
- **LLM**: `Llama-3.2-vision` via Ollama
- **Embeddings**: `BAAI/bge-large-en-v1.5`
- **Data Processing**: `Pandas`, `LlamaIndex`
- **Document Parsing**: `DoclingReader`
- **Caching**: Native Streamlit caching

## 📦 Installation

```bash
# Clone repository
git clone https://github.com/yourusername/excel-rag.git
cd excel-rag

# Install dependencies
pip install -r requirements.txt

# Start Ollama service (required)
ollama serve
