# Chat with PDF using Google Gemini Pro

This project allows users to interact with PDF documents by asking questions using **Google Gemini Pro** and **LangChain**. The app processes uploaded PDF files, extracts their content, and lets users ask questions. It uses **FAISS** to create a vector index for efficient similarity search and **Google Generative AI** for conversational abilities.

## Features

- Upload multiple PDF files and process them for question-answering.
- Split text into chunks and generate embeddings using Google Generative AI.
- Efficient similarity search using FAISS for document indexing.
- Answer questions based on the contents of the uploaded PDFs.

## Setup Instructions

### 1. Clone the repository:

```bash
git https://github.com/Shreyas250503/PDF-GPT-Document-Interaction-System.git
cd GEMINI_APP
```
### 2. Install the required dependencies:
```bash
pip install -r requirements.txt
```

### 3. Set up environment variables:
Create a .env file in the root directory.
Add your Google API key to the .env file:

```bash
GOOGLE_API_KEY=your_google_api_key_here
```

### 4. Run the Streamlit application:

```bash
streamlit run app.py
```
