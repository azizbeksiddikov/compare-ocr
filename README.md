# Text Detection & OCR Comparison

This repository demonstrates how to:

- Preprocess textual data from CSV.
- Perform OCR with Tesseract and EasyOCR.
- Compare performance based on:
  - Similarity score (intersection/union of characters).
  - Processing time.

## Quick Start

1. Clone repository
2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Ensure you have:

   - **Tesseract** installed (e.g., via Homebrew on macOS: `brew install tesseract`).
   - **EasyOCR** installed (Python library).

## Files

- **main.ipynb**: Main notebook that loads images, performs OCR (Tesseract & EasyOCR), calculates similarities, and prints results.
- **data/annotations.csv**: Example annotations for text in images, converted to labeled .txt files.
- **data/images/**: Directory containing images.
- **data/labels/**: Directory containing ground-truth text files for each image.
