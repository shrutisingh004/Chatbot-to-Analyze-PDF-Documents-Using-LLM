# 📄 Chatbot to Analyze PDF Documents Using LLM

An **AI-powered chatbot** that lets users upload PDF files and interact with them using natural language.  
The system **extracts content from PDFs, embeds the text, and uses a large language model (LLM)** to generate context-aware answers based on the document content.

---

## 🚀 Features

✔ Upload and parse PDF documents  
✔ Semantic retrieval using embeddings  
✔ Natural language question-answer interface  
✔ Context-aware responses powered by an LLM  
✔ Lightweight web UI (HTML/CSS/JS backend)  

(Source inspiration: RAG-based chatbots that enable interactive querying of documents using LLMs and vector search) :contentReference[oaicite:1]{index=1}

---

## 📌 How It Works

1. **PDF Upload & Text Extraction**
   - User uploads a PDF file.
   - All text is extracted and pre-processed into manageable chunks.

2. **Embedding & Storage**
   - Each chunk is converted into vector embeddings.
   - A vector store/index is created for efficient similarity retrieval.

3. **User Query Handling**
   - Queries are converted to embeddings.
   - Relevant chunks are retrieved based on similarity.
   - The language model uses the most relevant contexts to craft answers.

4. **LLM + Retrieval Fusion**
   - The system stitches relevant context together with the user query.
   - The LLM (e.g., OpenAI GPT) responds with content derived from the PDF.

This architecture follows the common **Retrieval-Augmented Generation (RAG) pattern** used in modern AI document chatbots. :contentReference[oaicite:2]{index=2}

---

## 🛠️ Tech Stack

| Component | Technology |
|-----------|------------|
| Backend | Python |
| Frontend UI | HTML / CSS / JavaScript |
| LLM Integration | OpenAI API (or other LLM provider) |
| Text / PDF Handling | PDF parsing libraries |
| Retrieval | Embeddings + vector similarity |  

*(Adjust this table based on your actual implementation details)*

---

## 📝 Usage

### Prerequisites
- Python 3.x
- API Key (e.g., OpenAI) stored securely

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/shrutisingh004/Chatbot-to-Analyze-PDF-Documents-Using-LLM.git
   cd Chatbot-to-Analyze-PDF-Documents-Using-LLM

