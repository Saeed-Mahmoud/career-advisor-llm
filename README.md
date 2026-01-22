# Career Advisor LLM (RAG-based)

This project is a bilingual career-advice assistant built using Large Language Models (LLMs) and Retrieval-Augmented Generation (RAG).

It provides grounded career guidance on:
- CVs and resumes
- Cover letters
- Job search and networking
- Interviews
- Upskilling and future careers

The assistant retrieves information from a curated set of PDF documents and uses an LLM to generate accurate, source-based answers.

---

## Technologies Used
- Python
- LangChain
- Chroma (Vector Database)
- Google Gemini API
- Retrieval-Augmented Generation (RAG)

---

## Project Files
- `Final_Project_LLM.ipynb` → Main notebook
- PDF files → Knowledge base for retrieval

---

## How to Run (Google Colab recommended)

1. Open the notebook in Google Colab
2. Install required libraries:
   ```bash
   pip install langchain chromadb
