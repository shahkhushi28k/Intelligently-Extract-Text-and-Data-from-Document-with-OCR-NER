# Document Scanner and Entity Recognition

## General Info

This project utilizes classic Optical Character Recognition (OCR) methods combined with Named Entity Recognition (NER) technology within a trained algorithm designed for processing business cards.

**PL:** Klasyczna metoda przetwarzania oraz wyodrębniania tekstu z obrazu (OCR) we współpracy z technologią rozpoznawania jednostek (NER) w przeszkolonym algorytmie na podstawie zbioru wizytówek.

## Technologies

- Python
- Jupyter Notebook
- OCR
  - OpenCV
  - Tesseract OCR
- NER
  - Pandas
  - SpaCy
  - RegEx

## Solution Architecture

The solution involves computer vision for scanning and extracting text from images, and natural language processing for identifying entities from text. The process can be summarized as follows:

1. Computer vision scans the document to identify text positions and extract text from the image.
2. OCR technology reads the document image to extract editable text.
3. Extracted text undergoes preprocessing and cleaning.
4. Text data is labeled using the BIO system to train the NER model.
5. The NER model is trained to recognize named entities (e.g., names, organizations).
6. Named entities are extracted from documents.

## Process Flow

The process flow and operation of the application can be described in ten steps:

1. Document submission via desktop or mobile devices.
2. Collection of scanned or photographed paper documents, forms, and emails.
3. Accumulation of a document dataset.
4. OCR analysis of document scans and photos.
5. Extraction of text from documents.
6. Preprocessing and cleaning of text data.
7. Labeling text data using the BIO tagging system for NER training.
8. Training the NER model.
9. Extraction of named entities from document text.
10. Presentation or storage of extracted entity data.

## Setup

### Prerequisites

Ensure you have Python 3.x installed along with the required libraries listed in `requirements.txt`.

### Installation

1. Clone the repository:
   git clone https://github.com/your-username/document-scanner.git
   cd document-scanner

2. Install dependencies:
   pip install -r requirements.txt

3. Usage
   Place your document images in a directory accessible to the script.
   Run the main script:
       python main.py
   View the annotated images with recognized entities and check the extracted entity information printed to the console.
   
![image](https://github.com/shahkhushi28k/Intelligently-Extract-Text-and-Data-from-Document-with-OCR-NER/assets/127178469/02955d17-3b03-4967-9ca7-582e3aa2713f)
