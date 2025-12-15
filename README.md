# AI Document Intelligence Capstone

**Video Demonstration:**  
Watch the full project demo here: https://drive.google.com/file/d/1bo2Kzf5UacB8Ejc1HieSuFJS5hWQolId/view?usp=sharing

Full Capstone: https://colab.research.google.com/drive/18fBzDw5M4JQeYpGJT-tuLSyP86RuyTAM?usp=sharing
---

## Overview
This project is an AI-powered document intelligence system built as the capstone
for the Outmation externship. The system ingests unstructured PDF documents,
extracts text using OCR, and enables natural-language querying through a
retrieval-augmented generation (RAG) pipeline.

The goal was to transform static, hard-to-search documents into an interactive,
queryable knowledge source using modern NLP techniques.

---

## Problem Statement
Organizations frequently store critical information in PDF documents that are:
- Unstructured
- Poorly searchable
- Difficult to analyze at scale

Traditional keyword search fails to capture semantic meaning or context.
This project addresses that gap by combining OCR, vector search, and LLMs.

---

## System Architecture
The system follows a multi-stage pipeline:

1. **Document Ingestion**
   - PDF upload and preprocessing

2. **OCR & Text Extraction**
   - Extracts text from scanned and native PDFs

3. **Chunking & Embedding**
   - Splits text into manageable chunks
   - Converts text into vector embeddings

4. **Vector Search**
   - Retrieves relevant document context based on semantic similarity

5. **LLM-Powered Q&A**
   - Generates context-aware answers using retrieved document chunks

---

## Capabilities Demonstrated
Shown in the video demonstration:
- Uploading and processing PDF documents
- Asking natural-language questions
- Context-aware answers grounded in document content
- Improved accuracy through chunking and retrieval strategies
- Handling noisy or imperfect OCR output

---

## Tools & Technologies
- Python
- OCR (PyMuPDF / Tesseract)
- LlamaIndex
- Retrieval-Augmented Generation (RAG)
- Vector databases
- Prompt engineering
- ChatGPT for evaluation and testing

---

## Key Challenges
- Extracting usable text from messy or scanned PDFs
- Designing effective chunking strategies
- Improving retrieval relevance
- Balancing response quality with performance
- Prompt tuning for accurate, grounded answers

---

## What I Learned
- How to design end-to-end AI systems, not just isolated models
- Practical challenges of OCR and unstructured data
- How retrieval quality directly impacts LLM performance
- The importance of system design and evaluation in applied AI projects

---

## Notes
This project was developed within an externship environment.
This repository focuses on system design, functionality, and demonstrated outcomes.
