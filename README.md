# Convert-100-Images-To-GrayScale
## Demo

![ezgif-1-cc925d5e39](https://github.com/NamanChaudhary1/Convert-100-Images-To-GrayScale/assets/91721649/846042f4-e308-4adc-91c6-84f7865ccf51)


## Features

- Downloads images from a web page
- Converts images to grayscale
- Extracts text from the images using OCR
- Converts the extracted text to audio

## How it Works

1. Specify the URL of the web page containing the images you want to convert.

2. The script downloads the images from the specified URL.

3. Each downloaded image is converted to grayscale using OpenCV.

4. OCR is applied to the grayscale image to extract text from it. The Tesseract OCR engine is used for this purpose.

5. The extracted text is then converted to audio using text-to-speech synthesis. The pyttsx3 library is used for text-to-speech conversion.

6. The converted grayscale images and audio files are saved in the output directory.

## Requirements

- Python 3.x
- OpenCV
- Tesseract OCR
- pytesseract
- pyttsx3

Acknowledgments
Special thanks to the creators of OpenCV, Tesseract OCR, pytesseract, and pyttsx3 for their amazing libraries.
