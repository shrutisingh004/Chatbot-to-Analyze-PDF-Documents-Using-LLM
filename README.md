# 📄 Chatbot to Analyze PDF Documents Using LLM

An **AI-powered chatbot** that allows users to upload PDF documents and interact with them using natural language.  
The system extracts text from PDFs and uses a **Large Language Model (LLM)** to generate accurate, context-aware responses based on the document content.

---

## Features

- Upload and analyze PDF documents  
- Natural language question-answering  
- Context-aware responses grounded in document content  
- Semantic retrieval using embeddings  
- Simple and intuitive user interface  

---

## Project Overview

Reading and extracting insights from long PDF documents can be time-consuming. This project solves that problem by enabling users to **ask questions directly to a PDF** and receive meaningful answers in real time using LLMs.

---

## How It Works

1. **PDF Upload & Text Extraction**  
   The uploaded PDF is parsed and converted into raw text.

2. **Text Chunking & Embedding**  
   The extracted text is split into smaller chunks and converted into vector embeddings.

3. **Query Processing**  
   User queries are embedded and matched with the most relevant document chunks.

4. **LLM Response Generation**  
   The LLM generates responses using the retrieved context to ensure answers remain grounded in the document.

This follows the **Retrieval-Augmented Generation (RAG)** approach commonly used in modern document-based AI systems.

---

## Tech Stack

- **Programming Language:** Python  
- **LLM & NLP:** OpenAI API, LangChain  
- **PDF Processing:** PyPDF / PDF text extraction libraries  
- **Vector Search:** Embedding-based similarity matching  
- **Frontend:** HTML, CSS, JavaScript  

---

## Example Use Cases

- “Summarize this PDF document.”  
- “What are the key points mentioned in chapter 2?”  
- “Explain the methodology used in this paper.”  

---

## Installation & Setup

### Prerequisites
- Python 3.8+
- OpenAI API key

### Steps

1. Clone the repository:
```bash
git clone https://github.com/shrutisingh004/Chatbot-to-Analyze-PDF-Documents-Using-LLM.git
cd Chatbot-to-Analyze-PDF-Documents-Using-LLM
```
   
2. Create and activate a virtual environment:
```bash
python -m venv venv
source venv/binactivate   # Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Set the API key:
```bash
export OPENAI_API_KEY = "your_api_key_here"
```

5. Run the application:
```bash
python app.py
```
