# 📄 RAG_Based-PDF-Assistant

A simple Retrieval-Augmented Generation (RAG) based PDF Assistant built with **Streamlit**, **LangChain**, **FAISS**, and **Groq LLM**. Upload one or more PDF files and ask questions to get context-based answers from the uploaded documents.

---

## 🚀 Features

- Upload multiple PDF files
- Extract text from PDFs
- Split text into chunks for better retrieval
- Store embeddings using FAISS
- Retrieve the most relevant document sections
- Generate answers using Groq LLM
- Simple and interactive Streamlit interface

---

## 🛠️ Tech Stack

- Python
- Streamlit
- LangChain
- FAISS
- FastEmbed Embeddings
- Groq API
- PyPDF2

---

## 📂 Project Structure

```
RAG_Based-PDF-Assistant/
│
├── app.py
├── requirements.txt
├── .env
├── README.md
└── assets/ (optional)
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/RAG_Based-PDF-Assistant.git
cd RAG_Based-PDF-Assistant
```

### 2. Create a virtual environment (Optional)

```bash
python -m venv venv
```

Activate the environment:

**Windows**

```bash
venv\Scripts\activate
```

**Mac/Linux**

```bash
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 Environment Variables

Create a `.env` file in the project folder.

```env
GROQ_API_KEY=your_groq_api_key
```

Get your API key from **Groq Console**.

---

## ▶️ Run the Application

```bash
streamlit run app.py
```

---

## 📖 How to Use

1. Launch the application.
2. Upload one or more PDF files.
3. Click **Submit & Process**.
4. Wait for the PDFs to be processed.
5. Ask questions related to the uploaded documents.
6. The assistant retrieves relevant content and generates a context-based response.

---

## 📦 Dependencies

- streamlit
- python-dotenv
- PyPDF2
- langchain
- langchain-community
- langchain-text-splitters
- langchain-groq
- faiss-cpu
- fastembed

Install all dependencies using:

```bash
pip install -r requirements.txt
```

---

## 📸 Output

- Upload PDF documents
- Process documents into vector embeddings
- Ask questions
- Receive answers based only on the uploaded PDF content

---

## 📌 Future Improvements

- Chat history
- Source citation with page numbers
- PDF preview
- Conversation memory
- Support for DOCX and TXT files

---

## 👩‍💻 Author

**Pratiksha Kamble**

---
