# Tesseract OCR Installation Guide

Tesseract is an open-source Optical Character Recognition (OCR) engine that can recognize text in images. To install Tesseract and its associated language data (tessdata) on your system, follow the instructions below.

## Python

pip install pytesseract

repo: https://github.com/tesseract-ocr/tesseract

## Windows

1. **Download Tesseract**: The latest installers for Tesseract OCR can be found on the GitHub [releases page](https://github.com/UB-Mannheim/tesseract/wiki). Download the appropriate version for your system (32-bit or 64-bit).

2. **Install Tesseract**: Run the downloaded installer. We recommend using the default settings for installation.

3. **Set the Tesseract path in your Environment Variables**: 
    - Right-click on 'This PC' (or 'My Computer') and choose 'Properties'.
    - Click on 'Advanced system settings'.
    - Click on 'Environment Variables...'.
    - In the System Variables section, find the 'Path' variable, select it and click on 'Edit'.
    - In the 'Edit Environment Variable' window, click 'New' and add the path where the Tesseract-OCR has been installed (for example, `C:\Program Files\Tesseract-OCR`).

4. **Verify Installation**: Open a new command prompt and run `tesseract -v`. If Tesseract has been installed correctly, the version number of the Tesseract engine will be displayed.

## Linux (Ubuntu)

1. **Install Tesseract**: You can install Tesseract directly from the Ubuntu repositories. Open a terminal and run the following command:

```shell
sudo apt install tesseract-ocr
```

* https://github.com/tesseract-ocr/tessdata 
* download tessdata and replace it in your tessearct-ocr dir.