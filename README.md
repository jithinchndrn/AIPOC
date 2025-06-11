# 📄 Document Search Bot

A Streamlit-based web application that allows authenticated users to upload, process, and query documents using a powerful large language model (LLM) — [Mixtral-8x7B-Instruct](https://huggingface.co/mistralai/Mixtral-8x7B-Instruct-v0.1) hosted on Hugging Face.

Features

- 🔐 User authentication with role-based access (admin/user)
- 📤 Admin-only document upload and processing
- 📄 Support for PDF, DOCX, TXT, XLSX, and PPTX formats
- 🧠 Text extraction from documents and searchable knowledge base
- 🤖 Natural language question answering using Mistral LLM (via Hugging Face)
- 🗂️ Manage and delete processed documents (admin only)

---

# LLM

- **[Mixtral-8x7B-Instruct](https://huggingface.co/mistralai/Mixtral-8x7B-Instruct-v0.1)** – An efficient, high-performing open-weight LLM from Mistral AI
- **Hugging Face Hub** – API hosting for LLMs
- **LangChain** – LLM integration via `langchain_huggingface`
- **Streamlit** – Easy-to-use Python web framework

---

## 📁 Folder Structure

```text
.
├── uploaded_docs/         # Stores original uploaded files
├── processed_docs/        # Stores extracted plain-text files
├── app.py                 # Main Streamlit application
├── .env                   # Contains Hugging Face API token
├── requirements.txt       # Python dependencies
└── README.md              # This file
