# Robust-Text-Extraction-from-Painted-Screenshots-Using-Adaptive-Inpainting-and-OCR
Extracts text from screenshots with painted areas using OpenCV inpainting and Tesseract OCR for improved accuracy.

# Painted Text Extraction from Screenshots

This project extracts text from screenshots that have painted or obscured areas by using OpenCV for adaptive inpainting and Tesseract OCR for text recognition.

## Features
- Handles painted/colored regions using color thresholding and mask creation.
- Applies inpainting techniques to reconstruct obscured text areas.
- Uses Tesseract OCR to extract clear text from processed images.

## Installation

```bash
pip install pytesseract opencv-python --upgrade
apt-get install tesseract-ocr

Usage
from painted_text_extraction import read_painted_text

image_path = 'path_to_screenshot.png'
text = read_painted_text(image_path)
print(text)

Description
Improves OCR accuracy on screenshots with painted sections by reconstructing missing parts before extracting text.

License
HIT License
