AILAS – AI Legal Analyzer & Summarizer:
An intelligent system that analyzes and summarizes legal documents using AI, NLP, and LLMs.

Project Overview:
----------------
AILAS (AI Legal Analyzer & Summarizer) is a smart AI-powered tool designed to extract, analyze, and summarize complex legal documents such as:
- Banking documents
- FIRs
- Property/Registry papers
- Policies
- Builder Property
Legal documents are often long, complicated, and filled with technical terms. This project helps users understand them quickly by generating clear summaries, identifying key clauses, and highlighting risks & obligations.

Features:
---------
1. PDF Text Extraction: Reads and extracts text from legal PDF documents.
2. AI/LLM-Based Summarization: Converts lengthy documents into short, meaningful summaries using BART / LLM models.
3. Clause & Section Identification: Detects important sections such as:
      ~ Terms & Conditions
      ~ Penalties
      ~ Obligations
      ~Legal Points
4. Risk Detection: Highlights unusual or risky clauses.
5. Multi-Document Support: Upload and analyze multiple categories like Banking, FIR, Policy, Property, Law, etc.
6. Fast & Accurate: Reduces manual reading effort and makes legal understanding easier.

Folder Structure:
----------------
AILAS_Project/
│
├── backend/
│   ├── app.py
│   ├── uploads/
│   ├── venv/
│
└── frontend/
    ├── src/
    ├── public/
    ├── package.json

Tech Stack:
----------
Backend:
-------
Python
Flask
Flask-CORS
PyPDF2 / PyMuPDF
Transformers (BART/LLM)
Torch
Regex
SpaCy

Frontend:
--------
React
Axios
Material UI / Tailwind

How It Works:
------------
1. User uploads a legal PDF
2. System extracts text
3. AI model summarizes the document
4. NLP identifies clauses and key sections
5. Output displayed with:
      ~ Summary
      ~ Clauses
      ~ Risks
      ~ Section-wise analysis
