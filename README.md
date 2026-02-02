# GenAI Document Chatbot (RAG-based)

## 📌 Project Overview
This project is a **Generative AI-powered document chatbot** that allows users to upload PDF documents and ask questions directly from their content.  
The application uses **Retrieval-Augmented Generation (RAG)** to ensure responses are generated **only from the uploaded document**, improving accuracy and reliability.

It is built using **LangChain, OpenAI LLMs, FAISS vector database, and Streamlit**, making it a practical example of real-world GenAI application development.

---

## ❓ Problem Statement
Traditional chatbots:
- Hallucinate answers
- Cannot understand custom documents
- Fail to provide source-specific responses

Manually searching large PDFs is:
- Time-consuming
- Inefficient
- Error-prone

---

## ✅ Solution
This application:
- Converts PDF content into embeddings
- Stores them in a vector database
- Retrieves only relevant document chunks
- Generates accurate answers using an LLM

This ensures:
- Context-aware answers
- Reduced hallucination
- Faster information retrieval

---

## 🧠 How It Works (RAG Flow)
1. User uploads a PDF document  
2. Document is split into chunks  
3. Embeddings are created using OpenAI  
4. FAISS stores embeddings for fast similarity search  
5. Relevant chunks are retrieved based on the query  
6. LLM generates an answer strictly from retrieved context  

---

## 🛠️ Tech Stack
- **Programming Language:** Python  
- **LLM:** OpenAI (GPT-3.5)  
- **Framework:** LangChain  
- **Vector Database:** FAISS  
- **Frontend:** Streamlit  
- **Document Loader:** PyPDF  
- **Environment Management:** python-dotenv  

---

## ▶️ How to Run the Project Locally

### 1. Clone the repository
```bash
git clone https://github.com/HarshOnTheWeb/genai-document-chatbot.git
cd genai-document-chatbot
