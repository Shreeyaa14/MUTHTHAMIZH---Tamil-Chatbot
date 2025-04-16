# முத்தமிழ் (Muththamizh) Chatbot

A comprehensive Tamil language chatbot that provides translation, literature queries, text summarization, and document search capabilities.

## Features

- English-Tamil and Tamil-English translation
- Tamil literature information and queries
- Tamil text summarization
- Word search in Tamil documents
- Voice output support
- Document upload and processing (PDF/DOCX)
- Tamil-themed user interface

## Installation

1. Create a virtual environment (recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

## Usage

Run the Streamlit application:
```bash
streamlit run thamizhi.py
```

The application will open in your default web browser with the following features:

1. **Translation**
   - Switch between English-Tamil and Tamil-English
   - Text-to-speech support for translations

2. **Literature Query**
   - Information about Tamil literature, epics, and Thirukkural
   - Explanations of Tamil terms and concepts

3. **Text Summarization**
   - Summarize Tamil text with adjustable summary length
   - Preserves key information while reducing content

4. **Word Search**
   - Upload PDF or DOCX documents
   - Search for specific Tamil words
   - View results in context

## Requirements

- Python 3.7+
- See requirements.txt for complete list of dependencies

## Note

The literature database included is a sample. For a production environment, you should expand the database with more comprehensive content from Tamil literature sources.
