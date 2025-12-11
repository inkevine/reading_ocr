**Printed Text Scanner (PyQt5 + PyTesseract)**

A simple desktop application that scans printed text from images or a webcam.
You can draw a region of interest (ROI), run OCR on that area, and view or save the results.

**Features**

Load images

Live webcam preview

Capture frame

Draw ROI

Run OCR

Show detected text

Save images with overlays

**Requirements**

Install required Python packages:

pip install opencv-python numpy Pillow pytesseract PyQt5


Install Tesseract OCR:

Windows: https://github.com/tesseract-ocr/tesseract

Linux:

sudo apt install tesseract-ocr libtesseract-dev


macOS:

brew install tesseract

**How to Run**
python main.py

**How to Use**

Load an image or start the camera

(Optional) Draw an ROI

Click “Run OCR”

View extracted text

Save overlay if needed
