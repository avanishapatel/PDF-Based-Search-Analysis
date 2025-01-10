# PDF-Based Search And Analysis

## Overview

PDF-Based Search Analysis is a tool designed to extract and analyze text from PDF documents, enabling efficient search and data analysis within PDF files.

## Features

- Extract text from PDF documents.
- Perform search operations within extracted text.
- Analyze and visualize search results.

## Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/avanishapatel/PDF-Based-Search-Analysis.git
   cd PDF-based-search-and-QA-system
2. **Set Up a Virtual Environment**
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   pip install -r requirements.txt
3. **Configure Environment Variables**
   ```bash
   PINECONE_API_KEY="your_pinecone_api_key"
   GROQ_API_KEY="your_groq_api_key"
4. **Run the Application**
   ```bash
   streamlit run app.py

## Project Structure
```bash
PDF-Based-Search-And-Analysis/
├── data/                       # Directory for storing PDF files
├── venv/                       # Virtual environment folder
├── src/                        # Source code
│   ├── pre_processing.py  # Module for parsing and processing PDFs
├── app.py                      # Main application logic
├── requirements.txt            # Python dependencies
├── .env                        # Environment variables
└── README.md                   # Project documentation
