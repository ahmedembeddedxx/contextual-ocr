# Contextual OCR

Contextual OCR is an API-based tool that leverages PyTesseract and DeepSeek r1 APIs to extract text from PDFs and refine it using a backend LLM (Language Learning Model). This open-source project offers a lightweight version of the GPT-4o-mini Context OCR.

## Features:

- **Text Extraction:** Uses PyTesseract to extract text from scanned PDFs.
- **Text Refinement:** Leverages backend LLMs to correct OCR errors, improve readability, and preserve original meaning.
- **Open-Source:** A simplified version of GPT-4o-mini Context OCR, accessible for modifications and enhancements.

## Usage:

- **Extract Text:** Process PDF files and extract raw text.
- **Refine Text:** Use the model to correct inaccuracies and improve text clarity.

## Files:

- **`notebooks/`**: Code for extracting and refining text.
- **`pdfs/`**: Sample PDFs for testing the tool.

## Installation:

1. Clone the repository:

   ```bash
   git clone https://github.com/ahmedembeddedxx/contextual-ocr.git
   cd contextual-ocr
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the application and start testing with the provided PDFs.

## License:

This project is open-source under the MIT license.
