# 🧠 Conversational RAG Chatbot with Web Content & History
A conversational chatbot built using RAG (Retrieval-Augmented Generation) that maintains chat history and answers queries based on the content of any given webpage. This project uses LangChain, webbase loader, and a LLM via Groq to deliver contextual, memory-aware responses from external sources.


## 📁 Project Structure
.
├── .env                # Contains API keys (Groq, HuggingFace)

├── .gitignore          # Specifies files to ignore in Git

├── app.ipynb           # Main notebook for running the chatbot

├── requirements.txt    # List of required Python packages




---

## 🔧 Features

- ✅ RAG-powered Q&A chatbot  
- 🌍 Accepts **any webpage URL** for context  
- 🧠 Maintains **chat history** with memory  
- 📘 Notebook-based interface (`app.ipynb`)  
- 📚 Uses `WebBaseLoader` from LangChain to load webpage content  

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/RITIKA-01A/rag_chat_hist_chatbot.git
cd rag-chatbot
 ```


### 2. Create a virtual environment (optional)
```
conda create -n rag-chatbot python=3.11 -y
conda activate rag-chatbot
```
### 3. Install dependencies
```
pip install -r requirements.txt
```

### 4. Set up environment variables
```
GROQ_API_KEY=your_groq_api_key
```

---
# 📓 How to Use
- Open app.ipynb in Jupyter or VS Code.

- Provide a webpage URL to load content using WebBaseLoader.

- Start chatting and ask questions about the content.

- The chatbot will fetch relevant chunks and respond with context and memory.

---
