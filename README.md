# Arabic Invoice OCR & Extraction

This repository contains a complete pipeline for extracting structured data from a scanned **Arabic invoice** using OCR and NLP techniques.

## Overview
The solution processes a scanned invoice image and produces clean, structured tabular data suitable for analytics or system ingestion.

Pipeline:
- Vision-based OCR (LLM)
- Raw text extraction
- Text cleaning & normalization
- Entity extraction (invoice metadata, line items, financial summary)
- Structured CSV output

## Files
- `notebook.ipynb`  
  End-to-end Google Colab notebook containing the full pipeline and explanations.

- `extracted_data.csv`  
  Final structured output combining all extracted tables into a single CSV file, with a `table_name` column to preserve table semantics.

## Notes
- Arabic text and numerals are fully supported.

## How to Run
Open the notebook in Google Colab and run the cells sequentially.

---
