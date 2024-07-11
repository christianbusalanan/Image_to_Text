# Image to Text Conversion using Pytesseract and OpenCV

This project demonstrates how to perform Optical Character Recognition (OCR) on images using Pytesseract and OpenCV `cv2` in Python.

## Overview

OCR is a technology that extracts text from images. In this project, we utilize Pytesseract, which is a Python wrapper for Google's Tesseract-OCR Engine, and OpenCV `cv2` for image processing tasks.

### Features

- Load images from file using OpenCV `cv2.imread()`
- Preprocess images for better OCR accuracy (e.g., grayscale conversion, resizing)
- Use Pytesseract `pytesseract.image_to_string()` to extract text from images
- Display original and processed images using OpenCV `cv2.imshow()`

## Requirements

- Python 3.x
- OpenCV `opencv-python`
- Pytesseract `pytesseract`

## Quick Sample

1. **Loading Image**:

   ![Example Image](https://github.com/christianbusalanan/image_to_text/blob/main/atomichabits%20(1).jpg)

   This is a sample image input
2. **Converting Image to Text**
   
   ![Example Image](https://github.com/christianbusalanan/image_to_text/blob/main/sample_output.PNG)
   
   This is the output, and can now be copied and pasted.
