# University Admission Assistant Using RAG

An AI-powered assistant that answers university admission-related questions using information retrieved from university documents.

## Overview

The University Admission Assistant uses Retrieval-Augmented Generation (RAG) to retrieve relevant information from university documents and generate context-aware answers. It helps users find admission information without manually searching through multiple documents.

## Features

- Document processing and text extraction
- Text chunking and vector embeddings
- FAISS-based similarity search
- Context-aware question answering
- Large Language Model (LLM) integration
- Prompt engineering for relevant responses

## Technologies Used

- Python
- Retrieval-Augmented Generation (RAG)
- Large Language Models (LLMs)
- FAISS
- Vector Embeddings
- Semantic Search
- Prompt Engineering

## Project Structure

```text
University-Admission-Assistant/
├── app.py
├── ingest.py
├── rag.py
├── utils.py
├── requirements.txt
├── data/
│   ├── Admission_Brochure 1.pdf
│   ├── Fee_Structure.pdf
│   ├── Hostel_Policy.pdf
│   ├── Placement_Report.pdf
│   └── Scholarship_Policy.pdf
└── README.md
```

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/CharishamaVarma/University-Admission-Assistant.git
cd University-Admission-Assistant
```

### 2. Create a virtual environment

```bash
python -m venv .venv
```

Activate it on Windows:

```powershell
.venv\Scripts\Activate.ps1
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the application

Check the instructions in `app.py` and the project's configuration to determine the required startup command.

## Use Cases

- Finding admission-related information
- Checking fee structures and hostel policies
- Exploring scholarship information
- Accessing placement-related details from available documents

## Future Improvements

- Improve document retrieval accuracy
- Add a user-friendly web interface
- Support additional university documents
- Enhance answer generation and source references

## Author

**Charishma Varma Vegesana**

GitHub: [CharishamaVarma](https://github.com/CharishamaVarma)
